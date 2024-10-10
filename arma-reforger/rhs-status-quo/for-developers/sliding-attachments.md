# Sliding Attachments

The information provided here will allow you to set up the rail sliding system on your weapon and attachment. This system allows the weapon slot position to be manipulatable via actions, moving the attachment (for example optic) backwards or forwards. In some cases you can also specify that the eye location shoild remain the same, making the optic apper smaller or larger on screen as it is moved.

<figure><img src="../../../.gitbook/assets/image (220).png" alt=""><figcaption><p>Optic in forward position</p></figcaption></figure>

<figure><img src="../../../.gitbook/assets/image (223).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../../.gitbook/assets/image (221).png" alt=""><figcaption><p>Optic in back position</p></figcaption></figure>

<figure><img src="../../../.gitbook/assets/image (222).png" alt=""><figcaption></figcaption></figure>

## Weapon Setup

First lets start with the weapon rail setup. First you need to add a **RHS\_WeaponRplComponent** to the weapon prefab. Do this to the top prefab in the inheritance tree. No parameters for this component need to be set as it is solely responsible for replicating the position of the attachment between clients in multiplayer games.

<figure><img src="../../../.gitbook/assets/image (224).png" alt=""><figcaption></figcaption></figure>

Then locate (or create) the AttachmentSlotComponent that you want to enable sliding on.

<figure><img src="../../../.gitbook/assets/image (225).png" alt=""><figcaption></figcaption></figure>

Right click on the InventoryStorageSlot and pick **RHS\_SlidingInventoryStorageSlot**.

<figure><img src="../../../.gitbook/assets/image (226).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../../.gitbook/assets/image (227).png" alt=""><figcaption></figcaption></figure>

This should keep the initial setup of the slot as it was and add a few extra options.

<figure><img src="../../../.gitbook/assets/image (228).png" alt=""><figcaption></figcaption></figure>

To set this up properly we need to take a closer look at the rail and the current default attachment point. Select the Offset propery of the attachment slot to visualise the attachment point position.

<figure><img src="../../../.gitbook/assets/image (229).png" alt=""><figcaption></figcaption></figure>

No you need to calculate how much movement forward and backward relative to this point is possible. You can do this by counting the number of notches ahead and behind the spot. NOTE: do not worry yet about the size of the optic base itself. That will be set in the optic iteself.

In this case there are 11 notches in front of the point and 7 behind. These correspond to possible range of motion between -7 and +11 cm and standard spacing (and this increments of movement) is 1cm. In meters this is -0.07 and 0.11 respectively.

Set the **Maximum Positive Slide Offset** to 0.11 and **Maximum Negative Slide Offset** to -0.07.

<figure><img src="../../../.gitbook/assets/image (230).png" alt=""><figcaption></figcaption></figure>

The **Current Slide Offset** defines the default position offset and can be left at 0 in most cases.

{% hint style="info" %}
If you already have a weapon that derives from this prefab and changes something in the AttachmentSlotComponent, you have to make sure you switch the class in that prefab as well.
{% endhint %}

This concludes the weapon setup. Now every attachment which implements the system as described in the following section should be able to slide the attachment back and forth. This behaviour is visible to other players online and the position should persist at respawn if you save it in the arsenal.

## Attachment Setup

To make the attachment compatible, you need to add an action of type RHS\_SlideAttachmentAction to its ActionManagerComponent additional actions. See the settings below.

<figure><img src="../../../.gitbook/assets/image (231).png" alt=""><figcaption></figcaption></figure>

Keep all properties as shown except for two important ones:

* **Affect Eye Distance For Optic** - (currently only works for optics implementing the RHS\_CollimatorSightsComponent) when checked keeps the eye at same absolute point relative to the weapon, i.e. the eye does not slide with the weapon.
* **Base Half Length** - this should be set to half the length of the base of the attachment. So if your optic has an attachment base of 4 cm this should be set to 0.02. This makes sure that the optic does not hang in front or back of the rail.
