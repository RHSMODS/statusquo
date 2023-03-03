---
description: >-
  This document is regenerated automatically from our systems at a time of a
  release.
---

# Changelog

<!-- reset point -->
<!-- changelog insert -->

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

