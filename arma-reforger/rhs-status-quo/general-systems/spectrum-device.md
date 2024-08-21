---
description: >-
  The Spectrum Device is a handheld transceiver that can act as an
  electromagnetic spectrum analyzer.
cover: ../../../.gitbook/assets/image (3).png
coverY: 4.198350893266148
layout:
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
---

# Spectrum Device



## Part 1: Introduction

<figure><img src="../../../.gitbook/assets/image (1).png" alt=""><figcaption><p>the Spectrum Device</p></figcaption></figure>

This device was made to advance in radio reconnaissance, and uses advanced processing technologies to allow detection and further processing of signal in 3D space with single receiver.&#x20;

Lets start with information about capabilities of this device.

Min signal detection range: 20m\
Max signal detection range: 4000m

{% hint style="warning" %}
Keep in mind that signal **detection** range is not equal to signal **processing** range
{% endhint %}

Weight: 2.5 Kg\




## Part 2: Theory

Before we move into practical usage, lets talk about some boring stuff.

First of all, spectrum device is not a magic wand, this is a very fine piece of innovative technologies. But just like any other equipment it got some technical limitations.&#x20;

First of all, in order to receive signals, you need to keep device steady and leveled to horizon, i will talk about it a little bit more later in practical usage.

It shouldn't be a surprise but radio signals can be obstructed by terrain, buildings, vehicles, or if we talk about artificial interruptions, by jammers.

Radio signals also tend to reflect and create fake noise. This is one of the most important things to worry about.

Spectrum device uses on single receiver and  software processing in order to detect signals.\
Rough terrains such as mountains can both obstruct and change how device sees signals. This leads to multiple issues, such as piling of signals, and signal reflections and other noise picked up as real signals.

<figure><img src="../../../.gitbook/assets/image (10).png" alt=""><figcaption><p>Example of piled signals</p></figcaption></figure>

Because of that, there are 3 types of signal:

1. Unprocessed signal
2. Fake/Garbage signal
3. Real signal

I will explain how they are displayed later in this guide.\


\
Probably last but not least thing that you need to know about is **Processing of signal**.\


Processing of signal takes time. Usually quite long amount of time. Time that you might not have. \
In order to crack the signal and process it, it needs to be emitted for enough time for spectrum device to process it. This is the point where you can see and feel the matter of distance. Further the signal is, longer it takes to process it. You can feel it when trying to track down enemy located far away from you. \
\
Although, you also need to keep in mind that some things are emitting signal constantly. Such as stationary antennas, command trucks, transmission towers, and vehicles equipped with datalink.\
\




## Part 3: Controls

In order to move cursor, you need hold LMB.

<figure><img src="../../../.gitbook/assets/cursor_move.gif" alt=""><figcaption></figcaption></figure>

To change zoom level, move cursor to the bottom to decrease scale, or to the top to increase it.

<figure><img src="../../../.gitbook/assets/change_zoom.gif" alt=""><figcaption></figcaption></figure>

To interact with signal hover cursor over it, and press F.

## Part 4: Usage and system info

First thing you see is booting screen. It takes around 2 seconds to boot system up.

<figure><img src="../../../.gitbook/assets/image (4).png" alt=""><figcaption></figcaption></figure>

Right after boot sequence you can see main menu. Aka signal map.

<figure><img src="../../../.gitbook/assets/image (7).png" alt=""><figcaption></figcaption></figure>

In order to start finding signals, you need to level spectrum device on horizon. When device is leveled, direction arrow should disappear.



{% hint style="info" %}
You can decrease processing time by looking at signals directly. That saves some time from distortion calculations.
{% endhint %}

<figure><img src="../../../.gitbook/assets/image (6).png" alt=""><figcaption></figcaption></figure>

Lets try to understand what kind of information we have on display.

<figure><img src="../../../.gitbook/assets/image (217).png" alt=""><figcaption></figcaption></figure>

ID on the left displays ID of currently selected signal.\
DIR displays heading of signal based on 3 last positions of signal.\
DIST displays rough distance to signal.\
DELAY displays delay from signal transmitted to signal recieved. Can be used to roughly estimate distance on signals that cannot be processed.\
METADATA: For now it displays cypher key of processed signal\
FREQUENCY: Frequency of processed signal.

{% hint style="danger" %}
Keep in mind that all information on the left is valid only after signal is fully processed.
{% endhint %}

<figure><img src="../../../.gitbook/assets/image (218).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../../.gitbook/assets/image (216).png" alt=""><figcaption></figcaption></figure>
