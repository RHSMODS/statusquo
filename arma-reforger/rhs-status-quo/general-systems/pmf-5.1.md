---
description: >-
  PMF-5.1 Is a MFD system that's used in APCs, Tanks, and MRAPs such as  T-14,
  T-15, K-17, K-16, Typhoon-K
---

# PMF-5.1



## Part 1. Introduction

PMF-5.1 Is a black display with 11 button around it. You can also identify it by ПМФ-5.1 written on top left corner of a display.\


<figure><img src="../../../.gitbook/assets/image (202).png" alt=""><figcaption></figcaption></figure>

To start interacting with it, turn it on by interacting with "Power" action.\


<figure><img src="../../../.gitbook/assets/image (203).png" alt=""><figcaption></figcaption></figure>

After that you will see boot menu appear.\


<figure><img src="../../../.gitbook/assets/image (204).png" alt=""><figcaption></figcaption></figure>

And not so long after, main menu will appear.

<figure><img src="../../../.gitbook/assets/image (205).png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
Before we continue with details of PMF subsystem, i feel like i need to mention that PMF-5.1 is a self sustainable device based on Linux kernel. It will continue working even if entire vehicle lost power or connection with main data bus was lost.
{% endhint %}

This is how main data bus and data processors look in K-17. PMF will cease to display all data that's collected for vehicle when these are damaged.

<figure><img src="../../../.gitbook/assets/image (206).png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
Another thing that you need to keep in mind, that all PMF displays are connected to main bus separately, so, if you're lucky enough, after main bus or data processors are damaged, some PMF displays will continue to receive data from it.&#x20;
{% endhint %}

<figure><img src="../../../.gitbook/assets/image (214).png" alt=""><figcaption></figcaption></figure>

If you see this error message, it means that this PMF display is now disconnected from main data bus. It either means that you're unlucky and main bus damage killed connection with your PMF, or that entire data bus ceased to exist.

## Part 2. Functionality

{% hint style="warning" %}
This is always subject to change, new systems may appear or major changes may happen without changes in this documentation.
{% endhint %}

Lets start with translating information we have in main menu.\


<figure><img src="../../../.gitbook/assets/image (207).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Turret and CMD turret are both indicating corresponding turret local (from vehicle body) rotation in soviet radians. Both are starting from 30-00 (Turret is heading front of the vehicle).
{% endhint %}

{% hint style="info" %}
Orientation displays current rotation of vehicle using sensors installed on vehicle.
{% endhint %}

{% hint style="info" %}
Ammunition will display info about ammunition later.
{% endhint %}

{% hint style="info" %}
Logs are displaying amount of system logs.
{% endhint %}

{% hint style="info" %}
System status displays information about state of various systems. Will be added in future.
{% endhint %}

## Part 3. Systems

<figure><img src="../../../.gitbook/assets/image (208).png" alt=""><figcaption></figcaption></figure>

Lets dive deeper into each system currently available.

### 1. Observation

<figure><img src="../../../.gitbook/assets/image (209).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
To switch between cameras, simply swipe screen to the left or right.
{% endhint %}

{% hint style="info" %}
Shutters button will allow user to close camera shutters later in future.
{% endhint %}

{% hint style="info" %}
Scan button turns on angle to angle scan mode for selected camera.
{% endhint %}

{% hint style="info" %}
Filter button allows user to cycle between brightness levels.
{% endhint %}

{% hint style="info" %}
Zoom buttons are pretty self explanatory.
{% endhint %}

{% hint style="info" %}
Auto detection button is responsible for turning on and off auto target detection. For now it's always active.
{% endhint %}

{% hint style="info" %}
Auto following button should follow selected target with cameras. Not active for now.
{% endhint %}

{% hint style="info" %}
Target lock button should transfer target data to commander turret. Not active for now.
{% endhint %}

### 2. Correction

Not active for now. Will be used to change brightness and contrast of gunner display on T-14 later in future.

<figure><img src="../../../.gitbook/assets/image (210).png" alt=""><figcaption></figcaption></figure>

### 3. Vehicle status.

<figure><img src="../../../.gitbook/assets/image (211).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../../.gitbook/assets/image (212).png" alt=""><figcaption></figcaption></figure>

### 4. Misc apps

This may sound like a tab with other apps but it actually leads to system desktop.&#x20;

<figure><img src="../../../.gitbook/assets/image (213).png" alt=""><figcaption><p>cat.</p></figcaption></figure>

Not much is active here. Perhaps later you will be able to find more useful stuff or maybe even games here. In order to go back to PMF subsystem, open `ПМФ_5.0_Ж12.exe`.



##
