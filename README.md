**Recycle** allows players to recycle crafted items to base resources.

## Permissions

* `recycle.use` -- Allows players to use the `/rec` chat command

## Commands

* `/rec` -- Open recycle box

## Configuration

* `box` - Change the box asset used to recycle
* `cooldownMinutes` - Duration between usages
* `refundRatio` - The percentage of original materials recycled (default: 50%)
* `NPCOnly` - Restrict recycle to using HumanNPC's
* `NPCIDs` - List of HumanNPC's that will recycle
* `recyclableTypes` - List of item categories which may be recycled
* `blacklist` - Specific items (shortname) that may not be recycled
* `allowSafeZone` - Allow recycling in safe zones (ZoneManager)

## For Developers

```csharp
bool IsRecycleBox(BaseNetworkable entity)
```