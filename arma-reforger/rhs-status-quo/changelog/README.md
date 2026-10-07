---
description: >-
  This document is regenerated automatically from our systems at a time of a
  release.
---

# Changelog

<!-- reset point -->
﻿<!-- changelog insert -->

## 0.17.5239

<!-- revision 5239 -->

{% hint style="info" %}
### **Release Meta Information**

_<mark style="color:red;">Built from Revision:</mark>_ 5239

_<mark style="color:red;">Date:</mark>_ Wednesday, October 7, 2026

_<mark style="color:red;">Revisions Since Last:</mark>_ 90 (5149)

_<mark style="color:red;">Changes:</mark>_ 10 additions, 11 improvements, 42 fixes and 5 deletions.
{% endhint %}


{% hint style="danger" %}
This release is only available on **Arma: Reforger Experimental**
{% endhint %}


##### Added


[Added] LBT-1961 and TT MK2 Strings, added to US and ION Arsenals

[Added] Added ARC V2 vest in RGR and MC variants

[Added] Added FILBE Assault backpack with radio

[Added] Added Matech BUIS

[Added] Added Radio_ANPRC152A_DEV.et (WIP), frequency switching implemented so far

[Added] Added new diag menu for creating touch-screen-based items (display bounds visualization, button visualization)

[Added] Added T14 turret depression limiter when rotating the turret towards the rear

[Added] Physics observer support to RHS_HelmetNodeStorageComponent for helmet knockoff handling

[Added] Knockoff support for RHS helmets with m_bIsDetachable enabled

[Added] Asset image generator script overrides


##### Improved


[Improved] M4A1 now equipped with Matech BUIS

[Improved] RHS_LoadoutSlotInfo improvements, thanks to Degman; fixes [#1440](https://github.com/RHSMODS/statusquo/issues/1440)

[Improved] Expose ClothNode Slotted Items in Backpack Inventory UI, thanks to Degman; fixes [#1441](https://github.com/RHSMODS/statusquo/issues/1441)

[Improved] RHS_MagazineAnimationComponent improvement, thanks to Degman; fixes [#1442](https://github.com/RHSMODS/statusquo/issues/1442)

[Improved] Typhoon windshield wipers can only be controlled by driver now; fixes [#1421](https://github.com/RHSMODS/statusquo/issues/1421)

[Improved] To UH1Y config files

[Improved] UH1Y blend files.

[Improved] 6B23 with 6Sh117 now blocks vest loadouts so you can no longer double layer

[Improved] Removed possibility to put armored plates into 6Sh117; fixes [#1457](https://github.com/RHSMODS/statusquo/issues/1457)

[Improved] Redone all vest prefab inventory previews

[Improved] Various weapon prefabs that inherited incorrect strings


##### Fixed


[Fixed] Fixed T14 Get out action showing when in driver triplex view; fixes [#1430](https://github.com/RHSMODS/statusquo/issues/1430)

[Fixed] Removed clothing offset from the core radio prefab

[Fixed] Fixed Vehicle Triplex blocking UI elements

[Fixed] RHS Faction errors

[Fixed] Fixed T14 Hatch texture bleeding in exterior light when closed

[Fixed] Wristwatch render targets crashing dedicated servers and widget cleanup

[Fixed] Russian AA-AVS vests now slot Granit plates instead of ESAPI; fixes [#1429](https://github.com/RHSMODS/statusquo/issues/1429)

[Fixed] Removed default plates from LBT1961 and TT Mk2 rigs; fixes [#1436](https://github.com/RHSMODS/statusquo/issues/1436)

[Fixed] Fixed rangefinder loosing context after coming out of ADS; fixes [#1437](https://github.com/RHSMODS/statusquo/issues/1437), [#1444](https://github.com/RHSMODS/statusquo/issues/1444)

[Fixed] Get Out and Open Door actions no longer appear when looking through driver triplex in T-14; fixes [#1448](https://github.com/RHSMODS/statusquo/issues/1448)

[Fixed] Some AA-CPC MC pouch presets had FG textures; fixes [#1402](https://github.com/RHSMODS/statusquo/issues/1402)

[Fixed] AA-CPC could not load dropped Granit plates back; fixes [#1428](https://github.com/RHSMODS/statusquo/issues/1428)

[Fixed] Fixed GM94 RplComponent problems; fixes [#1420](https://github.com/RHSMODS/statusquo/issues/1420)

[Fixed] BNZ pouch presets were not saving to the arsenal; fixes [#1460](https://github.com/RHSMODS/statusquo/issues/1460)

[Fixed] Fixed unstable call to RandomInt() in APSV2 script, resolving a recurring crash

[Fixed] Potential T14 turret crash related to destruction

[Fixed] Supply drop callins would get stuck in midair

[Fixed] Enemies could see markers for offensive callins

[Fixed] Offensive callin markers displayed the wrong player name

[Fixed] Offensive callin markers are now properly cleaned up when cancelled

[Fixed] Callins were blocked when the character was in a crouched or prone stance

[Fixed] Fixed T14/K17 Commander seat rotating with Gunner turret; fixes [#1464](https://github.com/RHSMODS/statusquo/issues/1464); fixes [#1446](https://github.com/RHSMODS/statusquo/issues/1446)

[Fixed] Fixed T14 Gunner seat positions; fixes [#1461](https://github.com/RHSMODS/statusquo/issues/1461)

[Fixed] Fixed K4386/K17 dual-feed cannon fire rate increase bug; fixes [#1446](https://github.com/RHSMODS/statusquo/issues/1446)

[Fixed] OG-7V was spawning anti-tank spall projectiles

[Fixed] Updated optic layers and material overrides to latest Reforger standards, resolving nighttime matte lens glow

[Fixed] TA31 reticle texture conflict between 3D materials and 2D sights

[Fixed] Arsenal restores no longer loop indefinitely and freeze the server

[Fixed] Sliding attachment positions are now saved and restored for the correct weapon

[Fixed] Saved loadouts are no longer deleted when RHS extra data is missing

[Fixed] Camo headgear is now preserved when spawning Arsenal loadouts (restored missing Reforger v1.8.x code)

[Fixed] Item insertion now correctly checks that both network storages exist (restored missing Reforger v1.8.x code)

[Fixed] NVG device cleanup code

[Fixed] Attachment swapping and restore inventory focus after replacements

[Fixed] Clothing attachment validation on blocked slots

[Fixed] Missing vanilla helmet knockoff handling in the armor damage override

[Fixed] Corrected and simplified helmet item colliders to prevent knocked off helmets falling through terrain

[Fixed] Garmin watch screens appearing grey when inactive or remaining blank until first inspection after spawning

[Fixed] Corrected Garmin watch screen materials for night time rendering

[Fixed] More fixes for various callin faction related issues and cleanup; fixes [#1471](https://github.com/RHSMODS/statusquo/issues/1471)

[Fixed] Collider issues on Harris bipod

[Fixed] Watch component not working on dedicated servers


##### Deleted


[Removed] Obsolete callsigns config file

[Removed] EditorImageGenerator scripts that already exist in vanilla Reforger

[Removed] VONMenuActiveActionCondition null reference workaround that now exists in vanilla Reforger

[Removed] Obsolete turret zoom workaround

[Removed] Legacy reticle workaround on RHS_2DPIPSightsComponent


