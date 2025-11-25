---
description: >-
  This guide will show you how to create your own custom pouch presets using the
  RHS mod within the Enfusion Tools for Arma Reforger.  Alternatively, you can
  watch the below video by TPM Tactical.
cover: ../../../.gitbook/assets/image (188).png
coverY: 0
layout:
  width: default
  cover:
    visible: true
    size: full
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
  metadata:
    visible: true
---

# Creating Custom Pouch Presets

{% hint style="danger" %}
Keep in mind that our systems tend to change without instant changes in documentation. So this guide may be outdated at some point.
{% endhint %}

{% hint style="info" %}
Please. Read this guide from start to end BEFORE making your own prefab.
{% endhint %}

{% hint style="info" %}
This guide assumes you know how to open Enfusion Tools and add RHS as a dependency to your project.
{% endhint %}

{% hint style="info" %}
Last thing, please make sure you check existing RHS prefabs to see exactly what components and settings have been used.
{% endhint %}

{% embed url="https://youtu.be/LH7rc0Dsf9Y" %}

## Step 1: Creating Prefab

* The first step is to locate [Vest\_Base.et](https://enfusionengine.com/api/redirect?to=enfusion://ResourceManager/~ArmaReforger:Prefabs/Characters/Core/Vest_Base.et).  At the top left in the resource browser, search for Vest\_Base.  It will be located within the ArmaReforger directory.
* Once located, right click Vest\_Base.et and select 'Inherit in \<yourprojectname>' and give your prefab a name.

<figure><img src="../../../.gitbook/assets/image.png" alt=""><figcaption></figcaption></figure>

* Located your newly created prefab, right click and select 'Edit Prefab' and the World Editor window will open.

<figure><img src="../../../.gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>

* If you want to utilise the inflatable pouch system you will need to add the 'SignalsManagerComponent', by click '+Add Component' located down the bottom right of your screen and searching 'SignalsManagerComponent' and selecting the component.

<figure><img src="../../../.gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>

* Add 'RHS\_ClothNodeStorageComponent' following the same steps as adding the 'SignalsManagerComponent' from above.

## Step 2: Configure RHS\_ClothNodeStorageComponent'

* In your Object Properties window of your prefab, select 'RHS\_ClothNodeStorageComponet' and then click 'Set Class' in the Attributes section, followed by selecting 'SCR\_ItemAttributeCollection'.

<figure><img src="../../../.gitbook/assets/image (5).png" alt=""><figcaption></figcaption></figure>

* You will now need to configr your 'RHS\_ClothNodeStorageComponent' as per the below screenshot or your own settings.

<figure><img src="../../../.gitbook/assets/image (6).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../../.gitbook/assets/image (7).png" alt=""><figcaption></figcaption></figure>

## Step 3: Mesh

* In your prefabs Object Properties, select 'MeshObject' and then locate the .xob file of the vest you want to attach your pouches and insert into the 'Object' section as seen below.  The .xob files will be located within either RHS\_Content\_01 or 02.  [JPC example location](https://enfusionengine.com/api/redirect?to=enfusion://ResourceManager/~RHS_Content_01:Assets/Characters/Vests/Vest_JPC/JPC.xob).

{% hint style="info" %}
This .xob file will be used temporarily to allows us to set the pouches in the correct position and parent them to the bones of the character.
{% endhint %}

<figure><img src="../../../.gitbook/assets/image (8).png" alt=""><figcaption></figcaption></figure>

* In your Object Properties window, select 'BaseLoadoutClothComponent' and ensure 'LoadoutVestArea' is selected in the Area Type section.

<figure><img src="../../../.gitbook/assets/image (9).png" alt=""><figcaption></figcaption></figure>

* In your Object Properties window, select 'BaseLoadoutClothComponent' and ensure 'LoadoutVestArea' is selected in the Area Type section.
* Within the same area, insert the same .xob file which was used above into the Worn Model and Item Model sections.

<figure><img src="../../../.gitbook/assets/image (10).png" alt=""><figcaption></figcaption></figure>

* Click the '+' symbole to add element within the slots section and select 'LoadoutSlotInfo' and give the slot a name. Eg RadioPouch

<figure><img src="../../../.gitbook/assets/image (11).png" alt=""><figcaption></figcaption></figure>

* In the Pivot ID section, select 'Spine5' and now locate the prefab of the pouch you want to use and drag it into the Prefab section.  Prefabs are located within 'RHS\_Core'
* Click in the Offset/Angles sections to then move the prefab around to the desired location.  Repeat these steps to add further pouches into new slots.

<figure><img src="../../../.gitbook/assets/image (12).png" alt=""><figcaption></figcaption></figure>

* Once you have finished adding and adjusting your pouches, we need to replace the the .xob files of the vest we are using with an empty xob.  For example [rhs\_equipment\_empty.xob](https://enfusionengine.com/api/redirect?to=enfusion://ResourceManager/~RHS_Content_01:Assets/Characters/Vests/Vest_Common/rhs_equipment_empty.xob) and [rhs\_equipment\_empty\_item.xob](https://enfusionengine.com/api/redirect?to=enfusion://ResourceManager/~RHS_Content_01:Assets/Characters/Vests/Vest_Common/rhs_equipment_empty_item.xob)
* Locate the above 2 empty xob files and drag them into the 'BaseLoadoutClothComponent' and 'MeshObject' as seen below.

<figure><img src="../../../.gitbook/assets/image (13).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../../.gitbook/assets/image (14).png" alt=""><figcaption></figcaption></figure>

* You have now completed your pouch preset, please ensure you save your prefab before closing the window.
* To test, add it to one of your faction items entity catalogue.

## Step 4: Adding a Belt

* If you want to add a belt with pouches, drag a belt .xob file (worn not ground .xob file) into the MeshObjects and BaseLoadoutClothComponent model sections where the empty .xob files are located and follow the steps above for adding slots/pouches.

<figure><img src="../../../.gitbook/assets/image (15).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../../.gitbook/assets/image (16).png" alt=""><figcaption></figcaption></figure>

* Once you have placed the pouches to the desired location on the belt, replace the Item Model .xob file with the ground .xob file and save.&#x20;

<figure><img src="../../../.gitbook/assets/image (17).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
If you are unsure on a particular setting, check on of the RHS prefabs.
{% endhint %}

{% hint style="warning" %}
When publishing your mode, make sure to read the RHS EULA
{% endhint %}

