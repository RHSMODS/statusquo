---
description: >-
  This document is regenerated automatically from our systems at a time of a
  release.
---

# Changelog

{% hint style="warning" %}
If stable RHS: Status Quo release is preceded by one or more experimental releases (not dev), then the changelog between this stable release and last stable release should be considered the combination of all the experimental changelogs in between as well as the changelog between the last experimental and stable release.
{% endhint %}

## 0.8.2268

{% hint style="info" %}
#### **Release Meta Information**

_<mark style="color:red;">Built from Revision:</mark>_ 2268

_<mark style="color:red;">Date:</mark>_ Tuesday, February 20, 2024

_<mark style="color:red;">Revisions Since Last:</mark>_ 3 (2265)

_<mark style="color:red;">Changes:</mark>_ 14 additions, 28 improvements, 27 fixes and 1 deletions.
{% endhint %}

{% hint style="danger" %}
This release is only available on **Arma: Reforger Experimental**
{% endhint %}

**Added**

\[Added] 30mm HE explosion sounds

\[Added] 30mm, 125mm and 122mm shells sonic cracks and flybyes added (need test)

\[Added] Added X Ultra pioneer boots

\[Added] Added X Ultra 4 boots

\[Added] Added G3 pants (ATACS-FG)

\[Added] Added G3 pants (OD)

\[Added] Added G3 pants (Multicam)

\[Added] Added voice notifications to T14 and K17

\[Added] Daniel Offense 9.55' ,12.25' ,12.25' FSP variants

\[Added] Daniel Offense FDE & BLK set colors

\[Added] Added AK-105

\[Added] Added M4A1 with Ergo Forward Rail Extension and AFG-2 (AFG not mountable yet)

\[Added] 10.3' ,14.5' ,14.5' HB Barrels & Textures

\[Added] SureFure 4 Prong Flashhider

**Improved**

\[Improved] Shell hit sounds

\[Improved] Sonic cracks for shells

\[Improved] Kh55 engine sound

\[Improved] Kh55 sounds and particles

\[Improved] Improved 6B47 mesh

\[Improved] Potential compatibility fix for item insertion into pouches

\[Improved] Added new pouch to PCGEN3 rifleman loadout

\[Improved] Regenerated K17 editor previews + fixed their import settings

\[Improved] Regenerated preview images for 2S1 & IL76

\[Improved] Corrected inspection slot position for PC Gen III Vest with pouches

\[Improved] Increased supply storage on K17 Unarmed

\[Improved] Added LODs to rhs\_su230

\[Improved] Added LODs to rhs\_su230\_mrds

\[Improved] Added LODs to rhs\_pouch\_6X9-1\_bayonet

\[Improved] Added LODs to rhs\_scabbard\_6X9-1\_bayonet

\[Improved] Added LODs to FILBE\_hydration\_pack

\[Improved] Added LODs to FILBE\_hydration\_pack\_ground

\[Improved] Added LODs to r187p1

\[Improved] Added LODs to garmin\_tactix\_bravo

\[Improved] Added LODs to anpeq15

\[Improved] Added LODs to aksu\_ltsu

\[Improved] Added LODs to rpk74m

\[Improved] Added LODs to m27iar

\[Improved] Helstar and MS2k are oriented in same way now, so both should be attachable to top and back Velcro on helmets; fixes [#608](https://github.com/RHSMODS/statusquo/issues/608)

\[Improved] Added localization for MP-443 pistol

\[Improved] MS2k, HELLSTAR6 and VIP Strobes can now be attached both to helmet top and back velcro slots; fixes [#668](https://github.com/RHSMODS/statusquo/issues/668)

\[Improved] Changed K-17 armor (Sides 35mm->20mm. Side UParmor 30mm->10mm. Front UParmor 40mm->15mm. Interior armor 30mm->5mm). It means that K-17 side armor is now vulnerable to 12.7 AP. However it doesnt mean that you can flame it by just shooting at passanger compartment. You still need to target engine, fuel tanks, and other critical elements.

\[Improved] Tweaked RPK-74M textures.

**Fixed**

\[Fixed] Custom bullet flyby sounds not working

\[Fixed] Fixed some of the broken PiP scopes after AR update

\[Fixed] Fixed radial menu entry null reference exception with shadow item

\[Fixed] Not being able to control attached light devices and missing radial menu actions; fixes [#653](https://github.com/RHSMODS/statusquo/issues/653) and [#655](https://github.com/RHSMODS/statusquo/issues/655)

\[Fixed] Patches that were attached to the helmet would be visible in FPP; fixes [#654](https://github.com/RHSMODS/statusquo/issues/654)

\[Fixed] Being able to put backpack radio into taktika radio pouch

\[Fixed] Fixed RITA turn off button was doing nothing

\[Fixed] Fixed T14 Turret now can be repaired

\[Fixed] Fixed G45 was falling through the ground

\[Fixed] Fixed G17 was falling through the ground

\[Fixed] Fixed MP443 was falling through the ground

\[Fixed] Fixed APS was falling through the ground

\[Fixed] Fixed SP81 was falling through the ground

\[Fixed] Not being able to use NVG when aiming with glocks/m17/m18

\[Fixed] Fixed 1PN93 PiP sights; fixes [#649](https://github.com/RHSMODS/statusquo/issues/649)

\[Fixed] Fixed MS2K placement on helmets; fixes [#643](https://github.com/RHSMODS/statusquo/issues/643)

\[Fixed] Inventory icon for A Pos blood patch was not working; fixes [#628](https://github.com/RHSMODS/statusquo/issues/628)

\[Fixed] Removed default helmet cover from Kiver which should fix an issue where player would respawn with default cover even when they saved their loadout with different cover attached

\[Fixed] Wrong name shown in some cases for VIP Strobe; fixes [#656](https://github.com/RHSMODS/statusquo/issues/656)

\[Fixed] Fixed TSh-4 wrong weight

\[Fixed] Fixed BallCap wrong weight

\[Fixed] Fixed Shemagh wrong weight

\[Fixed] Fixed Beanie wrong weight

\[Fixed] Fixed K-17 causing Game crash

\[Fixed] Not being able to attach strobes to the helmets

\[Fixed] Fixed barrel texture on RPK-74 not working anymore.

\[Fixed] Scripts compile for 1.1 and version bumped to 0.8

**Deleted**

\[Removed] Disabled Environment probe in k-17 due poor optimization
