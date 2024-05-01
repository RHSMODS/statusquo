---
description: >-
  This document is regenerated automatically from our systems at a time of a
  release.
---

# Changelog

<!-- reset point -->
<!-- changelog insert -->

## 0.8.2568

<!-- revision 2568 -->
  
{% hint style="info" %}
### **Release Meta Information**

_<mark style="color:red;">Built from Revision:</mark>_ 2568

_<mark style="color:red;">Date:</mark>_ Wednesday, May 1, 2024

_<mark style="color:red;">Revisions Since Last:</mark>_ 1 (2567)

_<mark style="color:red;">Changes:</mark>_ 0 additions, 0 improvements, 1 fixes and 0 deletions.
{% endhint %}


##### Added



##### Improved



##### Fixed


[Fixed] Coyote PMAGs should not be causing loadout save errors anymore


##### Deleted




## 0.8.2567

<!-- revision 2567 -->
  
{% hint style="info" %}
### **Release Meta Information**

_<mark style="color:red;">Built from Revision:</mark>_ 2567

_<mark style="color:red;">Date:</mark>_ Wednesday, May 1, 2024

_<mark style="color:red;">Revisions Since Last:</mark>_ 122 (2445)

_<mark style="color:red;">Changes:</mark>_ 19 additions, 52 improvements, 26 fixes and 1 deletions.
{% endhint %}


##### Added


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


##### Improved


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


##### Fixed


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


##### Deleted


[Removed] Removed buggy Bravo 4 with T1; fixes [#755](https://github.com/RHSMODS/statusquo/issues/755)



## 0.8.2445

<!-- revision 2445 -->
  
{% hint style="info" %}
### **Release Meta Information**

_<mark style="color:red;">Built from Revision:</mark>_ 2445

_<mark style="color:red;">Date:</mark>_ Wednesday, March 27, 2024

_<mark style="color:red;">Revisions Since Last:</mark>_ 4 (2441)

_<mark style="color:red;">Changes:</mark>_ 0 additions, 0 improvements, 1 fixes and 0 deletions.
{% endhint %}


##### Added



##### Improved



##### Fixed


[Fixed] Fixed footwear inventory icons in arsenal


##### Deleted




## 0.8.2441

<!-- revision 2441 -->
  
{% hint style="info" %}
### **Release Meta Information**

_<mark style="color:red;">Built from Revision:</mark>_ 2441

_<mark style="color:red;">Date:</mark>_ Tuesday, March 26, 2024

_<mark style="color:red;">Revisions Since Last:</mark>_ 32 (2409)

_<mark style="color:red;">Changes:</mark>_ 3 additions, 6 improvements, 9 fixes and 0 deletions.
{% endhint %}


##### Added


[Added] Added ECH lowcut woodland covered version and cover to arsenal

[Added] Added fuel counter to K-17 and T-14

[Added] Added "Medic" preset to AFRF arsenal


##### Improved


[Improved] Improved changed PG7VR volume size from 1200 to 2000

[Improved] Changed view distance for T-14 and K-17 turret animation from 1k to 2k (this means that you will see turret actually rotating from longer distances)

[Improved] Added more gain steps to REAP-IR, 1TWS, PATROL-IR, SNIPE-IR

[Improved] Improved brain damage system on K-17 and T-14

[Improved] Key binding names more consistent

[Improved] Refactored DAGR to new system


##### Fixed


[Fixed] Fixed K17/T14 PMF Turret orientation angle

[Fixed] Fixed T14 PMF damage screen visibility

[Fixed] Fixed wrong recoil on REAP-IR, SNIPE-IR, TWS1

[Fixed] Fixed reinit of hdr after opening menu while using thermal optic

[Fixed] FROG Trouser blood VFX textures

[Fixed] Controller key bindings are now settable; fixes [#731](https://github.com/RHSMODS/statusquo/issues/731)

[Fixed] BOSS Rugby Multicam now has correct name and image in inventory; fixes [#728](https://github.com/RHSMODS/statusquo/issues/728)

[Fixed] Fixed VehSimple and VehComplex colliders on T14

[Fixed] Revived DAGR; fixes [#724](https://github.com/RHSMODS/statusquo/issues/724)


##### Deleted




## 0.8.2409

<!-- revision 2409 -->
  
{% hint style="info" %}
### **Release Meta Information**

_<mark style="color:red;">Built from Revision:</mark>_ 2409

_<mark style="color:red;">Date:</mark>_ Tuesday, March 19, 2024

_<mark style="color:red;">Revisions Since Last:</mark>_ 4 (2405)

_<mark style="color:red;">Changes:</mark>_ 1 additions, 0 improvements, 4 fixes and 0 deletions.
{% endhint %}


##### Added


[Added] Added Multicam and OD versions of the Velocity shirt to Arsenal


##### Improved



##### Fixed


[Fixed] Fixed K17 "open driver hatch" action was broken

[Fixed] Fixed HDR broken when opening map with NVG googles and thermal sight

[Fixed] Fixed K17 and T14 turret Optic destruction

[Fixed] Fixed T14 PMF brains HitZone info


##### Deleted




## 0.8.2405

<!-- revision 2405 -->
  
{% hint style="info" %}
### **Release Meta Information**

_<mark style="color:red;">Built from Revision:</mark>_ 2405

_<mark style="color:red;">Date:</mark>_ Sunday, March 17, 2024

_<mark style="color:red;">Revisions Since Last:</mark>_ 1 (2404)

_<mark style="color:red;">Changes:</mark>_ 0 additions, 0 improvements, 2 fixes and 0 deletions.
{% endhint %}


##### Added



##### Improved



##### Fixed


[Fixed] White flare console errors

[Fixed] Kh-55 was pointing to wrong particle effect


##### Deleted




## 0.8.2404

<!-- revision 2404 -->
  
{% hint style="info" %}
### **Release Meta Information**

_<mark style="color:red;">Built from Revision:</mark>_ 2404

_<mark style="color:red;">Date:</mark>_ Sunday, March 17, 2024

_<mark style="color:red;">Revisions Since Last:</mark>_ 16 (2388)

_<mark style="color:red;">Changes:</mark>_ 2 additions, 7 improvements, 6 fixes and 0 deletions.
{% endhint %}


##### Added


[Added] Added Velocity Shirt Multicam

[Added] Added AK-74M and AK-105 with Zenitco B10M rail in black; fixes [#713](https://github.com/RHSMODS/statusquo/issues/713)


##### Improved


[Improved] Added proper prices to items in arsenal

[Improved] Readded LODs back to RPK-74M

[Improved] Added LODs to PGO-7V3; fixes [#710](https://github.com/RHSMODS/statusquo/issues/710)

[Improved] [Modding] For compatibility reason EGadgetType.GPS was renamed to EGadgetType.RHS_GPS

[Improved] Removed tons of unused materials

[Improved] AK-74M with Zenitco B-10M can now mount GP-25; fixes [#712](https://github.com/RHSMODS/statusquo/issues/712)

[Improved] K-17 GM description was too long for some low resolutions, blocking out other UI


##### Fixed


[Fixed] Fixed wrong roughness on MBUS

[Fixed] Fixed wrong reticle size and brightness on 1P63

[Fixed] Camo repair Ural now has camo on the back; fixes [#711](https://github.com/RHSMODS/statusquo/issues/711)

[Fixed] Fixed some incorrect collider settings in models

[Fixed] Fixed some incorrect texture assignments in materials

[Fixed] Some Zenitco railed rifles has wrong inventory name


##### Deleted




## 0.8.2388

<!-- revision 2388 -->
  
{% hint style="info" %}
### **Release Meta Information**

_<mark style="color:red;">Built from Revision:</mark>_ 2388

_<mark style="color:red;">Date:</mark>_ Thursday, March 14, 2024

_<mark style="color:red;">Revisions Since Last:</mark>_ 19 (2369)

_<mark style="color:red;">Changes:</mark>_ 0 additions, 0 improvements, 4 fixes and 1 deletions.
{% endhint %}


##### Added



##### Improved



##### Fixed


[Fixed] Fixed wrong rail position on RPK-74N

[Fixed] Revived SNIPE-IR

[Fixed] Being able to use night vision when helmet to which they were mounted was removed

[Fixed] Laser range finders work again


##### Deleted


[Removed] Disabled thermals until hotfix



## 0.8.2369

<!-- revision 2369 -->
  
{% hint style="info" %}
### **Release Meta Information**

_<mark style="color:red;">Built from Revision:</mark>_ 2369

_<mark style="color:red;">Date:</mark>_ Wednesday, March 13, 2024

_<mark style="color:red;">Revisions Since Last:</mark>_ 104 (2265)

_<mark style="color:red;">Changes:</mark>_ 33 additions, 12 improvements, 13 fixes and 0 deletions.
{% endhint %}


##### Added


[Added] Added MOHOC Camera standalone attachment

[Added] Added TOR counterweight pouch

[Added] Added Cheshire Cat patch

[Added] Added Switch MPLS light

[Added] Added black, olive and emr TOR counterweight pouch

[Added] Added more pouches to PC GEN 3

[Added] Added Velocity shirt

[Added] Added Black G3 shirt and pants

[Added] Added Altama boots

[Added] Added brown velocity shirt

[Added] Added OD velocity shirt

[Added] Added T-14 PMF damage screen

[Added] Added black Taktika variant

[Added] Added Black Taktika Pouch preset

[Added] Added SR-3M (Black)

[Added] Added SR-3M (Desert paintjob)

[Added] Added SR-3M (Green paintjob)

[Added] Added shoulder protection to Taktika vest

[Added] Added neck protection to Taktika vest

[Added] Added AK-105 with Zenitco B30U and B31N rails in black and tan

[Added] Added AK-105 with Zenitco B30U and B19N rails in black and tan

[Added] Added AK-105 with Zenitco B10M and B19N rails in black and tan

[Added] Added AK-105 with Zenitco B10M and B19 rails in black and tan

[Added] Added RG ATACS units

[Added] Added SOBR black presets

[Added] Added AK-74M with Zenitco B10M and B19 rails in black and tan

[Added] Added AK-74M with Zenitco B10M and B19N rails in black and tan

[Added] Added AK-74M with Zenitco B30U and B19N rails in black and tan

[Added] Added AK-74M with Zenitco B30U and B31N rails in black and tan

[Added] Added Rocky_SV2_Boots model and textures. Initial prefab setup.

[Added] Orion GPS now has basic functionality in inspect mode

[Added] Completely reworked RHS Faction system. Instead of USMC and MSV there is AFRF and USAF now. MSV and USMC moved to branches.

[Added] Added Emissive texture to ECH_LowCover Cateyes


##### Improved


[Improved] Tweaked RPK-74M textures.

[Improved] Regenerated navmesh on test atol - fixes  [#683](https://github.com/RHSMODS/statusquo/issues/683)

[Improved] Changed ocean sim on RHS Atol terrain to something less aggressive foam/wave wise

[Improved] Detached AK-74M muzzle from base weapon

[Improved] Tweaks to most PiP HDR materials to work better with new lighting; fixes [#681](https://github.com/RHSMODS/statusquo/issues/681)

[Improved] Improved 6L26 texture

[Improved] Daniel Offense Rails & textures

[Improved] Tweaks to 6B47 collider

[Improved] Changed NVG Gadget Type to use new type that was added by BI (EGadgetType.NIGHT_VISION)

[Improved] SR3M now has melee; fixes [#698](https://github.com/RHSMODS/statusquo/issues/698)

[Improved] Rail covers now stay at LOD0 in inventory preview

[Improved] Orion now has boot screen when turning on


##### Fixed


[Fixed] Fixed barrel texture on RPK-74 not working anymore.

[Fixed] Scripts compile for 1.1 and version bumped to 0.8

[Fixed] Fixed various console log errors

[Fixed] Fixed Charge Pro opacity

[Fixed] Fixed Switch MPLS localization

[Fixed] Fix to RHS gadgets error related to animation graphs

[Fixed] Fixed muzzle devices not respawning correctly on rifles in some cases; fixes [#696](https://github.com/RHSMODS/statusquo/issues/696)

[Fixed] Fixed Solomon X Ultra weight paint on LODs 1-4

[Fixed] Fixed 2S1 Replication crush; fixes [#689](https://github.com/RHSMODS/statusquo/issues/689)

[Fixed] Fixed right rail attachment position on Kiver RSP

[Fixed] Fixed showcase scenario

[Fixed] Fixed ECH_LowCover textures

[Fixed] Particles for 30mm HE shells


##### Deleted




## 0.8.2353

<!-- revision 2353 -->
  
{% hint style="info" %}
### **Release Meta Information**

_<mark style="color:red;">Built from Revision:</mark>_ 2353

_<mark style="color:red;">Date:</mark>_ Tuesday, March 12, 2024

_<mark style="color:red;">Revisions Since Last:</mark>_ 42 (2311)

_<mark style="color:red;">Changes:</mark>_ 18 additions, 3 improvements, 1 fixes and 0 deletions.
{% endhint %}


{% hint style="danger" %}
This release is only available on **Arma: Reforger Experimental**
{% endhint %}


##### Added


[Added] Added Black Taktika Pouch preset

[Added] Added SR-3M (Black)

[Added] Added SR-3M (Desert paintjob)

[Added] Added SR-3M (Green paintjob)

[Added] Added shoulder protection to Taktika vest

[Added] Added neck protection to Taktika vest

[Added] Added AK-105 with Zenitco B30U and B31N rails in black and tan

[Added] Added AK-105 with Zenitco B30U and B19N rails in black and tan

[Added] Added AK-105 with Zenitco B10M and B19N rails in black and tan

[Added] Added AK-105 with Zenitco B10M and B19 rails in black and tan

[Added] Added RG ATACS units

[Added] Added SOBR black presets

[Added] Added AK-74M with Zenitco B10M and B19 rails in black and tan

[Added] Added AK-74M with Zenitco B10M and B19N rails in black and tan

[Added] Added AK-74M with Zenitco B30U and B19N rails in black and tan

[Added] Added AK-74M with Zenitco B30U and B31N rails in black and tan

[Added] Added Rocky_SV2_Boots model and textures. Initial prefab setup.

[Added] Orion GPS now has basic functionality in inspect mode


##### Improved


[Improved] Changed NVG Gadget Type to use new type that was added by BI (EGadgetType.NIGHT_VISION)

[Improved] SR3M now has melee; fixes [#698](https://github.com/RHSMODS/statusquo/issues/698)

[Improved] Rail covers now stay at LOD0 in inventory preview


##### Fixed


[Fixed] Fixed right rail attachment position on Kiver RSP


##### Deleted




## 0.8.2311

<!-- revision 2311 -->
  
{% hint style="info" %}
### **Release Meta Information**

_<mark style="color:red;">Built from Revision:</mark>_ 2311

_<mark style="color:red;">Date:</mark>_ Tuesday, March 5, 2024

_<mark style="color:red;">Revisions Since Last:</mark>_ 43 (2268)

_<mark style="color:red;">Changes:</mark>_ 13 additions, 7 improvements, 7 fixes and 0 deletions.
{% endhint %}


{% hint style="danger" %}
This release is only available on **Arma: Reforger Experimental**
{% endhint %}


##### Added


[Added] Added MOHOC Camera standalone attachment

[Added] Added TOR counterweight pouch

[Added] Added Cheshire Cat patch

[Added] Added Switch MPLS light

[Added] Added black, olive and emr TOR counterweight pouch

[Added] Added more pouches to PC GEN 3

[Added] Added Velocity shirt

[Added] Added Black G3 shirt and pants

[Added] Added Altama boots

[Added] Added brown velocity shirt

[Added] Added OD velocity shirt

[Added] Added T-14 PMF damage screen

[Added] Added black Taktika variant


##### Improved


[Improved] Regenerated navmesh on test atol - fixes  [#683](https://github.com/RHSMODS/statusquo/issues/683)

[Improved] Changed ocean sim on RHS Atol terrain to something less aggressive foam/wave wise

[Improved] Detached AK-74M muzzle from base weapon

[Improved] Tweaks to most PiP HDR materials to work better with new lighting; fixes [#681](https://github.com/RHSMODS/statusquo/issues/681)

[Improved] Improved 6L26 texture

[Improved] Daniel Offense Rails & textures

[Improved] Tweaks to 6B47 collider


##### Fixed


[Fixed] Fixed various console log errors

[Fixed] Fixed Charge Pro opacity

[Fixed] Fixed Switch MPLS localization

[Fixed] Fix to RHS gadgets error related to animation graphs

[Fixed] Fixed muzzle devices not respawning correctly on rifles in some cases; fixes [#696](https://github.com/RHSMODS/statusquo/issues/696)

[Fixed] Fixed Solomon X Ultra weight paint on LODs 1-4

[Fixed] Fixed 2S1 Replication crush; fixes [#689](https://github.com/RHSMODS/statusquo/issues/689)


##### Deleted




## 0.8.2268

<!-- revision 2268 -->
  
{% hint style="info" %}
### **Release Meta Information**

_<mark style="color:red;">Built from Revision:</mark>_ 2268

_<mark style="color:red;">Date:</mark>_ Tuesday, February 20, 2024

_<mark style="color:red;">Revisions Since Last:</mark>_ 118 (2150)

_<mark style="color:red;">Changes:</mark>_ 14 additions, 28 improvements, 27 fixes and 1 deletions.
{% endhint %}


{% hint style="danger" %}
This release is only available on **Arma: Reforger Experimental**
{% endhint %}


##### Added


[Added] 30mm HE explosion sounds

[Added] 30mm, 125mm and 122mm shells sonic cracks and flybyes added (need test)

[Added] Added X Ultra pioneer boots

[Added] Added X Ultra 4 boots

[Added] Added G3 pants (ATACS-FG)

[Added] Added G3 pants (OD)

[Added] Added G3 pants (Multicam)

[Added] Added voice notifications to T14 and K17

[Added] Daniel Offense 9.55' ,12.25' ,12.25' FSP variants

[Added] Daniel Offense FDE & BLK set colors

[Added] Added AK-105

[Added] Added M4A1 with Ergo Forward Rail Extension and AFG-2 (AFG not mountable yet)

[Added] 10.3' ,14.5' ,14.5' HB Barrels & Textures

[Added] SureFure 4 Prong Flashhider


##### Improved


[Improved] Shell hit sounds

[Improved] Sonic cracks for shells

[Improved] Kh55 engine sound

[Improved] Kh55 sounds and particles

[Improved] Improved 6B47 mesh

[Improved] Potential compatibility fix for item insertion into pouches

[Improved] Added new pouch to PCGEN3 rifleman loadout

[Improved] Regenerated K17 editor previews + fixed their import settings

[Improved] Regenerated preview images for 2S1 & IL76

[Improved] Corrected inspection slot position for PC Gen III Vest with pouches

[Improved] Increased supply storage on K17 Unarmed

[Improved] Added LODs to rhs_su230

[Improved] Added LODs to rhs_su230_mrds

[Improved] Added LODs to rhs_pouch_6X9-1_bayonet

[Improved] Added LODs to rhs_scabbard_6X9-1_bayonet

[Improved] Added LODs to FILBE_hydration_pack

[Improved] Added LODs to FILBE_hydration_pack_ground

[Improved] Added LODs to r187p1

[Improved] Added LODs to garmin_tactix_bravo

[Improved] Added LODs to anpeq15

[Improved] Added LODs to aksu_ltsu

[Improved] Added LODs to rpk74m

[Improved] Added LODs to m27iar

[Improved] Helstar and MS2k are oriented in same way now, so both should be attachable to top and back Velcro on helmets; fixes [#608](https://github.com/RHSMODS/statusquo/issues/608)

[Improved] Added localization for MP-443 pistol

[Improved] MS2k, HELLSTAR6 and VIP Strobes can now be attached both to helmet top and back velcro slots; fixes [#668](https://github.com/RHSMODS/statusquo/issues/668)

[Improved] Changed K-17 armor (Sides 35mm->20mm. Side UParmor 30mm->10mm. Front UParmor 40mm->15mm. Interior armor 30mm->5mm). It means that K-17 side armor is now vulnerable to 12.7 AP. However it doesnt mean that you can flame it by just shooting at passanger compartment. You still need to target engine, fuel tanks, and other critical elements.

[Improved] Tweaked RPK-74M textures.


##### Fixed


[Fixed] Custom bullet flyby sounds not working

[Fixed] Fixed some of the broken PiP scopes after AR update

[Fixed] Fixed radial menu entry null reference exception with shadow item

[Fixed] Not being able to control attached light devices and missing radial menu actions; fixes [#653](https://github.com/RHSMODS/statusquo/issues/653) and [#655](https://github.com/RHSMODS/statusquo/issues/655)

[Fixed] Patches that were attached to the helmet would be visible in FPP; fixes [#654](https://github.com/RHSMODS/statusquo/issues/654)

[Fixed] Being able to put backpack radio into taktika radio pouch

[Fixed] Fixed RITA turn off button was doing nothing

[Fixed] Fixed T14 Turret now can be repaired

[Fixed] Fixed G45 was falling through the ground

[Fixed] Fixed G17 was falling through the ground

[Fixed] Fixed MP443 was falling through the ground

[Fixed] Fixed APS was falling through the ground

[Fixed] Fixed SP81 was falling through the ground

[Fixed] Not being able to use NVG when aiming with glocks/m17/m18

[Fixed] Fixed 1PN93 PiP sights; fixes [#649](https://github.com/RHSMODS/statusquo/issues/649)

[Fixed] Fixed MS2K placement on helmets; fixes [#643](https://github.com/RHSMODS/statusquo/issues/643)

[Fixed] Inventory icon for A Pos blood patch was not working; fixes [#628](https://github.com/RHSMODS/statusquo/issues/628)

[Fixed] Removed default helmet cover from Kiver which should fix an issue where player would respawn with default cover even when they saved their loadout with different cover attached

[Fixed] Wrong name shown in some cases for VIP Strobe; fixes [#656](https://github.com/RHSMODS/statusquo/issues/656)

[Fixed] Fixed TSh-4 wrong weight

[Fixed] Fixed BallCap wrong weight

[Fixed] Fixed Shemagh wrong weight

[Fixed] Fixed Beanie wrong weight

[Fixed] Fixed K-17 causing Game crash

[Fixed] Not being able to attach strobes to the helmets

[Fixed] Fixed barrel texture on RPK-74 not working anymore.

[Fixed] Scripts compile for 1.1 and version bumped to 0.8


##### Deleted


[Removed] Disabled Environment probe in k-17 due poor optimization
