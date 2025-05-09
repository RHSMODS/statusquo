# Patches

## Patch Objects

To follow this tutorial you can use the following Blender file that contains all the geometry necessary to create new patches on your own (either by swapping the textures of this sample or creating your own shape geometry). This tutorial will not teach you how to UV and texture, so pre-existing knowledge of these topics is required.

{% file src="../../../.gitbook/assets/rhs_patch_sample.blend" %}

When you open the file you will see the following:

<figure><img src="../../../.gitbook/assets/image (163).png" alt=""><figcaption></figcaption></figure>

The highlighted object is the patch geometry, and the purple box is the collider. You can leave the collider as is.

Patches in RHS follow very simple rules:

* No bones or rigging necessary
* The world origin must be at backside (velcro) of the patch center

<figure><img src="../../../.gitbook/assets/image (164).png" alt=""><figcaption></figcaption></figure>

* The patch must be facing in the direction of Y+ axis

<figure><img src="../../../.gitbook/assets/image (165).png" alt=""><figcaption></figcaption></figure>

* You can use morphs to make them fit the curvature of the objects they are attached to.

### Morph Targets

In order to ensure the curving of the patch on rounded objects such as helmets and sleeves, you can add a "Curve" shape key and modify the geometry to fit with the sample above. The **Curve** key at 1.0 setting is the maximum curvature. The **Basis** key should represent your patch in fully flat position.

<figure><img src="../../../.gitbook/assets/image (166).png" alt=""><figcaption></figcaption></figure>

When you are importing your FBX into Workbench, make sure the Export Morphs import setting is enabled.

<figure><img src="../../../.gitbook/assets/image (167).png" alt=""><figcaption></figcaption></figure>

You will then be able to control the morph in the xob editor, but you can leave it at 0:

<figure><img src="../../../.gitbook/assets/image (168).png" alt=""><figcaption></figcaption></figure>

### Prefab

While you are making your own mod with RHS: Status Quo as dependency, find **Patch\_Base.et** in SQ and right click on it. Select "Inherit in 'MyNewPatchMod'". This should prompt you to create a new inherited prefab in your own mod. Edit this prefab.

In the **InventoryItemComponent** change the **Name** and **Description** values.

<figure><img src="../../../.gitbook/assets/image (169).png" alt=""><figcaption></figcaption></figure>

In the **MeshObject** component set the **Object** value to your newly created xob.

{% hint style="info" %}
NOTE: If you are just changing textures and using the same mesh for the patches, then just change the material. You dont need a new xob for every patch.
{% endhint %}

<figure><img src="../../../.gitbook/assets/image (170).png" alt=""><figcaption></figcaption></figure>

In the **BaseLoadoutClothComponent** change the material overrides like shown below to your new materials. Change the **Area Type** value if necessary (just filter for Velcro to find all RHS velcto area types) depending on the general size of your patch.

<figure><img src="../../../.gitbook/assets/image (171).png" alt=""><figcaption></figcaption></figure>

Your patch is now ready to be accepted on RHS patch system compliant cloth items.

## Receiving Objects

If you are setting up cloth items that should receive patches there are a few steps that are different for objects like Helmets, Jackets and Vests, because they interact with the AR inventory system differently.

{% hint style="warning" %}
The simplest approach for any item type is to **inherit** from a pre-existing RHS object that most closely resembles your new object.
{% endhint %}

### Headgear

First add a **RHS\_ClothNodeStorageComponent** and set it up in a similar fashion, changing values where appropriate:

<figure><img src="../../../.gitbook/assets/image (172).png" alt=""><figcaption></figcaption></figure>

In the **BaseLoadoutClothComponent** make sure you have **Debug Worn Model** value set to true when editing positions of velcro attachment slots.

{% hint style="info" %}
Do not forget to turn **Debug Worn Model** to off when you are done editing.
{% endhint %}

<figure><img src="../../../.gitbook/assets/image (173).png" alt=""><figcaption></figcaption></figure>

In the **Slots** array of **BaseLoadoutClothComponent** make an new slot of type **RHS\_LoadoutSlotInfo**. The name of the slot MUST be one of the following (Top Velcro, Left Velcro, etc.). If you name it wrong it will not work:

<figure><img src="../../../.gitbook/assets/image (174).png" alt=""><figcaption></figcaption></figure>

Use the following reference to set up the slot:

<figure><img src="../../../.gitbook/assets/image (175).png" alt=""><figcaption></figcaption></figure>

The **Offset and Angle** properties should be used to align the patch positioning. Load a patch prefab into the **Prefab** property to see it while modifying position:

<figure><img src="../../../.gitbook/assets/image (176).png" alt=""><figcaption></figcaption></figure>

Set the Name and Area Type settings appropriate for your patch attachment (name must be same as the slot name and area type must be one of the RHS velcro slot areas). Use morph settings to indicate how much the patch should bend if it has morphs:

<figure><img src="../../../.gitbook/assets/image (177).png" alt=""><figcaption></figcaption></figure>

**Morph Value** setting indicates by how much between 0 and 1 the patch will bend.

### Vests

For armored vests the setup is exactly the same as for helmets but the name of the slot should be **ChestVelcro**.

### Jackets

For jackets and other upper torso objects, the component structure is a little bit different:

<figure><img src="../../../.gitbook/assets/image (179).png" alt=""><figcaption></figcaption></figure>

The **RHS\_ClothNodeStorageComponent** must be setup with above settings as a child of **SCR\_UniversalInventoryStorageCOmponent** that is setup as follows:

<figure><img src="../../../.gitbook/assets/image (180).png" alt=""><figcaption></figcaption></figure>

The **BaseLoadoutClothComponent** is then setup ehactly the same way as for the Headgear:

<figure><img src="../../../.gitbook/assets/image (181).png" alt=""><figcaption></figcaption></figure>

Note that the slot names **SleeveRight and LeftVelcro** must be maintained for it to work.
