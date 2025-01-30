# Detacheable Bipods

{% hint style="info" %}
This system is still work in progress and may evolve in the future.
{% endhint %}

In version 0.10 of RHS: Status Quo a new system was added to enable attachment of modular (mainly picattiny) bipods. As this feature is not available in the vanilla game, a lot of scripting and setup work has gone in to make this possible. What was not possible, however, is to make this useable as an out-of-the-box feature for all weapons and some modifications to exisitng weapons is required to make it compatible.

The first section of this document describes the proper way to set up a weapon to be compatible with receiving the bipod attachment and properly respecting the dynamic point of deplyment depending on whether the bipod is stowed or not. The second section (to be added later at some point) deals with creating new bipods that support this functionality as well.

## Weapon Setup

Several steps need to be followed to properly enable the weapon to be compatible.

### 1. Bone

The main xob of the weapon, essentially waht is used as the basis for the weapon prefab should have bone called `bipod_pos` at the approximate location where the deployment point should be as if the bipod was NOT attached to the weapon. This will be the point the weapon well rest on obsticles by default.

<figure><img src="../../../.gitbook/assets/image (235).png" alt=""><figcaption></figcaption></figure>

This can be added as a memory point in Blender like so:

<figure><img src="../../../.gitbook/assets/image (236).png" alt=""><figcaption></figcaption></figure>

{% hint style="danger" %}
This bone is critical and the system will not work without it.
{% endhint %}

### 2. Prefab

In the weapon prefab (or parent thereof) you need to make some changes. First we will add a new  `AttachmentSlotComponent` as a child to the `WeaponComponent` to prepare a slot where the bipod can attach to:

<figure><img src="../../../.gitbook/assets/image (238).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../../.gitbook/assets/image (239).png" alt=""><figcaption></figcaption></figure>

Set the attachment slot properties as such:

<figure><img src="../../../.gitbook/assets/image (240).png" alt=""><figcaption></figcaption></figure>

Make sure the Attachment Type is set to `AttachmentRIS1913Bipod` so that the bipod can find the right slot and it is set to **Show in Inspection**. Manipulate the **Offset** and **Inspection Widget Offset** positions to be roughly at where the bipod should attach and ideally on the same horizontal position as you have placed tou `bipod_pos` bone.

{% hint style="danger" %}
Leave the Pivot ID property empty or at the very least do NOT set it to `bipod_pos`.
{% endhint %}

Finally edit the `SCR_WeaponAttachmentsStorageComponent` section of `AimingModifierAttributes` **Deployment Points** section to look exacly like below:

<figure><img src="../../../.gitbook/assets/image (241).png" alt=""><figcaption></figcaption></figure>

The most important part being that there is 1 stabilization point that is tied to the `bipod_pos` bone. When a bipod is attached, the system will recognise it and animate this bone, moving the stabilization point up and down. When bipod is not there it will be ignored. Normal bipod deployment actions and key bindings should work with it and it should propagate through multiplayer.

The final and most complex step is modifying the animation graphs of the weapon to inject the trigger variable that will animate the point. For this you will have to edit or create the signals and the ProcAnimParams for the weapon. If your weapon already has a `ProcAnimComponent` with a `.pap` file assigned we will need to edit it, otherwise you will need to create a new one.&#x20;

<figure><img src="../../../.gitbook/assets/image (243).png" alt=""><figcaption></figcaption></figure>

When editing your pap file, press **Signal** in top left corner and locate `bipod_signal.siga` in RHS mod files.

<figure><img src="../../../.gitbook/assets/image (244).png" alt=""><figcaption></figcaption></figure>

Your signal node will be created in the graph with a **DEPLOY\_HEIGHT** signal present. Add a Bone, TranslateMake and TranslateSet nodes onto the graph using the buttons in the top toolbar, and hook them up to the signal and together as such:

<figure><img src="../../../.gitbook/assets/image (245).png" alt=""><figcaption></figcaption></figure>

Only the **Bone** node needs editing, and there make sure to set the Bone name property to `bipod_pos` as shown. All other nodes can be left with default settings. Save your pap file and close the Procedural Anim editor.

{% hint style="info" %}
Important: if you alreasy use a siga file for your weapon, paste the nodes from the bipod\_signal.siga into your siga and hook up the nodes in the pap using the existing signal node:

![](<../../../.gitbook/assets/image (246).png>)
{% endhint %}

Now if you attach the bipod you will be able to see the bone animating when bipod is extended:

<figure><img src="../../../.gitbook/assets/image (247).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../../.gitbook/assets/image (248).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../../.gitbook/assets/image (249).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../../.gitbook/assets/image (250).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../../.gitbook/assets/image (242).png" alt=""><figcaption></figcaption></figure>

## Creating New Bipods

TBA
