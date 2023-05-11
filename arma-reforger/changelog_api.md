---
description: >-
  This document is regenerated automatically from our systems at a time of a
  release.
---

# Changelog

<!-- reset point -->
<!-- changelog insert -->

## 0.3.787

<!-- revision 787 -->
  
{% hint style="info" %}
### **Release Meta Information**

_<mark style="color:red;">Built from Revision:</mark>_ 787

_<mark style="color:red;">Date:</mark>_ Thursday, May 11, 2023

_<mark style="color:red;">Revisions Since Last:</mark>_ 90 (697)

_<mark style="color:red;">Changes:</mark>_ 19 additions, 26 improvements, 68 fixes and 4 deletions.
{% endhint %}

### Added


[Added] Radial menu for AN/PEQ-16 and 1P63 (early trials)

[Added] AKS74U with LTSU Attachment

[Added] Deep shadow under vehicle for k17 and t14

[Added] Vkpo 1 layer undershorts

[Added] MSV arsenal

[Added] USMC arsenal

[Added] SVD with 1pn93 prefab

[Added] PKM with 1pn93 prefab

[Added] MSV vS USMC LoadoutManager

[Added] IT-1TWS-315A (temporary NV)

[Added] AK-74M With picatini rail (needs configuring)

[Added] Added ECH helmet

[Added] AK-74M Dry Reload Animation

[Added] Aimpoint T1 (high mount and low mount)

[Added] Added PC_Gen_III model & placeholder textures and ground model

[Added] T14 Camo Barrel

[Added] T14 Commander hatch open action

[Added] PC GEN 3 to arsenal

[Added] ALL ECH helmets to arsenal


### Improved


[Improved] Some back functionality for radial menu implemented

[Improved] Adjusted character prefabs to 0.9.8 update

[Improved] !!! CHANGED ATTACHEMNT TYPE FROM RHS RIS TO VANILLA RIS1913 !!!

[Improved] Summer vkpo pants rig

[Improved] EARHS backlight handling

[Improved] Change PEQ-16 preview image to be from top

[Improved] Reorganized loadouts of RF EMR prefabs

[Improved] AKS74U Hand Animations

[Improved] Complete factions and arsenals refactor; fixes [#236](https://github.com/RHSMODS/statusquo/issues/236); fixes [#234](https://github.com/RHSMODS/statusquo/issues/234)

[Improved] Spotlight angle adjustment action changed to be adjustable with scroll wheel like BTR hatches

[Improved] Handling of equipping used NV set

[Improved] Handling of NV ADS to prevent NVG being visible in FPP

[Improved] Infratech model

[Improved] AKS74U w/LTSU Animations

[Improved] Optic position on an94

[Improved] Optic position on npz dovetail rail

[Improved] T1 textures

[Improved] AO on k17 and t14

[Improved] Improved PC_Gen_III model

[Improved] Improved PC_Gen_III textures

[Improved] AGS firing range

[Improved] ECH localization

[Improved] MeshObject of all helmets moved to _item model

[Improved] Improved PC_Gen_III ground model

[Improved] Added collider and LODs to 6B47 ground model

[Improved] Moved BaseWeaponManagerComponent to RHS_Character_Base.et to safeguard for future


### Fixed


[Fixed] 1pn93 grain effect

[Fixed] Fixed radial not opening on first go

[Fixed] L5 Skirt on t14 was not moving

[Fixed] Missing hierarchy component on t14 armor and pieces

[Fixed] Missing hierarchy on collimator base

[Fixed] Missing hierarchy on vz52 magazine

[Fixed] Fixed nonexistent ref in inputs context

[Fixed] Missing hierarchy component on many stuff

[Fixed] Missing SignalManagerComponent on many stuff

[Fixed] PGS64 name

[Fixed] T14 Lights

[Fixed] AN-94 railed now uses AttachmentRIS1913Short slot

[Fixed] Vkpo undershirt collar that conflict into the neck on some vanilla heads, and lowered shine on mat

[Fixed] 1P86 eye point

[Fixed] K17 Lights

[Fixed] Fixed an94 and m27 wrong attachment type used for optics

[Fixed] Fixed and improved time changer in the showcase world; fixes [#221](https://github.com/RHSMODS/statusquo/issues/221)

[Fixed] EARHS for 0.9.8; fixes [#227](https://github.com/RHSMODS/statusquo/issues/227)

[Fixed] Missing Hierarchy components in battery and antenna prefabs of ANPRC152

[Fixed] IR illuminator were not visible in NV sights; fixes [#222](https://github.com/RHSMODS/statusquo/issues/222)

[Fixed] NVG for 0.9.8; fixes [#224](https://github.com/RHSMODS/statusquo/issues/224)

[Fixed] Fixed AN/PEQ-16 and 2A42 0.9.8 sound errors; closes [#253](https://github.com/RHSMODS/statusquo/issues/253) [#250](https://github.com/RHSMODS/statusquo/issues/250)

[Fixed] AK-74M Animations and reload sounds

[Fixed] Goggles were visible when ADS while in TPP after repossessing entity; fixed [#217](https://github.com/RHSMODS/statusquo/issues/217)

[Fixed] HDR_Regular had reference to no longer existing class

[Fixed] NV would remain ON when player would stop possessing entity by holding Y

[Fixed] AKS-74U Animations and reload sounds

[Fixed] AN-94 Reload Sounds

[Fixed] M27 Animations and reload sounds

[Fixed] Vz52 Magazine (incorrect magazine well)

[Fixed] AN-94 Inspection Animations

[Fixed] Fixed error spam on 6B7, R187, optics, melee components and mags

[Fixed] Fixed reload anim playing during ranging with Vector or PDU; fixes [#225](https://github.com/RHSMODS/statusquo/issues/225)

[Fixed] Fixed rangfinder second point indicator not clearing

[Fixed] Removed 0.9.8 error spam from MS2000, 1PN93 and 1P78

[Fixed] Fixed error spam due to missing CharacterWeaponComponent, now primary weapon selected at start; fixes [#235](https://github.com/RHSMODS/statusquo/issues/235)

[Fixed] Pgs64 localization; fixes [#244](https://github.com/RHSMODS/statusquo/issues/244)

[Fixed] Rifleman localization; fixes [#243](https://github.com/RHSMODS/statusquo/issues/243)

[Fixed] RF MSV EMR loadouts; fixes [#242](https://github.com/RHSMODS/statusquo/issues/242)

[Fixed] Possible fix to 2a42 missing tracer model; fixes [#262](https://github.com/RHSMODS/statusquo/issues/262)

[Fixed] Sukharka RU localization; fixes [#260](https://github.com/RHSMODS/statusquo/issues/260)

[Fixed] Removed unused params from ANPRC152 prefab; fixed 265

[Fixed] Updated radio OnCapture and OnReceive methods to comply with their respective 0.9.8 ScriptInvokers

[Fixed] Incorrectly added IR HP laser for ANPEQ16 prefab

[Fixed] No attachment slots were shown in inspection menu; fixes [#259](https://github.com/RHSMODS/statusquo/issues/259)

[Fixed] Reticle on t14 and k17 optics

[Fixed] Fixed RHS showcase mission by removing Editor Faction Manager from the world

[Fixed] Fixed position of fire mode switch action in weapon inspection mode on AK74M

[Fixed] Reverse lights on k17

[Fixed] Localization on aksu ltsu

[Fixed] Broken HDR by NV effect

[Fixed] Magnifier position on 1p87

[Fixed] For ECH menu positioning

[Fixed] NPZ Rail Attachment

[Fixed] Infratech reticle issue

[Fixed] Vignette on 1tws

[Fixed] Collider on npz rail

[Fixed] Optic position on m27

[Fixed] T14 horn sound; fixes [#251](https://github.com/RHSMODS/statusquo/issues/251)

[Fixed] Fix APS sound errors; fixes [#249](https://github.com/RHSMODS/statusquo/issues/249)

[Fixed] Fix 2a82 sound errors; fixes [#252](https://github.com/RHSMODS/statusquo/issues/252)

[Fixed] Fix 2a42 sound errors

[Fixed] Fixed more sound error spam; fixes [#257](https://github.com/RHSMODS/statusquo/issues/257)

[Fixed] K17 recoil

[Fixed] K17 Commander Sight

[Fixed] K17 errors; fixes [#229](https://github.com/RHSMODS/statusquo/issues/229), [#233](https://github.com/RHSMODS/statusquo/issues/233)

[Fixed] VKPO undershirt item geometry error

[Fixed] ANPRC 152 sound amplitude error due to renamed config


### Deleted


[Removed] -----------0.98----------

[Removed] Camo ural prefab, since its vanilla now

[Removed] Obsolete stuff from testmap

[Removed] Old PC_Gen_III ground model textures



## 0.2.697

<!-- revision 697 -->
  
{% hint style="info" %}
### **Release Meta Information**

_<mark style="color:red;">Built from Revision:</mark>_ 697

_<mark style="color:red;">Date:</mark>_ Friday, April 28, 2023

_<mark style="color:red;">Revisions Since Last:</mark>_ 41 (656)

_<mark style="color:red;">Changes:</mark>_ 15 additions, 22 improvements, 20 fixes and 3 deletions.
{% endhint %}

### Added


[Added] MS2000 visible and IR functionality

[Added] MS2000 animations

[Added] ANPEQ16 High power modes

[Added] Attribute that allow scopes to see IR light

[Added] Dual PVS14 adapter with bones and full lods and textures & colliders

[Added] Subsonic 5.45 ammo to arsenal

[Added] VKPO summer field pants and undershirt (layer 1)

[Added] NVG Blemishes system

[Added] Summer VKPO pants and underwear to arsenal

[Added] Balaclava to arsenal

[Added] Loadouts to LoadoutManager_Editor.et

[Added] AKS-74U

[Added] AKS-74UN to arsenal

[Added] Crewman kit

[Added] Kits with AN-94


### Improved


[Improved] Strobe effect when switching NV

[Improved] MS2K Collider

[Improved] VKPO demiseason jacket - textures, add lods, fix rig

[Improved] VKPO demiseason pants - textures

[Improved] Faradey boots size adjusted

[Improved] Binos Layout + fixes for positioning entities

[Improved] Vkpo boots - add lods

[Improved] Vkpo cap - were fixed proportions for all vanilla heads, add lods, upd textures

[Improved] Names for new things

[Improved] Dual NVG general prefab improvements

[Improved] 1pn93 filmgrain effect

[Improved] Added LODs to Peltor Item model

[Improved] Vkpo inv preview

[Improved] K17 textures

[Improved] Vkpo textures

[Improved] Vkpo textures 2

[Improved] EMR texture on VKPO

[Improved] Vkpo 6b51 textures 3

[Improved] Added AKS74UN base prefab

[Improved] Textures for vkpo items

[Improved] Localization for equipment kits

[Improved] Localization for AKS-74UN


### Fixed


[Fixed] IR lights were not visible to NV rifle scopes

[Fixed] Some IR lights would not be visible for authority

[Fixed] Desaturation of HDR material of rifle scopes

[Fixed] MS2000 Collider

[Fixed] Various NVG stuff collider fixes

[Fixed] Skinning on MS2K

[Fixed] NPE when IR device was deleted from the map

[Fixed] NPE when light device was deleted when strobe effect was active

[Fixed] Issue when having NVG would prevent IR capable scopes from seeing IR light

[Fixed] K17 Wheel lods

[Fixed] HDR application when swapping NVG to a set that is turned on

[Fixed] Body invisibility after wearing vkpo

[Fixed] 6B45 Item Renderer

[Fixed] Weird shadow on K17 Wheels

[Fixed] A2 Flashhider now has temp black material

[Fixed] Normal map on 6b51 elbows

[Fixed] Optic position on AK-74N

[Fixed] Optic position on AKS-74UN

[Fixed] Fixed PGS64 not being reattach function

[Fixed] Fixed AKS74U inheritance


### Deleted


[Removed] Old version of 1pn138

[Removed] Unused components from Puncox, Wilcox, L4G24, PVS14

[Removed] Obsolete vkpo materials



## 0.2.656

<!-- revision 656 -->
  
{% hint style="info" %}
### **Release Meta Information**

_<mark style="color:red;">Built from Revision:</mark>_ 656

_<mark style="color:red;">Date:</mark>_ Friday, April 14, 2023

_<mark style="color:red;">Revisions Since Last:</mark>_ 8 (648)

_<mark style="color:red;">Changes:</mark>_ 3 additions, 3 improvements, 4 fixes and 0 deletions.
{% endhint %}

### Added


[Added] Commander turret to K17 Epoch

[Added] Missiles to K17 Epoch

[Added] NV Layout system for limiting wearer view with additional images of dual and quad layout masks


### Improved


[Improved] Removed obsolete attachment classes

[Improved] NVG IR lights support

[Improved] Proper IR lights that are only visible in night vision


### Fixed


[Fixed] Fixed wrong editor preview link in T14 base

[Fixed] NV flickering when using higher power scopes

[Fixed] MS2000 Bones for animation.

[Fixed] T-14 Turret lod 2 and 3 were missing skinning


### Deleted




## 0.2.648

<!-- revision 648 -->
  
{% hint style="info" %}
### **Release Meta Information**

_<mark style="color:red;">Built from Revision:</mark>_ 648

_<mark style="color:red;">Date:</mark>_ Sunday, April 9, 2023

_<mark style="color:red;">Revisions Since Last:</mark>_ 151 (497)

_<mark style="color:red;">Changes:</mark>_ 53 additions, 59 improvements, 32 fixes and 7 deletions.
{% endhint %}

### Added


[Added] Wilcox PVS14 Adapter

[Added] M27 Flip Sight Script

[Added] A2 Flash hider Attachment

[Added] Added MP synchronization of NVG state

[Added] Added automatic hiding of NVG model in FPV + Added NVG post processing effect

[Added] Added olive Peltors

[Added] Added White Phosphor variant of NVG

[Added] Added small light source when NVG is ON

[Added] T14

[Added] 3bM69 APFSDS-T for T14

[Added] Warhead_Shell_HE_125

[Added] Ammo_Spall_HE_125.et

[Added] Added boonie hat to the RHS crate

[Added] Skirt proc anim for t-14

[Added] 125mm HE hit effect

[Added] 2a82 Shot effects

[Added] 2a82 Shot Sound

[Added] 3 Variations of shrapnel prefabs for 125mm HE

[Added] Armata version with only HE shells (temporary until we got ability to reload shells that we want for testing, doesnt include in arsenal.conf)

[Added] Added LODs to USMC_Boonie_Hat_Ground

[Added] Placeholder optics for t14

[Added] CombatOps Arland MSV Flora vs USA

[Added] New way to change turret ammo with swap weapon button

[Added] AN/PEQ-16B

[Added] A lot of sounds samples for future

[Added] Tank icon for zeus menu

[Added] T14 Version with destructible ERA armor

[Added] Era destruction on t14 turret

[Added] T-14 Camo version

[Added] New t14 to zeus

[Added] Rear get in action for driver in K17

[Added] 2A82 recoil animation

[Added] LShZ attachment

[Added] Controller key bind for NVG toggle assigned to [Right shoulder]+[Dpad right]

[Added] Light and visible laser to the ANPEQ16

[Added] Inspect mode actions to switch ANPEQ16 mode

[Added] Localization for T-14

[Added] Added two modes for PEQ that will be used for IR (WIP - 2 high and 2 low visibility illuminators and lasers)

[Added] Clicking sounds for PEQ mode switching

[Added] Added USMC groups

[Added] Dynamic light for 30mm hit effect

[Added] More dispersion for 2a42

[Added] Shrapnel for 30mm HE

[Added] ANPEQ16 LED status indicator

[Added] ANPEQ16 knob sounds

[Added] ANPEQ16 procedural animations for its knob

[Added] Decals for 30mm he

[Added] MS-2000

[Added] Subsonic 5.45 ammo and mags

[Added] Cat eyes to T-14

[Added] Lods to K17

[Added] K-17 Wreck model

[Added] New screenshots


### Improved


[Improved] Rearranged test island layers

[Improved] Added simple collider for USMC combat boots item model

[Improved] M27 Animations

[Improved] Improved NVG shortcut detection

[Improved] Improved NVG handling

[Improved] Tweaked and improved ACOG lods; closes [#57](https://github.com/RHSMODS/statusquo/issues/57)

[Improved] Fixed missing M27 and flashhider strings

[Improved] Army M150 RCO now uses the chevron reticle; closes [#202](https://github.com/RHSMODS/statusquo/issues/202)

[Improved] Changed Peltor to olive on LShZ

[Improved] Improved HDR material for GP NVG to fix 'black light'

[Improved] Reenabled RigidBody component for L4G24 mount as it has colliders now

[Improved] More vibrant WP light bleed

[Improved] Handling of entity possession with NVG

[Improved] Set nvg light bleed to be disabled by default to prevent glow when item was spawned

[Improved] T-14 lights

[Improved] Enabled AI driving on K17 & M1151 (without setting an params yet)

[Improved] 125mm HE sets

[Improved] TestingRedline.ent

[Improved] T14 textures

[Improved] 2a82 effects and sounds

[Improved] 2a82 Particles

[Improved] 2a82 Sounds

[Improved] Track textures

[Improved] T14 dynarmor refactor

[Improved] T14 armor model

[Improved] Increased air drag on HEAT penetrators

[Improved] Damage for 125mm and 30mm HE

[Improved] T14 damage model

[Improved] K17 Action positions

[Improved] Configured T14 Commander Turret

[Improved] Added RHS_ tag to tank entity class to avoid clashes with other mods

[Improved] T-14 Commander reticle

[Improved] Additional attempt to achieve compatibility with other mods

[Improved] Added counter rotation component to T14 commander turret (need to be tested in MP)

[Improved] Splitted R187P1 model to be able to use with EARS

[Improved] Added some experimental spalling to T14 AP shells

[Improved] Added coax MG to T14 gunner

[Improved] NV system separation to allow for reusability in the future

[Improved] Minor adjustments to NV HDR and film grain effects

[Improved] Changed actions names to prevent any possible conflicts by adding RHS to it

[Improved] Reduced size of interaction sphere on PEQ box to allow for from iron sights manipulation on m27

[Improved] Railed AN-94 can mount front rail devices like AN/PEQ-16

[Improved] Tweaked T-14 GM integration

[Improved] Added localization for IL-76

[Improved] HE shells can now be reloaded in T14 (changed magazine well)

[Improved] Changed default radio on USMC characters to ANPCR 152

[Improved] 2a42 camera shake

[Improved] 30mms Tracer

[Improved] Standing animations for AN-94

[Improved] ANPEQ16 strobe mode for currently used lights and LED indicator

[Improved] Renamed T-14 Prefabs

[Improved] File structure

[Improved] 2A42 light from particles

[Improved] Epoch and Berezhok hud

[Improved] T-14 skirt animation

[Improved] K-17 hitbox

[Improved] T-14 hitbox

[Improved] T-14 Wreck model

[Improved] T-14 LODs


### Fixed


[Fixed] Way of attaching NightVision devices to Rhino prefabs

[Fixed] USMC Boonie hat localization

[Fixed] Fixed duplicated gear in various Russian vests

[Fixed] L4G24 Texture & folding script

[Fixed] Fixed NPE when player didnt have RHS_RpcManager component

[Fixed] Wrong material overrides on worn black LShZ with Peltor

[Fixed] Fixed NVG MP synchronization

[Fixed] Fixed bug that would cause film grain effect to disappear when some menus were open

[Fixed] L4G24 Colliders & Lods

[Fixed] PVS14 Colliders & Lods

[Fixed] Wilc0x adapter Colliders & Lods

[Fixed] Zeus was able to un/fold nods of previously possessed entity if he had nvg on his main character

[Fixed] Bug that would remove some NVG effects when player would open some menus ie. inventory

[Fixed] Missing gamemat

[Fixed] Fixed duplicate emats

[Fixed] 30mm configs

[Fixed] 125MM configs

[Fixed] Error spam cause by era

[Fixed] K17 seating positions

[Fixed] 2A82 procedural animation

[Fixed] Collider on LShZ_attachment

[Fixed] Wrong classnames on RHS_Atoll

[Fixed] T-14 AmmoRack collider config

[Fixed] Weird workaround for missing signal manager component on T14 after post init

[Fixed] Removed button click sound when device was turned off by its timer

[Fixed] 30mm he bebryanka ((pelmen) warhead)

[Fixed] RPG-7 now able to attach nvg optics

[Fixed] Minor changes on T-14 an K-17

[Fixed] Temporal fix for fuel tanks

[Fixed] K-17 LODs

[Fixed] Added some missing stuff to arsenal

[Fixed] Minor fixes in characters


### Deleted


[Removed] Unused test prefabs

[Removed] L4G24 Item

[Removed] Old t14 from zeus

[Removed] 2A82 HE from T14 turret

[Removed] HE barrel from t14

[Removed] PKT from gunner

[Removed] Removed NVG test helmet from Arsenal - for now NVG is only available in showcase mission till it is further tweaked



## 0.2.497

<!-- revision 497 -->
  
{% hint style="info" %}
### **Release Meta Information**

_<mark style="color:red;">Built from Revision:</mark>_ 497

_<mark style="color:red;">Date:</mark>_ Tuesday, March 7, 2023

_<mark style="color:red;">Revisions Since Last:</mark>_ 26 (471)

_<mark style="color:red;">Changes:</mark>_ 7 additions, 5 improvements, 12 fixes and 1 deletions.
{% endhint %}

### Added


[Added] 6b47 version with balaclava

[Added] Added FROG Trousers Ground model

[Added] Added placeholder USMC faction

[Added] K17 Added GM Preview

[Added] Added USMC Boonie

[Added] Added USMC spawn points

[Added] PVS14 model


### Improved


[Improved] K17 Get in positions

[Improved] Flashlight position on 6b45

[Improved] Tweaked R187P1 preview image in loadout menu

[Improved] Tweaked Suharka preview image and structure

[Improved] L4G24 Item Renderer


### Fixed


[Fixed] Ultimate fix for laser range finder (PDU-4/Vector) blocking ADS

[Fixed] K17 Sights positions

[Fixed] Hiding ManPacks

[Fixed] Floating pouch on 6b45

[Fixed] USMC clothing localization

[Fixed] Added missing items to arsenal

[Fixed] Fixed FROG Combat Shirt clipping

[Fixed] Fixed EMR MG group editor icon

[Fixed] Fixed AN94 skeleton contained _end bones

[Fixed] Fixed inspection actions on AN94

[Fixed] L4G24 Animations

[Fixed] Fixed K17 faction affiliation


### Deleted


[Removed] K17 Epoch Commander Turret



## 0.2.471

<!-- revision 471 -->
  
{% hint style="info" %}
### **Release Meta Information**

_<mark style="color:red;">Built from Revision:</mark>_ 471

_<mark style="color:red;">Date:</mark>_ Friday, March 3, 2023

_<mark style="color:red;">Revisions Since Last:</mark>_ 3 (468)

_<mark style="color:red;">Changes:</mark>_ 0 additions, 2 improvements, 2 fixes and 0 deletions.
{% endhint %}

### Added



### Improved


[Improved] NVG grain effect

[Improved] Regenerated preview images


### Fixed


[Fixed] Fixed K17 Berezhok crashing dedicated server

[Fixed] Fixed EMR infantry loadouts


### Deleted




## 0.2.468

<!-- revision 468 -->
  
{% hint style="info" %}
### **Release Meta Information**

_<mark style="color:red;">Built from Revision:</mark>_ 468

_<mark style="color:red;">Date:</mark>_ Friday, March 3, 2023

_<mark style="color:red;">Revisions Since Last:</mark>_ 1 (467)

_<mark style="color:red;">Changes:</mark>_ 0 additions, 0 improvements, 1 fixes and 0 deletions.
{% endhint %}

### Added



### Improved



### Fixed


[Fixed] Fixed OPFOR Arsenal crate had wrong GUID


### Deleted




## 0.2.467

<!-- revision 467 -->
  
{% hint style="info" %}
### **Release Meta Information**

_<mark style="color:red;">Built from Revision:</mark>_ 467

_<mark style="color:red;">Date:</mark>_ Friday, March 3, 2023

_<mark style="color:red;">Revisions Since Last:</mark>_ 9 (458)

_<mark style="color:red;">Changes:</mark>_ 0 additions, 1 improvements, 5 fixes and 0 deletions.
{% endhint %}

### Added



### Improved


[Improved] Azart position on 6b45


### Fixed


[Fixed] Fixed reference to non existing material in Jacket 6B51 VKPO

[Fixed] Fixed wrong model was assigned in MeshObject of balaclava base prefab

[Fixed] Fixed NPE when game tried to load VONDisplay for AI Unit

[Fixed] Fixed potential conflict with standalone EARS (EARS side fix also already up on workshop)

[Fixed] IL-76 Missing audio


### Deleted




## 0.2.458

<!-- revision 458 -->
  
{% hint style="info" %}
### **Release Meta Information**

_<mark style="color:red;">Built from Revision:</mark>_ 458

_<mark style="color:red;">Date:</mark>_ Thursday, March 2, 2023

_<mark style="color:red;">Revisions Since Last:</mark>_ 44 (414)

_<mark style="color:red;">Changes:</mark>_ 18 additions, 25 improvements, 15 fixes and 6 deletions.
{% endhint %}

### Added


[Added] 30mm HE hit effect

[Added] 30mm 3UOF8 warhead

[Added] 1P90

[Added] Test AK pouches for 6B45

[Added] Integrated EARS functionality into RHS

[Added] Casing for 2a42

[Added] Test map TestingTerrRedline/Terrain

[Added] Added 1P86 localization

[Added] 3 pouches for azart radio, vog rounds, first aid med pouch and 6B45 presets for it

[Added] 1P87 with 1PN138

[Added] Added ANPRC152 Eng localization strings

[Added] Added compatibility list to attachment type and checks for that to storage and action scripts

[Added] Added ability to turn on/off the radio through [G]+[R]

[Added] Added ability to change knob position through [G]+[Scrollwheel]

[Added] Added ability to set encryption key for each preset separately

[Added] Added ability to add more presets

[Added] Added ability to set radio frequency by inputting it with radio keyboard

[Added] Radio unhide script


### Improved


[Improved] Il76 sounds

[Improved] 30mm ballistic

[Improved] Azart textures

[Improved] Tweaked AK74M textures

[Improved] New reticle for Sig Bravo 4; closes [#200](https://github.com/RHSMODS/statusquo/issues/200)

[Improved] SP81 Muzzle flash

[Improved] Configured red dot on SU230 with MRDS - close [#197](https://github.com/RHSMODS/statusquo/issues/197)

[Improved] Tweaked collimator script so fake red dot is disabled by default

[Improved] Tweaked BUIS recoil behavior on SU230

[Improved] Added missing LODs on 6B45 with close neck armor

[Improved] 6B45 textures. optimized size to 2k

[Improved] Improved incoming radio transmission detection (compared to the latest EARS version)

[Improved] PDU-4 now has more accurate 7x zoom

[Improved] Weapons_HeavyWeapons_2a42_Shot.acp

[Improved] HIT_30mm_HE.ptc

[Improved] Smoke_2a42.ptc

[Improved] Tweaked 6M2 item LOD switching

[Improved] Name and description for new items

[Improved] 6B45 separated into vest and collar, improved rig

[Improved] Tweaked AK74M fire geo - added weapon_plastic material to the stock

[Improved] Radio will be ON by default unless it was loaded with the map

[Improved] Improved frequency presets handling between players

[Improved] Changed GUIDs of 6b45 and 6b45 (rifleman) vests so they are matching previously created prefabs - this way backward compatibility with already existing assets was maintained and some of the errors were also fixed during that process

[Improved] Added compatibility with community RIS optics

[Improved] Auto transform enabled for radio slot on ratnik SL vest


### Fixed


[Fixed] 9M113 not firing

[Fixed] K17 top speed

[Fixed] Removed duplicated entries in InventoryItemComponent of scopes

[Fixed] Fixed default camera position on GM showcase mission

[Fixed] SU230 reticle is no longer changing scale with zoom - close  [#198](https://github.com/RHSMODS/statusquo/issues/198)

[Fixed] LShZ normals

[Fixed] IL76UN_running.et sounds

[Fixed] Fixed 1P86 PIP reticle

[Fixed] Ak pouches rig and size, add lods and colliders

[Fixed] Azart localization

[Fixed] Fixed AK74M skeleton - removed some weird second skeleton, _end bones and other weird things

[Fixed] Fixed radio turning off when player is teleported over long distance

[Fixed] Fixed wrong gamemats on 2 M1151 colliders

[Fixed] Fixed duplicated signals manager component on 1P63

[Fixed] Fixed RHS GM Showcase scenario was loading wrong world


### Deleted


[Removed] Fixed wandering reticle on m8541

[Removed] M8541 Reticle now scales with zoom at least in PiP

[Removed] Not used samples for 2a42 shot sound

[Removed] Dynamic light for HIT_30mm_HE.ptc

[Removed] Not used audio files

[Removed] All cinematic stuff



## 0.2.414

<!-- revision 414 -->
  
{% hint style="info" %}
### **Release Meta Information**

_<mark style="color:red;">Built from Revision:</mark>_ 414

_<mark style="color:red;">Date:</mark>_ Saturday, February 4, 2023

_<mark style="color:red;">Revisions Since Last:</mark>_ 413 (1)

_<mark style="color:red;">Changes:</mark>_ 137 additions, 179 improvements, 88 fixes and 11 deletions.
{% endhint %}

### Added


[Added] Added some dirty Flora reskins of M88 uniform

[Added] Added APS wirestock configuration

[Added] Added RPK74N to ammo crate

[Added] Setup of RHS Aresnal

[Added] RPK74N (dovetail texture size and quality is temp)

[Added] 6L23 Plastic variant

[Added] AK74N prefab

[Added] AK74 Dovetail model

[Added] Added item variant for CVC

[Added] Added some basic AN94 prefab

[Added] Sounds folder

[Added] APS mechanics samples

[Added] APS acp

[Added] Added some test VSR textures

[Added] Added some Flora units

[Added] Added new test terrain with navmesh

[Added] Added Flora & VSR units & groups (basics)

[Added] Added arm patch experiment to M88 Flora uniform

[Added] Added 6M2

[Added] 1P78 Model

[Added] PDU-4

[Added] Test nvg

[Added] NVG test prefab and map

[Added] Test range for setting up scope ranges

[Added] Added modified version of SCR_2DPIPSightsComponent_RHS.c (doesn't seem to work yet)

[Added] Added AK74N with 1P78 prefab

[Added] FilmGrain hdr

[Added] Added some example PP effects for NVG

[Added] RHS_MagazineWell.c

[Added] APS Magazine

[Added] APS magazine base prefab

[Added] 1PN93-1 AK-74

[Added] Added AS, RPG, PKM and SVD versions of 1PN93

[Added] Russian language to gproj & generated runtime tables

[Added] SP-81 mesh

[Added] 26X45 Cartrige and casing (ammo for sp-81)

[Added] VKPO Demiseason Jacket

[Added] 6B47 Helmet; closes [#3](https://github.com/RHSMODS/statusquo/issues/3)

[Added] Vector21 Rangefinder; closes [#32](https://github.com/RHSMODS/statusquo/issues/32)

[Added] Added LoadoutManager_Editor.et in order to fix selection of RHS faction in Game Master

[Added] 6B7-1M Helmet

[Added] AK74M basic model and broken prefab

[Added] VKPO cap

[Added] Added Flare Particle Effects

[Added] Added SP81 Prefabs/Weapons/Handguns/SP81

[Added] Added Flare Particle Effects Prefabs

[Added] Added 26x45 Illumination Flare Ammunition Prefab

[Added] Added SP81 Flare Pistol to Test Mission

[Added] Folded vkpo pants

[Added] EMR unarmed unit

[Added] Updated Vector21 UI

[Added] IL-76 Model

[Added] Added 1пн93 Scopes for AK74, PKM, SVD, RPG

[Added] RSP-30 Model (texture, uv and rig are temporary and subject to change)

[Added] RSP30 Rig

[Added] Added ak74m weapon animations

[Added] Added new flare projectile as Ammo_Flare_26x45_White

[Added] Added new flare particle effect

[Added] VKPO pants with 6B51 kneepads (test)

[Added] Added basic rangefinder ability to Vector21

[Added] Some experiments with APS with stock animations

[Added] VKPO pants with 6B51 item model

[Added] Added AK-74M GP-25 prefab

[Added] Added RHS statuette

[Added] Picatiny attachment slot

[Added] AN-94 With rails

[Added] 1P87

[Added] Added PDU laser ranging script fully functioning

[Added] Few more picatiny attachment slots

[Added] VKPO jacket with 6B51 elbowpads

[Added] 1P63; closes [#6](https://github.com/RHSMODS/statusquo/issues/6)

[Added] Lods for sp-81 and ak74m

[Added] Added TA31RCO

[Added] Po4x24

[Added] 6B45 (not finished)

[Added] 6B45 item model

[Added] 6B45 localization

[Added] Bravo4 mesh and texture

[Added] Added custom weapon hand anim to Vz52

[Added] Open il-76 version

[Added] Added new test terrain

[Added] Added placeholder EMR section of MSV

[Added] Added AK74M with GP25

[Added] Added RHS version of Combat Patrol

[Added] Camo version of ural cargo

[Added] LShZ-3 model 2

[Added] Fake early A3 style collimator script

[Added] AN-94 With 1P63

[Added] Added proper reticle for 1P87

[Added] Added lots of stuff to OPFOR arsenal

[Added] Added two olive CVC variants

[Added] Added Olive and Black CVC to US box

[Added] SU230 with and without MRDS

[Added] Added MSV spawn point

[Added] Added GM version of showcase scenario

[Added] Added Vector horizontal and vertical distance (press and release R, then hold R for 2s. and release)

[Added] Added 1PN138 experimental XOB file and textures

[Added] Added FROG Combat Shirt, XOB files and textures. Built prefab for testing.

[Added] Ratnik buttpack for 6B45

[Added] UN Version of IL-76

[Added] Added lods to il-76

[Added] Ability to change magnification for su230

[Added] Il76 version with running engines

[Added] 1p86

[Added] R187P1 Azart radio

[Added] Added M8541 Optic

[Added] NVG effect to camera

[Added] M1151 base mesh

[Added] K17 base mesh

[Added] Temp texture for K17

[Added] Added M1151 vehicle prefab

[Added] Added WIP FROG Trousers, XOB files and textures. Built prefab for testing & added to Showcase_full scenario

[Added] K17 Vehicle Prefab

[Added] Simple vehicle testsite

[Added] AGS-30 to K17

[Added] Case ejection particle to 2A42

[Added] Get in actions for hatches on K17

[Added] Placeholder exhaust effect for K17

[Added] Added WIP USMC Combat Boots, XOB files and WIP textures. Built prefab for testing.

[Added] Added LODs to FROG_Trousers

[Added] K17 Epoch Turret

[Added] Added 3M PELTOR ComTac VI

[Added] LShZ textures

[Added] High cut LShZ

[Added] LShZ with 3M

[Added] Lights to K17

[Added] Balaclava for LShZ

[Added] K17 to GameMaster

[Added] Peltor arc adapter

[Added] Added black Peltor texture

[Added] LShZ 1+ mod2 with peltors

[Added] Black peltor version prefab

[Added] Camo ural

[Added] K17 placeholder interior

[Added] Position lights to il-76

[Added] 3UOF8 HEI Ammo to the K17

[Added] Reload function to switch between HEI and APDSFS-T on K17


### Improved


[Improved] Updated version file for testing

[Improved] Dovetail textures are now 1k res

[Improved] Changed lighting on test world

[Improved] Renamed Pistols to Handguns folder

[Improved] Tweaked RHS Arsenal config

[Improved] Added some initial APS animations and configuration

[Improved] Preparation of RHS arsenal box

[Improved] Added Manual Frame Range to anims

[Improved] PBR fixes on AN-94 and Platic Mag

[Improved] Added basic AN-94 animations

[Improved] Moved back AN-94 so it fits AK-74 animations

[Improved] Various rpk74n tweaks

[Improved] Tweaked AN-94 bone hierarchy

[Improved] Prepared AN-94 animation workspace

[Improved] Configured AK74N dovetail

[Improved] Made GUIDs unique

[Improved] Tweaked test mission + exposed in workshop

[Improved] Fixed file structre (once again)

[Improved] Tweaked an-94

[Improved] Some changes on devmap

[Improved] Removed old abakan blendfile

[Improved] Added working localization

[Improved] Tweaked test world

[Improved] Attempt to set localization properly

[Improved] Small 1p21 mesh fixes

[Improved] Added CVC to BLUFOR crate

[Improved] Tweaked visibility of AN-94 in zeus crate

[Improved] Exported updated AN94 to FBX

[Improved] Some basic configuration of AN94

[Improved] Attempt to enable ammo crates

[Improved] Added resourceDatabase.rdb to ignore list

[Improved] APS base prefab to use APS sounds

[Improved] Tweaked Flora textures

[Improved] Tweaked to uniforms configuration

[Improved] Added firing range to showcase mission

[Improved] Fixed 1p21 position

[Improved] Kh-55 texture improvements

[Improved] 1p78 now have its own mark

[Improved] Minor KH-55 texture improvments (only .tif bcz my tools are broken)

[Improved] Minor changes on NVG HDR

[Improved] Lifted matrial law in scripts

[Improved] Renamed 1P78 textures so they get proper compression profile

[Improved] Increased FOV of 1P78 (not calibrated yet)

[Improved] Tweaked order of PP effects

[Improved] Tweaked 6M2 inventory preview

[Improved] Final version of NVG HDR

[Improved] Now APS have its own magazine and full auto firemode

[Improved] Added 1PN93 LODs

[Improved] Improved sp-81 textures and model

[Improved] Reorganized assets a little bit

[Improved] Added RHS variant of SCR_FiringRangeScoringComponent.c (WIP)

[Improved] Registered Screenshots folder and added ignore flag to it

[Improved] Changed project language on SVN

[Improved] VKPO cap texture and rig

[Improved] Cleaned up world layers

[Improved] Added prototype of reticle scaling with zoom on 1P21

[Improved] Fixed ak74m ao texture

[Improved] Faradey boots item model

[Improved] Folded vkpo jacket textures

[Improved] M88 Flora prefab model

[Improved] MSV Flora loadout (return M88 pants)

[Improved] 1P78 Eye position

[Improved] Improved 2DPIPOpticsComponent

[Improved] VKPO Uniform textures

[Improved] RSP30 texture, uv, and model

[Improved] Rsp30 texture

[Improved] VKPO textures for props

[Improved] Name and description of VKPO stuff

[Improved] VPKO jack and pants item models - added UBX collider so actions would work on them

[Improved] Enabled fpv hiding for vkpo_cap.emat

[Improved] IL-76 Texture

[Improved] IL-76 Static model

[Improved] Improved Flare effect

[Improved] AK-74M texture and model

[Improved] VKPO jacket LODs and materials

[Improved] Updated APS animation file

[Improved] Tweaked animation switching when APS stock is mounted

[Improved] VKPO pants with 6B51 LODs, textures, rig

[Improved] Added lods and colliders on 6B7 ground items

[Improved] Slightly improve lod transitions for 6B7 uncovered item

[Improved] Tweaked SP-81 animation setup

[Improved] Tweaked preview models setup on SP81 anim workspace

[Improved] Added some base classes and improved naming of 6B7 prefabs

[Improved] Added straps to 6B47

[Improved] VKPO jacket 6b51 position and rig

[Improved] Added newer stuff to the arsenal boxes

[Improved] VZ52 and 1P63 Textures

[Improved] Thicker and ranged ACOG sights

[Improved] PDU properly ranged markings

[Improved] Acog optic dualcolor

[Improved] 6B45 item LODs

[Improved] Added new weapon inspection logic to AK74M & AN94

[Improved] Tweaked default action position on AN-94

[Improved] Tweaked 1P63 & TA31RCO scope params

[Improved] Added params for hiding of helmet accessories (0.9.7 version required)

[Improved] Tweaked 6L23 magazines inheritance

[Improved] Tweaked 6L23 default action position

[Improved] Tweaked optics inheritance & structure

[Improved] Added mount/dismount action to scopes

[Improved] Added environment probe to test dev map

[Improved] Tweaked firing range (added hit indicator for long firing range)

[Improved] Changed TA31RCO item settings so it fits into inventory

[Improved] Bravo4 is now usable

[Improved] Nvg hdr

[Improved] Vz52 is now correctly using snap_weapon slot

[Improved] Tweaked vz52 actions position

[Improved] Updated navmesh on test map

[Improved] Tweaked action position on some of the scopes

[Improved] Tweaked scopes inventory size

[Improved] 6B45 rig

[Improved] VKPO proportions for correct 6B45 placement

[Improved] Added missing alpha texture to some of the Russian headgear

[Improved] Tweaked configuration of flare ammo & ratnik vests (inheritance)

[Improved] Increased temporarily capacity of 6B45 vest so the EMR faction can be somewhat used in GM

[Improved] Regenerated content browser pictures for EMR troops

[Improved] Converted 1P63 to use collimator trick too

[Improved] EMR AR is now using RPK74N with 1P78

[Improved] HDR material for NVG scopes

[Improved] Tweaked color of 1P63 reticle

[Improved] Filter on 1p63

[Improved] Tweaked inventory previews on various weapons

[Improved] Tweaked 1P87 coli dot brightness

[Improved] Tweaked terrain layer preset

[Improved] 1P63 (lods and new glass)

[Improved] Added contrast filter toggle action on 1P63 (available in inspect menu)

[Improved] Further improved TA-31 reticle and FOV

[Improved] Tweaked TA31RCO script and setup

[Improved] Tweaked 1P63 materials (fix for weird alpha sorting in game)

[Improved] Tweaked AK74M zeroing animations

[Improved] Further improve Vector 21 script

[Improved] Disabled ironsights on AK74M & AN94 when optic is mounted

[Improved] Added TA31 and Vector to general RHS arsenal

[Improved] Tweaked TA31 action position

[Improved] Tweaked range finder script so it works with experimental build

[Improved] Added action tooltips for range finder

[Improved] Added unconsciousness to RHS Combat Ops

[Improved] Adjusted EMR troops loadouts (magazines)

[Improved] Improved Vector 21 key hints

[Improved] Added LODs to TA31RCO

[Improved] ARD hex darkening for enabled scopes

[Improved] LOD switching for RCO

[Improved] Changed bravo4 texture

[Improved] Tweak 6M1 LOD transitions

[Improved] Changed HDR on NVGs

[Improved] Tweaked render preview of picatinny scopes

[Improved] Nvg effect

[Improved] Added rest of Vector functionality

[Improved] Added RHS statue to RHS Arsenal

[Improved] Updated all english and russian stringtable entries

[Improved] Added localization to 6B47 helmet and variants

[Improved] Added localizations for 6B7-1M

[Improved] IL-76 UN Livery

[Improved] Buttpack textures and scale

[Improved] IL-76 Sounds

[Improved] Improved azart texture

[Improved] Time of day on test world

[Improved] Improved FROG Trousers(new belt/belt loops)

[Improved] Updated FROG Trousers textures

[Improved] K17 Engine torque and power

[Improved] K17 Buoyancy Simulation

[Improved] Improved FROG Trousers weights

[Improved] M8541 Textures update thanks to @sabre

[Improved] AI targeting in K17 turrets

[Improved] Added backup sights to SU230

[Improved] Hide Peltor in 1st person view

[Improved] LShZ model

[Improved] Color of emr

[Improved] K17 Buoyancy simulation

[Improved] Damage of 2A42 APDSFS rounds

[Improved] Various LShZ fixes and improvements

[Improved] Added most of the new goodies to appropriate arsenal boxes

[Improved] EMR troops now use Azart radios

[Improved] Peltor proportions on LShZ

[Improved] Ratnik gear textures

[Improved] Improved Marine Combat Boots texture/prefab

[Improved] Lights on the K17

[Improved] Improved PDU4 reticle; closes [#194](https://github.com/RHSMODS/statusquo/issues/194)

[Improved] K17 Suspension

[Improved] K17 Tire settings


### Fixed


[Fixed] Fixed AK74N dovetails

[Fixed] Fixed FactionManager was missing RHS faction config

[Fixed] Fixed 1P21 strings

[Fixed] Cleaned up from files which were overriding Sample Mod

[Fixed] Forgot to plug in that anim to AN-94

[Fixed] Fixed PIP issue on AN-94 (temporary workaround till pivots are fixed in the game)

[Fixed] Fixed CVC visibility in first person

[Fixed] Fixed authored labels on groups & units

[Fixed] Fixed 1P78 name and added to test world

[Fixed] Fixed location of Arsenal related things

[Fixed] PDU position and color

[Fixed] Eye position on 1p78 Fixed issue

[Fixed] Kh-55 texture fix

[Fixed] Various localisation fixes

[Fixed] Nvg fixes

[Fixed] Fixed NVG brightness

[Fixed] First iteration of setting 1p78 ranges

[Fixed] Localization fixes

[Fixed] 1P78 eye position Fixed issue

[Fixed] 1P78 now have proper zeroing

[Fixed] Some more script fixes related to SCR_2DPIPSightsComponent_RHS.c

[Fixed] Final version of 1p78 zeroing

[Fixed] APS now have proper lods

[Fixed] Fixed PIP script due to bad API change; fixes [#163](https://github.com/RHSMODS/statusquo/issues/163)

[Fixed] Removed test stuff

[Fixed] Fixed broken material overrides on 6B7

[Fixed] Replaced SP81.xob... new one has memory points necessary for prefab

[Fixed] Fixed configuration of ignored from packing folder

[Fixed] Fixed APS stock position

[Fixed] Added Different Color Flares

[Fixed] Fixed PIP UV map on 1PN93

[Fixed] AO on ak74m

[Fixed] Window texture on IL-76

[Fixed] Fixed 1P78 reticle in PIP mode

[Fixed] Replaced for now material override with prefab variants on 6B7 flora & olive variants

[Fixed] Fixed broken skinning on 6B7 LOD2

[Fixed] Missing files

[Fixed] Fix to SP-81 IK anim link

[Fixed] Hide pistol on soldier back

[Fixed] 1P63 Model

[Fixed] Wrong layer preset and material on 6L23 magazine

[Fixed] Fixed obsolete audio file assignment in AN94 prefab

[Fixed] Fixed remap related errors in console log when VPKO uniform was present

[Fixed] 1P21 script had duplicated variable in 0.9.7 version of the game

[Fixed] Fixed faction affiliation of Arsenals in showcase scenario

[Fixed] Fixed material links errors in various assets

[Fixed] Fixed missing AreaType param

[Fixed] Fixed RHS Arsenal faction affiliation

[Fixed] Size and weight of sp81 ammo

[Fixed] Normal map on il-76 engine covers

[Fixed] Localization of some items

[Fixed] 1P21 Position on SVD

[Fixed] Fixed vz52 duplicated weapon sound component

[Fixed] Fixed some colliders materials

[Fixed] Removed unwanted material overwrite

[Fixed] Fixed Flora pants missing in compiled version of the mod

[Fixed] Fixed lake in showcase scenario

[Fixed] Fixed offset of AN94 railed variant

[Fixed] Made SP-81 reload somehow working

[Fixed] Deinitialization of RHS PIP effects

[Fixed] VKPO pants - wrong position with shoes

[Fixed] Optics position on AN-94

[Fixed] Fixed SP-81 Ammo names

[Fixed] TA31 scope zoom and markings

[Fixed] AO on 1p63

[Fixed] Vector 21 ranging and azimuth calculations (use R for ranging and F for azimuth, both at the same time to see both)

[Fixed] Fixed Vecotr inheritance

[Fixed] Fixed RHS pip script was calling non existing materials

[Fixed] Fixed PDU4 VME in Workbench

[Fixed] Fixed 6B45 open inheritance

[Fixed] Fixed LOD switching problem on 6M2

[Fixed] Possible fix for US arsenal box

[Fixed] Various localization fixes

[Fixed] Potential rangefinder fix

[Fixed] Green CVC texture

[Fixed] Fixed FROG Combat Shirt prefab

[Fixed] Fixed strings for ACOG to be M150 RCO and M7 RCO

[Fixed] Wrong position of PDU and Vector on player's model

[Fixed] Removed Il-76 layer preset override from prefab

[Fixed] Collision on il76

[Fixed] K17 mesh hierarchy

[Fixed] K17 Fire Geometry

[Fixed] Fixed vector material overrides

[Fixed] Material instances on LShZ HC

[Fixed] Brake lights on K-17

[Fixed] Fixed changelog stuff

[Fixed] PDU-4 now uses advanced rangefinder script; closes [#62](https://github.com/RHSMODS/statusquo/issues/62)

[Fixed] K17 Wheel Diameter


### Deleted


[Removed] Removed some obsolete files

[Removed] 1p21 beta

[Removed] Structure fixes

[Removed] Added devmap to make tests easier

[Removed] Removed obsolete files

[Removed] Removed SSh68 override

[Removed] Removed meta files for folders

[Removed] Removed some rogue file

[Removed] Unused jacket textures

[Removed] VKPO unused textures

[Removed] Epoch Commander seat to prevent crashes

