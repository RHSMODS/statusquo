# Throwable and Placeable Items

## Purpose

This guide shows how to make an item that the player can throw like a grenade and place on a surface like an explosive charge. The RHS strobes use this system. For the player side, see [Strobe Devices](../general-systems/strobe-devices.md).

## Prerequisites

* RHS: Status Quo as a dependency of your mod.
* An item model with collision geometry.

## Procedure

1. Make a prefab that inherits from the vanilla `{A9EF01A7A6FE60CD}Prefabs/Weapons/Core/Throw_Base.et`.
2. Add `SCR_PlaceableInventoryItemComponent` as the inventory item component.
3. Add `RHS_ThrowablePlaceableItemComponent` and set its attributes (see the reference below).
4. Set up the throw:
   1. In `WeaponComponent`, set **isThrowable** to 1 and **WeaponSlotType** to `grenade`.
   2. Add a `GrenadeMoveComponent` without a trigger.
   3. Add a `RigidBody`. Use the item weight as the mass.
5. Save the prefab and test it in play mode.

The player throws the item with the left mouse button. To place it, the player holds the right mouse button (input action `RHS_PlaceModeHold`) and pushes the left mouse button.

{% hint style="info" %}
Use the RHS strobe prefabs as a template. They also keep the velcro attachment of the original items (`BaseLoadoutClothComponent` and the RHS attach, detach and replace actions).
{% endhint %}

## Example

```
RHS_ThrowablePlaceableItemComponent "{...}" {
 m_bRequireAimToPlace 1
 m_bAlignForwardToSurfaceNormal 1
 m_bPickableAfterThrow 1
 m_bSkipPlacementAnimation 1
}
```

## Reference

`RHS_ThrowablePlaceableItemComponent`:

| Attribute | Default | Description |
| --- | --- | --- |
| `m_bRequireAimToPlace` | 1 | Show the placement preview only while the player holds the right mouse button. Otherwise the item is thrown. |
| `m_bAlignForwardToSurfaceNormal` | 1 | Place the item with its front (local Z axis) along the surface normal instead of its top (local Y axis). |
| `m_bPickableAfterThrow` | 1 | When a thrown item stops, the server replaces it with a new item of the same prefab, so the player can pick it up. |
| `m_bSkipPlacementAnimation` | 1 | Place the item without an animation. Grenade animation sets have no placing animation. |

## Prefabs

| Prefab | Description |
| --- | --- |
| `{5F7EF7FEBC39B874}Prefabs/Items/Equipment/Nightvision/HelstarStrobe/Helstar.et` | HEL-STAR 6 strobe, light faces local +Z |
| `{643AB339663E92F7}Prefabs/Items/Equipment/Nightvision/MS2000/Marker_MS2000.et` | MS2000 strobe |
| `{8F54EE49D3317266}Prefabs/Items/Equipment/Nightvision/VipLight/VipLight.et` | VIP strobe |
