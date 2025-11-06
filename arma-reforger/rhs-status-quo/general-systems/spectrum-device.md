---
description: >-
  The Spectrum Device is a handheld transceiver that can act as an
  electromagnetic spectrum analyzer.
cover: ../../../.gitbook/assets/image (3).png
coverY: 4.198350893266148
---

# Spectrum Device

## Part 1: Introduction

<figure><img src="../../../.gitbook/assets/image (1) (1).png" alt=""><figcaption><p>The Spectrum Device</p></figcaption></figure>

The Spectrum Device was developed thanks to advances in radio reconnaissance. It utilizes advanced processing technologies to detect and process signals in 3D space using a single receiver.

&#x20;

The Spectrum Device's capabilities include:

&#x20;

●     Minimum signal detection range: 20 meters

●     Maximum signal detection range: 4,000 meters

●     Weight: 2.5 Kg

{% hint style="warning" %}
Keep in mind that signal **detection** range is not equal to signal **processing** range.
{% endhint %}

## Part 2: Theory

Before proceeding to practical usage, we must discuss some foundational concepts.

An electromagnetic spectrum monitoring device detects and identifies active emitters of electromagnetic fields, such as transmitting walkie-talkies, radios, and radars. Many communication and surveillance systems emit signals, and this device can detect a broad range of frequencies, aiding in the identification of these sources and facilitating faster location of enemies.

&#x20;

It is important to note that the Spectrum Device is not a magic solution, but rather a sophisticated piece of innovative technology with inherent technical limitations. To ensure effective signal reception, the device must be kept steady and level with the horizon—a point further elaborated upon in the practical usage section.

&#x20;

Spectrum Devices utilize software processing and a single receiver to detect signals. However, challenging terrains, such as mountainous regions, can both obstruct signals and alter the device's signal perception. This can lead to complications such as signal piling, reflections, and other noise being incorrectly identified as genuine signals.

&#x20;

Radio signals can be obstructed by terrain, buildings, vehicles, or artificial interruptions, such as jammers. Additionally, radio signals are prone to reflection, which can create false noise—a significant concern in signal detection.

<figure><img src="../../../.gitbook/assets/image (10).png" alt=""><figcaption><p>Example of piled signals</p></figcaption></figure>

Because of these factors, signals can be classified into three types:

&#x20;

1\.    Unprocessed signal

2\.    Fake/Garbage signal

3\.    Real signal

How these signals are displayed will be explained later in this guide.\
\
Another important aspect is how signals are processed. Signal processing takes time, and for the Spectrum Device to effectively process a signal, the signal must be emitted for a sufficient duration. For example, handheld radios are only detectable when they are actively transmitting (e.g. when a user is speaking). This is where the impact of distance becomes apparent--the farther away the signal source is, the longer it takes to process the signal. You will notice this delay when tracking down an enemy far from your position.

&#x20;

Some sources emit signals continuously, such as stationary antennas, command trucks, transmission towers, and vehicles equipped with datalink systems.

{% hint style="danger" %}
This device can't see radios used by AI, because they never use them to speak to each other. Its usefulness therefore is mostly in Multiplayer against other players.
{% endhint %}

## Part 3: Controls

To move the cursor, hold the left mouse button (LMB).

<figure><img src="../../../.gitbook/assets/cursor_move.gif" alt=""><figcaption></figcaption></figure>

To adjust the zoom level, move the cursor to the bottom of the screen to decrease the scale or to the top to increase it.

<figure><img src="../../../.gitbook/assets/change_zoom.gif" alt=""><figcaption></figcaption></figure>

To interact with a signal, hover the cursor over it and press "F."

## Part 4: Usage and system info

The first thing you see is the boot screen, which takes about 2 seconds to start up.&#x20;

<figure><img src="../../../.gitbook/assets/image (4).png" alt=""><figcaption></figcaption></figure>

Once the boot sequence is complete, you will be directed to the main menu, known as the signal map.

<figure><img src="../../../.gitbook/assets/image (7).png" alt=""><figcaption></figcaption></figure>

To start detecting signals, you need to level the spectrum device with the horizon. Once the device is properly leveled, the direction arrow will disappear.

{% hint style="info" %}
You can reduce processing time by directly focusing on signals, which helps bypass some of the distortion calculations.
{% endhint %}

<figure><img src="../../../.gitbook/assets/image (6).png" alt=""><figcaption></figcaption></figure>

### Understanding the Display Information

<figure><img src="../../../.gitbook/assets/image (217).png" alt=""><figcaption></figcaption></figure>

Let's break down the information displayed on the screen:

&#x20;

●     ID: Displays the ID of the currently selected signal.

●     DIR: Shows the heading of the signal based on its last three positions.

●     DIST: Indicates the approximate distance to the signal.

●     DELAY: Displays the delay between when the signal was transmitted and when it was received. This can be used to roughly estimate the distance to signals that cannot be fully processed.

●     METADATA: Currently displays the cipher key of the processed signal.

●     FREQUENCY: Shows the frequency of the processed signal.

&#x20;

&#x20;

{% hint style="danger" %}
Please note that all information on the left is only accurate once the signal is fully processed.
{% endhint %}

<figure><img src="../../../.gitbook/assets/image (218).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../../.gitbook/assets/image (216).png" alt=""><figcaption></figcaption></figure>
