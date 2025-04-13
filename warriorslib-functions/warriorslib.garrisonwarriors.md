# WarriorsLib.GarrisonWarriors

## `WarriorsLib.GarrisonWarriors(buldingid, player)`

Garrison a building. This makes a military building to search nearby units and when found command them to enter the specified building to completely occupy all spots in the building.

#### return value

* **Since Version 1.5.0**: success \[0, 1]
* Before: none

```lua
WarriorsLib.GarrisonWarriors(Buildings.GetFirstBuilding(1, Buildings.GUARDTOWERSMALL),1)
```
