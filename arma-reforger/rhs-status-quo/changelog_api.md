---
description: >-
  This document is regenerated automatically from our systems at a time of a
  release.
---

# Changelog

<!-- reset point -->
<!-- changelog insert -->

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


