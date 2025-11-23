---
description: This guide is about making custom pouch presets using Enfusion tools.
cover: ../../../.gitbook/assets/image (188).png
coverY: 0
---

# Custom pouch presets

{% hint style="danger" %}
Keep in mind that our systems tend to change without instant changes in documentation. So this guide may be outdated at some point.
{% endhint %}

{% hint style="warning" %}
Please. Read this guide from start to end BEFORE making your own prefab.
{% endhint %}

{% hint style="info" %}
Last thing before this guide starts. When unsure about anything, check how it's done in existing RHS prefabs.
{% endhint %}

{% embed url="https://youtu.be/LH7rc0Dsf9Y" %}

## Step 1: Prefab

Lets start with inheriting our custom pouch preset from [Vest\_Base](https://enfusionengine.com/api/redirect?to=enfusion://ResourceManager/~RHSStatusQuo:Prefabs/Characters/Core/RHS_Vest_Base.et)\
After that we can open it. If you want to use inflatable pouches on your preset, you need to add a SignalsManagerComponent

![](<../../../.gitbook/assets/image (189).png>)

and SCR\_UniversalInventoryStorageComponent.

![](<../../../.gitbook/assets/image (197).png>)

I'm not gonna go into details about configuring SCR\_UniversalInventoryStorageComponent, just use existing RHS prefabs as reference. F.e Vest\_PCGen\_III\_Loadout\_base

## Step 2: Mesh

Start with putting mesh of the vest you want to make pouch preset for in MeshObject and BaseLoadoutCloth component. In our case we will use NCPC as example.

{% hint style="warning" %}
We gonna need it only temporary, just to be able to parent our pouches to bones on character.
{% endhint %}

<figure><img src="../../../.gitbook/assets/image (190) (1).png" alt=""><figcaption></figcaption></figure>

You need to put worn model not \_ground one.

<figure><img src="../../../.gitbook/assets/image (191).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../../.gitbook/assets/image (193).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../../.gitbook/assets/image (194).png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
Keep in mind that we will remove model from pouch preset later. Once again, we need it only temporary, just to be able to parent our pouches to bones on character.
{% endhint %}

## Part 3: Configuration

Now you can go to BaseLoadoutClothComponent and create a new slot. It should be LoadoutSlotInfo.

Then you can put a pouch you want to attach in prefab slot.\
Pouches can be found in these folders:

1. Vest\_PCGen\_III\_Pouches
2. Vest\_CPC\_NCPC\_pouches
3. Vest\_AACPC\_Pouches
4. Vest\_Taktika\_Pouches
5. Vest\_TV110\_Pouches

And after that parent it to bone[^1]

<figure><img src="../../../.gitbook/assets/image (196).png" alt=""><figcaption><p>Make sure to have exactly same checkboxes checked as on this screenshot</p></figcaption></figure>

## Step 4: Final touches

After you done with all steps mentioned above, it's time to replace temp meshes with invisible ones.

put **rhs\_equipment\_empty\_item.xob** in **meshobject**

<figure><img src="../../../.gitbook/assets/image (199).png" alt=""><figcaption></figcaption></figure>

put **rhs\_equipment\_empty\_item.xob** in Item Model\
put **rhs\_equipment\_empty.xob** in Worn model

<figure><img src="../../../.gitbook/assets/image (200).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
You may want to ask, "What if i want to have a belt as well?
{% endhint %}

It is as simple as it sounds, instead of **rhs\_equipment\_empty\_item.xob** and **rhs\_equipment\_empty.xob** put corresponding meshes of belt.

Once again, instead of guessing how it should look like, just check how it's done in our prefabs.\
![](<../../../.gitbook/assets/image (201).png>)

[^1]: if you dont know what are you doing, always use spine5 for pouches on platecarrier and spine1 for pouches on belt
