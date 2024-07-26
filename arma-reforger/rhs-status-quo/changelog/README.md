---
description: >-
  This document is regenerated automatically from our systems at a time of a
  release.
---

# Changelog

<!-- reset point -->
<!-- changelog insert -->

## 0.9.3094

<!-- revision 3094 -->
  
{% hint style="info" %}
### **Release Meta Information**

_<mark style="color:red;">Built from Revision:</mark>_ 3094

_<mark style="color:red;">Date:</mark>_ Friday, July 26, 2024

_<mark style="color:red;">Revisions Since Last:</mark>_ 121 (2973)

_<mark style="color:red;">Changes:</mark>_ 26 additions, 13 improvements, 21 fixes and 4 deletions.
{% endhint %}


##### Added


[Added] Kega explosion particles and sound

[Added] Added all Wartech pouches in EMR

[Added] Added ARS Arma GMR in EMR

[Added] Added ARS Arma HSGI belt in EMR

[Added] Added Shaw Concepts pouches in Multicam

[Added] Added HSGI pouches in Multicam

[Added] Added Wartech MP103 Pouch

[Added] Added JPC Platecarrier

[Added] Added AVS Platecarrier

[Added] Added 6.22 Rush-12 Backpack

[Added] Added ZSh-7V

[Added] Added TS-30A2 scope

[Added] Added TS-30A2 scope (camo)

[Added] Added GEO-ONV1-01 night vision goggles

[Added] 3uor6 30mm round instead of 3uof6

[Added] Added Ars ARMA CPC Mod 2 Platecarrier

[Added] Added NCPC Platecarrier

[Added] Added side armor variants of AVS

[Added] Added new pouches to and JPC AVS

[Added] Added AOR1 LBH

[Added] Added Kiver RSP cover in multicam

[Added] Added OKC-3S bayonet

[Added] Added painted Mich 2000

[Added] Added AVS 6x9 in EMR Camo

[Added] Added AA CPC with Groin protection

[Added] Added EMR AVS with Groin protection


##### Improved


[Improved] PDU-4 and Vector 21 magnification slightly reduced (from 7x to 5x) to keep whole reticle visible on screen, reticle stays true to sight picture

[Improved] Tucha particles and optimization

[Improved] Armata ammo rack particles and sounds

[Improved] Updated RHS Conflict scenario

[Improved] Replaced ammunition in base M40A5 magazine with M118 Special Ball (an additional magazine has been provided using the previous M80 FMJ ammo)

[Improved] Particles for 30mm

[Improved] Plugged in K17 engine start animations

[Improved] ZSh-7V (pilot) helmet can now only accept GEO-ONV1-01 Night vision goggles (ant as of the moment thats the only helmet to which they can be mounted; fixes [#918](https://github.com/RHSMODS/statusquo/issues/918)

[Improved] Added: Information when highlighting the GEO-ONV1-01 nvg and ZSh-7V helmet about the mounting compatibility restrictions

[Improved] Corrected designation of 6Kh9-1 bayonet

[Improved] Reworked M4A1 CQBR inheritance so that they inherit from a common base class

[Improved] Reduced muzzle velocity of CQBR rifles

[Improved] Adjusted TV110 preview icon


##### Fixed


[Fixed] Fixed major crash

[Fixed] 1P21 PIP magnification - sight rear, front and scope radius needed tweak

[Fixed] Fixed Jeans were missing some hide body parts params

[Fixed] Missing animation files related to M40 safety. (Issue [#906](https://github.com/RHSMODS/statusquo/issues/906))

[Fixed] AKS-74UN w/ LTSU and B-18 picatinny mount having the wrong animation set. (Issue [#842](https://github.com/RHSMODS/statusquo/issues/842))

[Fixed] Fixed Filbe was using using wrong mesh for ground model

[Fixed] Fixed EXPS / SU-231A reticle flickering

[Fixed] Small PDU-4 layout tweak

[Fixed] Fixed FAST MT Marpat wrong texture

[Fixed] TS30A2 reticle changed to rear focal plane, valid only at maximum magnification 8x

[Fixed] Damage on 30mm rounds

[Fixed] Fixed strings on TV-110 pouch presets

[Fixed] Trailing space in PC Gen III display name string

[Fixed] Fixed: Items dragged while arsenal is open would be refunded rather than transferred to the storage to which they were meant to go; fixes [#916](https://github.com/RHSMODS/statusquo/issues/916)

[Fixed] Fixed: Inventory option to press F in order to equip an gadget straight from the inventory would not show up; fixes [#916](https://github.com/RHSMODS/statusquo/issues/916)

[Fixed] Fixed: When some vest were present then gloves would go to the vest rather than to their dedicated slot; fixes [#916](https://github.com/RHSMODS/statusquo/issues/916)

[Fixed] Fixed m240 had broken collider

[Fixed] Some preview icons were not loading the camo correctly; fixes [#921](https://github.com/RHSMODS/statusquo/issues/921)

[Fixed] Fixed wrong Taktika belts description

[Fixed] Fixed K17 antena animation CTD

[Fixed] TV-110 triple pouch are now part of the vest


##### Deleted


[Removed] Removed some default patches from few TV110 pouch presets

[Removed] 3uof6 30mm round, since it is not real

[Removed] Removed several variants of Mich 2000 and Mich 2001

[Removed] Removed: Game Master - Temporarily removed F/A-18 GBU and KH-55 CAS due to unpredictable crashes



## 0.9.2973

<!-- revision 2973 -->
  
{% hint style="info" %}
### **Release Meta Information**

_<mark style="color:red;">Built from Revision:</mark>_ 2973

_<mark style="color:red;">Date:</mark>_ Monday, July 8, 2024

_<mark style="color:red;">Revisions Since Last:</mark>_ 140 (2833)

_<mark style="color:red;">Changes:</mark>_ 9 additions, 26 improvements, 43 fixes and 0 deletions.
{% endhint %}


##### Added


[Added] GPD-30 Grenade for AGS-30 on K17

[Added] Tucha smoke launcher shot and explosion sounds

[Added] SureFire 3prong muzzle device muzzle flashes for long and short barrels

[Added] M40 Sounds and particles

[Added] GM-94 Shot and handling sounds

[Added] M240 shot sounds

[Added] M17 Shooting sounds

[Added] SV98 Shooting sounds

[Added] K17 and T14 horn sounds


##### Improved


[Improved] Changed position of first PMF 5.1 display in t14

[Improved] Bayonets attached to AN-94 rifles now follow barrel recoil animation

[Improved] Disabled velcro slots on PC Gen II/III pouch setups that don't have a admin panel on the chest

[Improved] Enabled side plates on PC Gen II

[Improved] TS30-A2 scope's reticle and eye relief configuration

[Improved] More accurate FOV for TS30-A2: 2 * (35.5/2 ft atan2 100 yd) = 6.772 deg

[Improved] TA31 RCO magnification

[Improved] Faster 2D vignette movement for Bravo4, PO4x24, TA648 MDO

[Improved] 1P87 + 1P90 2D FOV and PIP magnification

[Improved] 1P87 1P90 2D reticle color, compression and misalignment

[Improved] Particles for AKSu, SR3m, 9m133

[Improved] Sounds for K17 engine

[Improved] Adjusted position of rear veclro on opscore MT and MID

[Improved] Particle effects for SR3m, AKSu, 2a42

[Improved] Interior sounds of K17 engine

[Improved] Shot sounds for 2a42 and 2a82 and AGS30 (Compressor added)

[Improved] Changed: Added hints to items that can be attached with information how they can be used and an icon of the slot that can accept this item

[Improved] Changed: Reordered items in arsenals so that all headwear are together and headphones, masks and eyewear are after helmets

[Improved] Added new anim sequence for k17 ramp getIn/getOut

[Improved] Added antenna jiggle to K17

[Improved] Added collision to K17 rear ramp

[Improved] Tucha sounds

[Improved] 2a42 shooting sounds and particles

[Improved] Added SPH-44 to arsenal box

[Improved] Changed: IR strobes surfaces can now glow when emitting light (f.e. V-Light)

[Improved] Adjusted the order of ops core type helmets in USAF arsenal box so they're grouped more consistently


##### Fixed


[Fixed] Bayonet could not be attached to M27 rifles via inspection

[Fixed] Bayonet could not be attached to AN94 rifles via inspection

[Fixed] 6Kh9 bayonet name did not display correctly in interaction menu

[Fixed] Disabled bayonet slot on CQBR, SOPMOD Block II and ERGO rail variants of M4 rifles - barrels are either too short, or do not have an accessible lug to fit bayonets

[Fixed] Fixed: Helmet attachments disappearing after certain distance from their initial spawn position; Fixes [#871](https://github.com/RHSMODS/statusquo/issues/871)

[Fixed] B-lite and VIP strobe had incorrect names in radial menu

[Fixed] Fixed wrong pos of BlueForce pouch on pcgen3 light; Fixes [#866](https://github.com/RHSMODS/statusquo/issues/866)

[Fixed] Issue [#826](https://github.com/RHSMODS/statusquo/issues/826). AK-105's sights are now zeroed and animated

[Fixed] Fixed AN-94 barrel movement - this was caused by some missing anims (fire mode and trigger animations)

[Fixed] Updated weapon graphs - replaced FullBodyGadget to FullBody and updated weapon inspection variable. This should fix crouched weapon inspection issue

[Fixed] RPLComponent Parent Node error on several assets (most fixes were already in 0.9.2833, but wasn't included in the changelog)

[Fixed] Fixed: IR lights are working again

[Fixed] Fixed: (1.2) Some spall and warheads had old configurations; fixes [#876](https://github.com/RHSMODS/statusquo/issues/876)

[Fixed] Fixed broken scabbard reference in 6B45 rifleman pouch set

[Fixed] Issue [#828](https://github.com/RHSMODS/statusquo/issues/828) Changed inheritance of AK-74M with NPZ rail and GP-25 to inherit from AK-74M w/ GP-25

[Fixed] Ballistics for VOG-30, it matches real data now

[Fixed] Vector 21 and PDU: fixed magnification, reticle scale and consistency with vanilla binoculars

[Fixed] Fixed: wrong configuration of RplComponent of some prefabs; fixes [#880](https://github.com/RHSMODS/statusquo/issues/880)

[Fixed] Fixed: GM CAS not working; fixes [#873](https://github.com/RHSMODS/statusquo/issues/873)

[Fixed] Fixed: GBU particles could start playing long after the explosion if player wasnt looking at them at that time

[Fixed] Fixed wrong position of 6X9 scabbard on rifleman pouch kit

[Fixed] Fixed wrong position of PONOS camera on all helmets

[Fixed] Some .acp files related to 2a42

[Fixed] Fixed: Some ECH variants were accepting wrong helmet covers

[Fixed] Fixed: Attaching headphones from the arsenal could prevent attachment of the mask to the helmet

[Fixed] Fixed: Added NPE prevention to RHS_LaserLightDevice

[Fixed] Fixed M240 bipod lods were missing skinning

[Fixed] Fixed wrong collider type and material on LBH

[Fixed] TOR-2 ground model collider was broken

[Fixed] TOR-2 face shieled was not hiding in FPV; fixes [#857](https://github.com/RHSMODS/statusquo/issues/857)

[Fixed] Fixed: Missing attachable item hints; Fixes [#888](https://github.com/RHSMODS/statusquo/issues/888)

[Fixed] Fixed: Attachable headgear like masks or headphones would still disappear when wearer would go outside of replication range of their spawn position

[Fixed] Fixed: Adjust spotlight angle action progress is wrong; Fixes [#890](https://github.com/RHSMODS/statusquo/issues/890)

[Fixed] Fixed: Weapon deployment not working form M4A1; Fixes [#891](https://github.com/RHSMODS/statusquo/issues/891)

[Fixed] Fixed: SU-260/P MDO item preview was incorrect; fixes [#887](https://github.com/RHSMODS/statusquo/issues/887)

[Fixed] Fixed Wrong sound acp file for DAGR and Orion

[Fixed] Minor log spam caused by clothing

[Fixed] Fixed TOR colliders

[Fixed] Fixed NPE trap in RHS_MuzzleEffectComponent.c

[Fixed] M203 now has the detach and attach ammo actions in inspection; fixes [#897](https://github.com/RHSMODS/statusquo/issues/897)

[Fixed] Fixed: pouches wouldnt show items stored in them for other clients in MP; fixes [#899](https://github.com/RHSMODS/statusquo/issues/899)

[Fixed] Fixed several ground model colliders having wrong material.

[Fixed] Fixed clothing material assign errors; fixes [#872](https://github.com/RHSMODS/statusquo/issues/872)


##### Deleted




## 0.9.2833

<!-- revision 2833 -->
  
{% hint style="info" %}
### **Release Meta Information**

_<mark style="color:red;">Built from Revision:</mark>_ 2833

_<mark style="color:red;">Date:</mark>_ Friday, June 28, 2024

_<mark style="color:red;">Revisions Since Last:</mark>_ 18 (2815)

_<mark style="color:red;">Changes:</mark>_ 1 additions, 3 improvements, 7 fixes and 0 deletions.
{% endhint %}


##### Added


[Added] Micro T1 to redfor Arsenal box


##### Improved


[Improved] Changed: Temporarily disabled IR lights functionality to prevent game from crashing when saving the loadout with NVG

[Improved] Added sounds to m40a5 animations

[Improved] Replaced Micro T1s in blufor Arsenal and weapon prefabs. Now contains version with military designation SU-278/PVS


##### Fixed


[Fixed] Patched two more prefabs (T14 turrets) which could potentially crash the game

[Fixed] Potential fix for 2S1 & T14 crashes

[Fixed] Resaved PDU4 & Garmin works spaces in order to update their graphs and fix console log warnings

[Fixed] Strings and preview image for Zephyr GTX boots

[Fixed] Fixed Character_RHS_RF_SOF_MG.et was missing helmet

[Fixed] Fixed flibe subbelt ground model

[Fixed] Fixed Vest_PCGen_II/Variants/Vest_PCGen_II_rifleman.et and Vest_PCGen_II/Variants/Vest_PCGen_II_tako3.et were missing ground model


##### Deleted




## 0.9.2815

<!-- revision 2815 -->
  
{% hint style="info" %}
### **Release Meta Information**

_<mark style="color:red;">Built from Revision:</mark>_ 2815

_<mark style="color:red;">Date:</mark>_ Thursday, June 27, 2024

_<mark style="color:red;">Revisions Since Last:</mark>_ 240 (2575)

_<mark style="color:red;">Changes:</mark>_ 63 additions, 31 improvements, 57 fixes and 2 deletions.
{% endhint %}


##### Added


[Added] Added AOR2 texture to Crye clothing and FROG pants

[Added] Added OPSCORE LBH

[Added] Added MICH 2000 and MICH 2001

[Added] Added Liberator headset

[Added] Added Sordin headset

[Added] Added ECH helmet cover desert MARPAT

[Added] Added OPSCORE MT and XP with Liberator headset on rail

[Added] Added OPSCORE LBH with Liberator headset on rail

[Added] Added TOR S helmet with Sordin headset on rail

[Added] Added TOR-2 Helmet

[Added] Added ECH with Liberator headset on rail

[Added] Added highcut ECH helmet covers

[Added] Added Bek's Luma boots (localization not done yet)

[Added] Surefire warden

[Added] Surefire socom RC2

[Added] Surefire socom RC3

[Added] Surefire fa762ss

[Added] Surefire prong4

[Added] Surefire prong3

[Added] Surefire muzzles (RC2, RC3, WARDEN, FA762SS, PRONG3, PRONG4)

[Added] LongSleve Hoodie in multicam, black and ATACS

[Added] Added USMC Sub-belt

[Added] Added new PC G3 pouch preset

[Added] Random unit variants in MSV and MEF groups

[Added] Added Tactica pouch preset with no belt

[Added] Added PC G3 pouch preset with no belt

[Added] Vkpo3.0 emr

[Added] Added civilian jeans

[Added] Added TV110 vest

[Added] Added Wartech pouches

[Added] Added new pouches to PC G3

[Added] Added OD and multicam ARS ARMA HSGI belt

[Added] Added Wartech UP101 admin pouch

[Added] Added Wartech UP102 admin pouch

[Added] Added Wartech UP103 medkit pouch

[Added] Added Wartech UP104 utility pouch

[Added] Added Wartech UP108 utility pouch

[Added] Added Wartech UP109 utility pouch

[Added] Added Wartech UP118 utility pouch

[Added] Added Wartech UP120 utility pouch

[Added] Added Blueforce Triple mag pouch

[Added] Added HSGI bleeder medkit pouch

[Added] Added HSGI pistol pouch

[Added] Added Shaw concepts NERD mini pouch

[Added] Added Shaw concepts NERD large pouch

[Added] Added Shaw concepts Placard V3

[Added] Added Shaw concepts Flex pouch

[Added] Added Shaw concepts Raid pouch

[Added] Added PC G3 radio pouch

[Added] Added SU-231A Black

[Added] Added SU-231A Tan

[Added] Added EXPS 3-1 Black

[Added] Added EXPS 3-1 Tan

[Added] Added EXPS 3-2 Black

[Added] Added EXPS 3-2 Tan

[Added] Added EXPS 3-3 Black

[Added] Added EXPS 3-3 Tan

[Added] Added camo version of M27

[Added] Added Camo painted version of SU-231A

[Added] Added black armed MI-8

[Added] Added PC G2 crewman kit

[Added] Strings to MBUS

[Added] Added B-lite strobe


##### Improved


[Improved] Particles of 2a42, 30mm, 2a82, 125mm

[Improved] All OPSCORES and TOR helmet scaled close to ECH

[Improved] KIVER RSP scaled close to ECH

[Improved] Improved model and textures TGPA

[Improved] TGPA new model and textures

[Improved] Changed suspension system on Lowcut ECHs

[Improved] Changed: Reduced all eyewear volume to make them fit most storages; fixes [#799](https://github.com/RHSMODS/statusquo/issues/799)

[Improved] Changed: M4A1 and its variants can accept m9 bayonet

[Improved] Changed: Made 6X9 bayonet functional

[Improved] Changed: M27 and its variants can accept m9 bayonet

[Improved] Changed: AN94 and its variants can accept 6X9-1 or 6Kh4 bayonet

[Improved] Changed: Added bayonets to their respective arsenals

[Improved] Sording and Liberator ground models have colliders; fixes [#804](https://github.com/RHSMODS/statusquo/issues/804)

[Improved] Vkpo3.0 textures and rig

[Improved] Changed: Helmet covers can now enable velcro slots on helmets which may have previously not have velcro slots and at the same time they can also block them if f.e. such cover doesnt have velcro on it

[Improved] Changed: If helmet cover will obstructed already used slot then game will not allow for equipping such cover until player removes that item from the slot that will be obstructed

[Improved] Changed: When player removes helmet cover which enabled velcro slots then items which were attached to it will be moved to other storage in that players inventory or dropped on the ground if that is not possible

[Improved] Vehicle configs now use Multi Lists; work on [#769](https://github.com/RHSMODS/statusquo/issues/769)

[Improved] Switched out some ground models for clothes to more appropriate default models. WIP

[Improved] Improved Various item size fixes

[Improved] Changed capacity of various pouches

[Improved] Tweaked weapon obstruction on M4A1 - fix [#825](https://github.com/RHSMODS/statusquo/issues/825)

[Improved] Improved M27 Rear sight model

[Improved] Changed: Made NVG and weapon laser/light device keybind hints visible only for 10s instead of indefinitely

[Improved] Changed AN-94 recoil pattern.

[Improved] Heavily changed M240 recoil

[Improved] US optic localization

[Improved] Glock localization

[Improved] Adjusted M240B rate of fire, accuracy, and init speed to better match actual performance

[Improved] Added new pouches to USMC kits

[Improved] Added new vanilla 40mm flare rounds and gloves to arsenal as well as some missing magazine ammo variants for ARs, M240, & M249.


##### Fixed


[Fixed] Tracer color of 3UOF6 (Yellow to Red)

[Fixed] Fixed: 1PN138 NVG was sometimes visible in FPP; fixes [#763](https://github.com/RHSMODS/statusquo/issues/763)

[Fixed] Fixed: NVG effect would be removed if user would switch between fullscreen and windowed mode; fixes [#764](https://github.com/RHSMODS/statusquo/issues/764)

[Fixed] Fixed: Wrong configuration of helmet covers and their slots; fixes [#768](https://github.com/RHSMODS/statusquo/issues/768)

[Fixed] Fixed: Rifle clipping when slung over back with only PC Gen III; fixes [#767](https://github.com/RHSMODS/statusquo/issues/767)

[Fixed] Fixed invisible velcro shapes on OPSCORE XP

[Fixed] Added lods to ESS crossbow and Strelok on TOR

[Fixed] Fixed: Not being able to attach patches to the top velcro slot of the pc gen III pouch kit

[Fixed] Fixed: Watch would rotate during some animation when worn on the wrist

[Fixed] Fixed: (1.2) Cas deals no damage; fixes [#789](https://github.com/RHSMODS/statusquo/issues/789)

[Fixed] Fixed: (1.2) NVGs broken; fixes [#777](https://github.com/RHSMODS/statusquo/issues/777)

[Fixed] Fixed: (1.2) 1P21 PiP reticle range animation; fixes [#780](https://github.com/RHSMODS/statusquo/issues/780)

[Fixed] Fixed: (1.2) broken PEQ button sound

[Fixed] Fixed: (1.2) NPE when hovering over items in inventory; fixes [#776](https://github.com/RHSMODS/statusquo/issues/776)

[Fixed] Fixed: (1.2) Missing armor plate state indicator; fixes [#792](https://github.com/RHSMODS/statusquo/issues/792)

[Fixed] Fixed: (1.2) Armor plates take no damage; fixes [#793](https://github.com/RHSMODS/statusquo/issues/793)

[Fixed] Fixed main camera HDR change, when K17/T14 been loaded on client.

[Fixed] Vog pouches volume

[Fixed] Fixed: wrong material used by 40mm marker grenade; fixes [#795](https://github.com/RHSMODS/statusquo/issues/795)

[Fixed] Fixed: (1.2) Disabled UseVirtualInventoryReplication for visible storage

[Fixed] Fixed: (1.2) Converted all projectiles BaseDamageEffect into ProjectileDamage

[Fixed] Colliders on worn MICH helmets were importing wrong

[Fixed] MICH 2000/2001 ground models now have colliders

[Fixed] Fixed: (1.2) Getting in the RF BTR-70 gunner seat crashes the game; fixes [#801](https://github.com/RHSMODS/statusquo/issues/801)

[Fixed] Fixed: (1.2) RPG rockets dont work; fixes [#781](https://github.com/RHSMODS/statusquo/issues/781)

[Fixed] TGP-A collider material fixed

[Fixed] Fixed: NPE due to missing MuzzleUiInfo in MuzzleInMagComponent of SP81

[Fixed] Fixed: (1.2) PSO-1 override was broken; fixes [#811](https://github.com/RHSMODS/statusquo/issues/811)

[Fixed] MBUS Front sight causing alternative wrong sight view; fixes [#807](https://github.com/RHSMODS/statusquo/issues/807)

[Fixed] MBUS Rear Sight was rotating eye point when folding

[Fixed] TOR Peltor variant fixed collider material

[Fixed] Fixed: (1.2) UGL flyby sounds

[Fixed] Fixed Gascan glasses causing character to fly in some conditions

[Fixed] AK-74M GP-25 mag reload sound was not playing

[Fixed] Fixed wrong colliders on Liberator High Cut ECH

[Fixed] Fixed: (1.2) ARTII scope override was broken; fixes [#817](https://github.com/RHSMODS/statusquo/issues/817)

[Fixed] Fixed broken UVs on ECH lowcut with rails and velcro; fixes [#821](https://github.com/RHSMODS/statusquo/issues/821)

[Fixed] Fixed various log spam by RHS armor plates

[Fixed] Fixed PC GEN 2 Ground model was missing collider

[Fixed] M240B now has proper weight

[Fixed] Fixed: Light device keybinds not working in 1.2 expiremental; fixed [#827](https://github.com/RHSMODS/statusquo/issues/827)

[Fixed] Fixed: RHS factions shooting at civilians and non combatants; fixes [#800](https://github.com/RHSMODS/statusquo/issues/800)

[Fixed] M240B Was missing SightsSwitchSkip; Fixes [#832](https://github.com/RHSMODS/statusquo/issues/832)

[Fixed] Restored VehicleWheeledSimulation component in K17 & 2S1, which was removed in rev 2625.

[Fixed] Removed _SA suffix from vehicle components - there is no longer non Server Authority version of vehicle simulation

[Fixed] Initial cleanup of vehicle prefabs

[Fixed] Set "Parent Node From Parent" on some prefabs as warning message suggested

[Fixed] Removed duplicated components (RigidBody) on Ammo_Flare_26x45_Base.et

[Fixed] Fixed 2S1 get in/out

[Fixed] Fixed duplicated Rigidbody on marker grenades

[Fixed] Fixed 6x9 missing locale strings

[Fixed] Wrong laser position on M40A5

[Fixed] Fixed MG_RPK74N_1P78.et was missing 1p78

[Fixed] Fixed draggable 9M133

[Fixed] Fixed SR3M lacking any visual recoil

[Fixed] Revived various K17/T14 Smart systems

[Fixed] Revived triplexes


##### Deleted


[Removed] Outdated unit prefabs

[Removed] Removed: Deleted override of EGadgetType which was adding RHS_GPS as now vanilla has GPS enum



## 0.9.2750

<!-- revision 2750 -->
  
{% hint style="info" %}
### **Release Meta Information**

_<mark style="color:red;">Built from Revision:</mark>_ 2750

_<mark style="color:red;">Date:</mark>_ Wednesday, June 19, 2024

_<mark style="color:red;">Revisions Since Last:</mark>_ 93 (2657)

_<mark style="color:red;">Changes:</mark>_ 6 additions, 13 improvements, 18 fixes and 1 deletions.
{% endhint %}


{% hint style="danger" %}
This release is only available on **Arma: Reforger Experimental**
{% endhint %}


##### Added


[Added] Vkpo3.0 emr

[Added] Added civilian jeans

[Added] Added TV110 vest

[Added] Added Wartech pouches

[Added] Added new pouches to PC G3

[Added] Added OD and multicam ARS ARMA HSGI belt


##### Improved


[Improved] Changed: Reduced all eyewear volume to make them fit most storages; fixes [#799](https://github.com/RHSMODS/statusquo/issues/799)

[Improved] Changed: M4A1 and its variants can accept m9 bayonet

[Improved] Changed: Made 6X9 bayonet functional

[Improved] Changed: M27 and its variants can accept m9 bayonet

[Improved] Changed: AN94 and its variants can accept 6X9-1 or 6Kh4 bayonet

[Improved] Changed: Added bayonets to their respective arsenals

[Improved] Sording and Liberator ground models have colliders; fixes [#804](https://github.com/RHSMODS/statusquo/issues/804)

[Improved] Vkpo3.0 textures and rig

[Improved] Changed: Helmet covers can now enable velcro slots on helmets which may have previously not have velcro slots and at the same time they can also block them if f.e. such cover doesnt have velcro on it

[Improved] Changed: If helmet cover will obstructed already used slot then game will not allow for equipping such cover until player removes that item from the slot that will be obstructed

[Improved] Changed: When player removes helmet cover which enabled velcro slots then items which were attached to it will be moved to other storage in that players inventory or dropped on the ground if that is not possible

[Improved] Vehicle configs now use Multi Lists; work on [#769](https://github.com/RHSMODS/statusquo/issues/769)

[Improved] Switched out some ground models for clothes to more appropriate default models. WIP


##### Fixed


[Fixed] Colliders on worn MICH helmets were importing wrong

[Fixed] MICH 2000/2001 ground models now have colliders

[Fixed] Fixed: (1.2) Getting in the RF BTR-70 gunner seat crashes the game; fixes [#801](https://github.com/RHSMODS/statusquo/issues/801)

[Fixed] Fixed: (1.2) RPG rockets dont work; fixes [#781](https://github.com/RHSMODS/statusquo/issues/781)

[Fixed] TGP-A collider material fixed

[Fixed] Fixed: NPE due to missing MuzzleUiInfo in MuzzleInMagComponent of SP81

[Fixed] Fixed: (1.2) PSO-1 override was broken; fixes [#811](https://github.com/RHSMODS/statusquo/issues/811)

[Fixed] MBUS Front sight causing alternative wrong sight view; fixes [#807](https://github.com/RHSMODS/statusquo/issues/807)

[Fixed] MBUS Rear Sight was rotating eye point when folding

[Fixed] TOR Peltor variant fixed collider material

[Fixed] Fixed: (1.2) UGL flyby sounds

[Fixed] Fixed Gascan glasses causing character to fly in some conditions

[Fixed] AK-74M GP-25 mag reload sound was not playing

[Fixed] Fixed wrong colliders on Liberator High Cut ECH

[Fixed] Fixed: (1.2) ARTII scope override was broken; fixes [#817](https://github.com/RHSMODS/statusquo/issues/817)

[Fixed] Fixed broken UVs on ECH lowcut with rails and velcro; fixes [#821](https://github.com/RHSMODS/statusquo/issues/821)

[Fixed] Fixed various log spam by RHS armor plates

[Fixed] Fixed PC GEN 2 Ground model was missing collider


##### Deleted


[Removed] Outdated unit prefabs



## 0.9.2657

<!-- revision 2657 -->
  
{% hint style="info" %}
### **Release Meta Information**

_<mark style="color:red;">Built from Revision:</mark>_ 2657

_<mark style="color:red;">Date:</mark>_ Saturday, May 25, 2024

_<mark style="color:red;">Revisions Since Last:</mark>_ 304 (2353)

_<mark style="color:red;">Changes:</mark>_ 53 additions, 74 improvements, 80 fixes and 2 deletions.
{% endhint %}


{% hint style="danger" %}
This release is only available on **Arma: Reforger Experimental**
{% endhint %}


##### Added


[Added] Completely reworked RHS Faction system. Instead of USMC and MSV there is AFRF and USAF now. MSV and USMC moved to branches.

[Added] Added Emissive texture to ECH_LowCover Cateyes

[Added] Added Velocity Shirt Multicam

[Added] Added AK-74M and AK-105 with Zenitco B10M rail in black; fixes [#713](https://github.com/RHSMODS/statusquo/issues/713)

[Added] Added Multicam and OD versions of the Velocity shirt to Arsenal

[Added] Added ECH lowcut woodland covered version and cover to arsenal

[Added] Added fuel counter to K-17 and T-14

[Added] Added "Medic" preset to AFRF arsenal

[Added] Added NT4 soft covers (black and multicam)

[Added] Added AK-74M with TGP-A silencer

[Added] Added M240B

[Added] Added ESS Crossbow

[Added] Added PVS-31 Battery pack

[Added] Added black ESS Crossbow

[Added] Added tan Kondor glasses

[Added] Added olive Kondor glasses

[Added] Added ODG Manta items and Updated TAN & BLK

[Added] Added unarmed K-17 in EXPO camo

[Added] AI Ballistic tables for 30mm rounds

[Added] AI Ballistic tables for 125mm rounds

[Added] Added version of M240B with light stock and supports

[Added] Vkpo 3.0

[Added] EPM magazine

[Added] MCT windowed PMAG

[Added] En and ru localization of actions on T14/K17 screens

[Added] Added AFRF Helicopter Pilots

[Added] RPG-7V with RHS PGO7V prefab for RHS units

[Added] Added AOR2 texture to Crye clothing and FROG pants

[Added] Added OPSCORE LBH

[Added] Added MICH 2000 and MICH 2001

[Added] Added Liberator headset

[Added] Added Sordin headset

[Added] Added ECH helmet cover desert MARPAT

[Added] Added OPSCORE MT and XP with Liberator headset on rail

[Added] Added OPSCORE LBH with Liberator headset on rail

[Added] Added TOR S helmet with Sordin headset on rail

[Added] Added TOR-2 Helmet

[Added] Added ECH with Liberator headset on rail

[Added] Added highcut ECH helmet covers

[Added] Added Bek's Luma boots (localization not done yet)

[Added] Surefire warden

[Added] Surefire socom RC2

[Added] Surefire socom RC3

[Added] Surefire fa762ss

[Added] Surefire prong4

[Added] Surefire prong3

[Added] Surefire muzzles (RC2, RC3, WARDEN, FA762SS, PRONG3, PRONG4)

[Added] LongSleve Hoodie in multicam, black and ATACS

[Added] Added USMC Sub-belt

[Added] Added new PC G3 pouch preset

[Added] Random unit variants in MSV and MEF groups

[Added] Added Tactica pouch preset with no belt

[Added] Added PC G3 pouch preset with no belt


##### Improved


[Improved] Orion now has boot screen when turning on

[Improved] Added proper prices to items in arsenal

[Improved] Readded LODs back to RPK-74M

[Improved] Added LODs to PGO-7V3; fixes [#710](https://github.com/RHSMODS/statusquo/issues/710)

[Improved] [Modding] For compatibility reason EGadgetType.GPS was renamed to EGadgetType.RHS_GPS

[Improved] Removed tons of unused materials

[Improved] AK-74M with Zenitco B-10M can now mount GP-25; fixes [#712](https://github.com/RHSMODS/statusquo/issues/712)

[Improved] K-17 GM description was too long for some low resolutions, blocking out other UI

[Improved] Improved changed PG7VR volume size from 1200 to 2000

[Improved] Changed view distance for T-14 and K-17 turret animation from 1k to 2k (this means that you will see turret actually rotating from longer distances)

[Improved] Added more gain steps to REAP-IR, 1TWS, PATROL-IR, SNIPE-IR

[Improved] Improved brain damage system on K-17 and T-14

[Improved] Key binding names more consistent

[Improved] Refactored DAGR to new system

[Improved] Performance for T14 shells

[Improved] Added door control panel to gunner and commander seat it K-17

[Improved] Changed amount of gears on T-14 gearbox 4->14

[Improved] Decreased engine torque on T-14

[Improved] Decreased engine power on T-14

[Improved] Decreased main differential ratio on T-14

[Improved] Recalculated aerodynamic frontal drag on T-14

[Improved] Changed brake settings on K-17

[Improved] Recalculated aerodynamic frontal drag on K-17

[Improved] Changed center of mass on K-17

[Improved] Added weight of turret to K-17 overall weight calculation

[Improved] Player no longer able to use any sights/optics with PATROL-IR

[Improved] Revived procedural numbers and labels on vehicles

[Improved] Changed priority of which pouch is filled first when item is transferred - 1st mag pouches that change their shape to show stored item, 2nd simple pouches with visible items, 3rd pouches that dont have items visible and after that everything else

[Improved] Improved rugby shirt patch locations; fixes [#735](https://github.com/RHSMODS/statusquo/issues/735)

[Improved] Changed: Far less temporary textures for US 40mm GL rounds

[Improved] Changed: Updated preview for M585, XM663 and XM664 to show letter that corresponds to the color of the stars

[Improved] Added M406, M713, M715, M716, M585, XM663 and XM664 US GL Rounds to the USMC arsenal

[Improved] BLK & ODG Manta emat

[Improved] 125mm drag calculations

[Improved] 30mm drag calculations

[Improved] AI turret target movement speeds

[Improved] Armor plates will now knock the wind of out of the wearer when bullet dont penetrate it to the point that user can get knocked out

[Improved] Slightly adjusted vehicle Thermal distortion noise

[Improved] M240B has internals now

[Improved] 30mm HE particles

[Improved] Internal sounds for k17 engine

[Improved] Changed: Added second velctro slot to the PCGen III vest (pouches) above the first one; fixes [#751](https://github.com/RHSMODS/statusquo/issues/751)

[Improved] Changed: Made it possible to attach two medium size patches to 35L FLIBE backpack

[Improved] Overhaul of M4 stringtable

[Improved] Finished US weapon localization

[Improved] T14/K17 gunner/driver screens can be disabled

[Improved] T14/K17 gunner/driver camera HDR brightness can be adjusted

[Improved] TOR helmets in arsenal now have covers by default

[Improved] Added vanilla PGO7V to AFRF arsenal

[Improved] Cleanup of optic prefabs: added inheritance from vanilla base prefabs and components, removed of obsolete attribute defines, improved consistency

[Improved] M8541 mildot reticle PIP texture and material improvements

[Improved] M8541 and Leupold Mk4 FOVs, 2D reticle

[Improved] PO4x24 FOV and 2D optics

[Improved] Bravo4 reticle precision improved

[Improved] SU-260/P MDO reticle texture quality

[Improved] SU-260/P FOVs

[Improved] Added ability to remove / attach eyecup to 1p21

[Improved] Added zoom wheel animation to 1p21

[Improved] Improved 1p21 Texture

[Improved] 1PN93 reticle textures and materials

[Improved] 1PN93 FOVs

[Improved] PGO-7V3, 1PN93-2 RPG use vanilla PGO-7V3 reticle

[Improved] PG-7VL, PG-7VR and TBG-7V ballistics made compatible with vanilla PGO-7V3

[Improved] OG-7V ballistics fit with vanilla PGO-7V3

[Improved] Vkpo3.0 textures

[Improved] ATACS ballcap color matching

[Improved] STANAG EPM magazines added to the arsenal

[Improved] Changed price of ak74 with tgpa to match with BLUFOR silencers and PBS-4 pricings

[Improved] Particles of 2a42, 30mm, 2a82, 125mm

[Improved] All OPSCORES and TOR helmet scaled close to ECH

[Improved] KIVER RSP scaled close to ECH

[Improved] Improved model and textures TGPA

[Improved] TGPA new model and textures

[Improved] Changed suspension system on Lowcut ECHs


##### Fixed


[Fixed] Fixed showcase scenario

[Fixed] Fixed ECH_LowCover textures

[Fixed] Particles for 30mm HE shells

[Fixed] Fixed wrong rail position on RPK-74N

[Fixed] Revived SNIPE-IR

[Fixed] Being able to use night vision when helmet to which they were mounted was removed

[Fixed] Laser range finders work again

[Fixed] Fixed wrong roughness on MBUS

[Fixed] Fixed wrong reticle size and brightness on 1P63

[Fixed] Camo repair Ural now has camo on the back; fixes [#711](https://github.com/RHSMODS/statusquo/issues/711)

[Fixed] Fixed some incorrect collider settings in models

[Fixed] Fixed some incorrect texture assignments in materials

[Fixed] Some Zenitco railed rifles has wrong inventory name

[Fixed] White flare console errors

[Fixed] Kh-55 was pointing to wrong particle effect

[Fixed] Fixed K17 "open driver hatch" action was broken

[Fixed] Fixed HDR broken when opening map with NVG googles and thermal sight

[Fixed] Fixed K17 and T14 turret Optic destruction

[Fixed] Fixed T14 PMF brains HitZone info

[Fixed] Fixed K17/T14 PMF Turret orientation angle

[Fixed] Fixed T14 PMF damage screen visibility

[Fixed] Fixed wrong recoil on REAP-IR, SNIPE-IR, TWS1

[Fixed] Fixed reinit of hdr after opening menu while using thermal optic

[Fixed] FROG Trouser blood VFX textures

[Fixed] Controller key bindings are now settable; fixes [#731](https://github.com/RHSMODS/statusquo/issues/731)

[Fixed] BOSS Rugby Multicam now has correct name and image in inventory; fixes [#728](https://github.com/RHSMODS/statusquo/issues/728)

[Fixed] Fixed VehSimple and VehComplex colliders on T14

[Fixed] Revived DAGR; fixes [#724](https://github.com/RHSMODS/statusquo/issues/724)

[Fixed] Fixed footwear inventory icons in arsenal

[Fixed] Incorrect name 3OF36 -> 3OF26

[Fixed] Overly large vehiclesimple collider for T14

[Fixed] Taktika groin, left, and right plates now actually work

[Fixed] Fixed K-17 berezhok turret missing viewGeo collider

[Fixed] Fixed K-17 Berezhok destructible optic collider not following turret

[Fixed] Fixed K-17 Epoch destructible optic ccollider not following turret in vertical axis

[Fixed] Fixed base coverage for all seats in K-17 and T-14 to match with BTR-70 from vanilla

[Fixed] Fixed M27 no longer falls through the ground

[Fixed] Items stored in pouches or attached to the helmet wouldnt impact loadout cost; fixes [#734](https://github.com/RHSMODS/statusquo/issues/734) and fixes [#725](https://github.com/RHSMODS/statusquo/issues/725)

[Fixed] Fixed 2S1 Vehicle collider

[Fixed] Fixed Manta NMO

[Fixed] 30mm explosion particles spawn

[Fixed] Fixes to publication tools to try to help avoid false positives

[Fixed] Fixed Crye pants clipping with leg; Fixes [#747](https://github.com/RHSMODS/statusquo/issues/747)

[Fixed] Fixed: unable to place AN-94 in vehicle storage; fixes [#753](https://github.com/RHSMODS/statusquo/issues/753)

[Fixed] Fixed GBU-12 explosion particle was using OnVisible event instead of OnFrame

[Fixed] Removed broken ground fire particle from t-14 (BI, please fix)

[Fixed] NVGs were not attaching correctly to base lowcut ECH; fixes [#737](https://github.com/RHSMODS/statusquo/issues/737)

[Fixed] Fixed thermal NPEs

[Fixed] Bad icon setting for M17/M18 base prefab

[Fixed] Fixed k17 wheels not rotating from distance further than 75 meters

[Fixed] Fixed T14 HE shell impulse

[Fixed] Fixed Editable component for AFRF VV

[Fixed] Fixed 1P21 FOVs in PIP and 2D modes

[Fixed] Vkpo3.0 patches and garmin comp

[Fixed] RPK-74M stock was folding wrong way; fixes [#766](https://github.com/RHSMODS/statusquo/issues/766)

[Fixed] Coyote PMAGs should not be causing loadout save errors anymore

[Fixed] Bravo 4 reticle size was halved

[Fixed] Fixed wrong wristwatch rotation on hand

[Fixed] Fixed k17 finally float again

[Fixed] Tracer color of 3UOF6 (Yellow to Red)

[Fixed] Fixed: 1PN138 NVG was sometimes visible in FPP; fixes [#763](https://github.com/RHSMODS/statusquo/issues/763)

[Fixed] Fixed: NVG effect would be removed if user would switch between fullscreen and windowed mode; fixes [#764](https://github.com/RHSMODS/statusquo/issues/764)

[Fixed] Fixed: Wrong configuration of helmet covers and their slots; fixes [#768](https://github.com/RHSMODS/statusquo/issues/768)

[Fixed] Fixed: Rifle clipping when slung over back with only PC Gen III; fixes [#767](https://github.com/RHSMODS/statusquo/issues/767)

[Fixed] Fixed invisible velcro shapes on OPSCORE XP

[Fixed] Added lods to ESS crossbow and Strelok on TOR

[Fixed] Fixed: Not being able to attach patches to the top velcro slot of the pc gen III pouch kit

[Fixed] Fixed: Watch would rotate during some animation when worn on the wrist

[Fixed] Fixed: (1.2) Cas deals no damage; fixes [#789](https://github.com/RHSMODS/statusquo/issues/789)

[Fixed] Fixed: (1.2) NVGs broken; fixes [#777](https://github.com/RHSMODS/statusquo/issues/777)

[Fixed] Fixed: (1.2) 1P21 PiP reticle range animation; fixes [#780](https://github.com/RHSMODS/statusquo/issues/780)

[Fixed] Fixed: (1.2) broken PEQ button sound

[Fixed] Fixed: (1.2) NPE when hovering over items in inventory; fixes [#776](https://github.com/RHSMODS/statusquo/issues/776)

[Fixed] Fixed: (1.2) Missing armor plate state indicator; fixes [#792](https://github.com/RHSMODS/statusquo/issues/792)

[Fixed] Fixed: (1.2) Armor plates take no damage; fixes [#793](https://github.com/RHSMODS/statusquo/issues/793)

[Fixed] Fixed main camera HDR change, when K17/T14 been loaded on client.

[Fixed] Vog pouches volume

[Fixed] Fixed: wrong material used by 40mm marker grenade; fixes [#795](https://github.com/RHSMODS/statusquo/issues/795)

[Fixed] Fixed: (1.2) Disabled UseVirtualInventoryReplication for visible storage

[Fixed] Fixed: (1.2) Converted all projectiles BaseDamageEffect into ProjectileDamage


##### Deleted


[Removed] Disabled thermals until hotfix

[Removed] Removed buggy Bravo 4 with T1; fixes [#755](https://github.com/RHSMODS/statusquo/issues/755)


