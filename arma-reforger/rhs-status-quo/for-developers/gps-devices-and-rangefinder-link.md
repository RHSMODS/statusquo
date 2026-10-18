# GPS Devices and Rangefinder Link

## Purpose

This guide shows how to connect your own rangefinder to the RHS GPS receivers (DAGR and Orion), and how to change the images in the GPS image viewer. For the player side, see [Navigation and Positioning](../general-systems/navigation-and-positioning.md).

## Prerequisites

* RHS: Status Quo as a dependency of your mod.
* A rangefinder prefab that uses `RHS_SCR_2DLRFComponent` or a component that inherits from it (for example `RHS_SCR_2DVector21Component`, `RHS_SCR_2DPDU4Component`).

## Procedure

### Link a rangefinder to the GPS devices

1. Open your rangefinder prefab in Workbench.
2. Select the rangefinder component (`RHS_SCR_2DLRFComponent` or a child class).
3. In the **Ranging** category, set **m\_sGPSLinkName** to the name that the GPS devices show, for example `PDU-4`.
4. Save the prefab.

The GPS devices now list the rangefinder in their link menu when the same character carries both items. After each range measurement, the rangefinder sends the target to the linked GPS device.

{% hint style="info" %}
An empty **m\_sGPSLinkName** means that the rangefinder cannot be linked.
{% endhint %}

### Send the target from your own component

The base component sends the target after its own range measurement (`OnRange`). If your component measures the range in its own code, call `SendTargetToGPS()` after the measurement.

### Change the images of a GPS device

1. Open the GPS device prefab (for example `DAGR.et` or `Orion.et`), or a prefab that inherits from it.
2. Select `RHS_GPSGadgetComponent`.
3. In the **GPS** category, add an entry to **m\_aImages**.
4. Set **m\_sName** (16 characters maximum) and **m\_sTexture** (an `.edds` texture).

## Example

A rangefinder that can be linked:

```
RHS_SCR_2DPDU4Component "{5D0CB09DD1352E4A}" {
 m_sGPSLinkName "PDU-4"
}
```

A custom rangefinder component that sends the target after its own measurement:

```c
class MY_RangefinderComponent : RHS_SCR_2DLRFComponent
{
	protected void OnMyMeasurement()
	{
		// ... measure the range ...
		SendTargetToGPS();
	}
}
```

The images of the Orion:

```
RHS_GPSGadgetComponent "{629EB9FEB91C438C}" {
 m_aImages {
  RHS_GPSImage "{6F2A000000000001}" {
   m_sName "EVERON"
   m_sTexture "{07FC05544D9D40AF}UI/Textures/GPSMaps/EveronMapRastr.edds"
  }
 }
}
```

## Reference

| Component | Attribute | Description |
| --- | --- | --- |
| `RHS_SCR_2DLRFComponent` | `m_sGPSLinkName` | Name shown by the GPS devices. Empty = no link. |
| `RHS_SCR_2DLRFComponent` | `m_fMaximumRange` | Maximum lasing distance in meters (default 5000). |
| `RHS_GPSGadgetComponent` | `m_aImages` | Images in the image viewer of the device (`RHS_GPSImage`: `m_sName`, `m_sTexture`). |

The target goes only to a GPS device that is linked to the rangefinder and carried by the same character.

## Prefabs

| Prefab | Description |
| --- | --- |
| `{B1798B0F1258B765}Prefabs/Items/Equipment/Navigation/DAGR/DAGR.et` | DAGR GPS receiver |
| `{A55A815F28739FEC}Prefabs/Items/Equipment/Navigation/Orion/Orion.et` | Orion GPS receiver |
| `{03810BEF182ADA0B}Prefabs/Items/Equipment/Binoculars/Rangefinder_Vector21.et` | Vector 21, link name "Vector 21" |
