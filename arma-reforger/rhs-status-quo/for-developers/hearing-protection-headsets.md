# Hearing Protection Headsets

## Purpose

This guide shows how to make a headset or a helmet give active hearing protection. For the player side, see [Hearing Protection](../general-systems/hearing-protection.md).

## Prerequisites

* RHS: Status Quo as a dependency of your mod.
* A headgear prefab: a headset that is worn on its own, a headset that attaches to the **Headset** slot of a helmet, or a helmet with an integrated headset.

## Procedure

1. Open the headgear prefab in Workbench.
2. Add the component `RHS_HearingProtectionComponent`.
3. Change the attributes if your headset must sound different (see the reference below). The defaults suit a typical electronic headset.
4. To let the player set the level from the RHS radial menu, add one `RHS_HearingProtectionSetLevelAction` per level to the `ActionsManagerComponent`:
   1. Set **m\_iLevel** (0 = electronics off).
   2. Add `default` to **ParentContextList**.
   3. Set **m\_bIgnoreInRadial** to 0.
5. Save the prefab.

The system finds the headset when it is worn on the head, attached to the worn headgear, or is the worn headgear itself.

{% hint style="warning" %}
A headset in a slot of a hat or helmet works only when the headgear has a storage component for its slots (for example `RHS_ClothNodeStorageComponent`). Without it the headset does not spawn and gives no protection.
{% endhint %}

## Example

A helmet with an integrated headset and the level action for level 1:

```
RHS_HearingProtectionComponent "{6E5001A0C00000FF}" {
}
ActionsManagerComponent "{5112706CD4157AC9}" {
 additionalActions {
  RHS_HearingProtectionSetLevelAction "{6E5001A0C0000001}" {
   ParentContextList {
    "default"
   }
   UIInfo UIInfo "{6E5001A0C0000011}" {
    Name "#RHS-HearingProtection_SetLevel"
   }
   "Sort Priority" 11
   m_bIgnoreInRadial 0
   m_iLevel 1
  }
 }
}
```

Use new GUIDs for your own components and actions.

## Reference

`RHS_HearingProtectionComponent`, category **Hearing Protection**:

| Attribute | Default | Description |
| --- | --- | --- |
| `m_iLevelCount` | 4 | Number of amplification levels. |
| `m_iDefaultLevel` | 2 | Level when the headset is worn for the first time. 0 = off. |
| `m_fPassiveVolume` | 0.3 | Volume of the world when the electronics are off. |
| `m_fMinLevelVolume` | 0.45 | Volume of the world at level 1. |
| `m_fMaxLevelVolume` | 1 | Volume of the world at the highest level. |
| `m_fLimiterThresholdDb` | 82 | Sound level in dB above which the limiter reacts. |
| `m_fLimiterFloor` | 0.15 | Lowest volume the limiter can go to. |
| `m_fLimiterRelease` | 0.35 | Time in seconds for the limiter to release. |
| `m_fDynamicRange` | -1.5 | Game dynamic range while the electronics are on. |

## Prefabs

| Prefab | Description |
| --- | --- |
| `{1F49EEF2B889F0C1}Prefabs/Characters/HeadGear/Headphones_Peltor/Headphones_Peltor_base.et` | Headset worn on its own or in a helmet slot |
| `{FE551345A4A69E3D}Prefabs/Characters/HeadGear/Hat_USMC_Boonie/Hat_USMC_Boonie_Comtac.et` | Hat with a headset slot and storage component |
| `{C50D23658C5A6F86}Prefabs/Characters/HeadGear/Helmet_ECH/Helmet_ECH_hc_v_r_p.et` | Helmet with an integrated headset |
