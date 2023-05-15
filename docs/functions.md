# GetActors
> <a>GetActors()</a> returns all actor objects in a json format.
- <strong>Arguments:</strong> None.
- <strong>Return:</strong> Json string.
```json
{ 
    "101": {"id": 101, "model_id": 60079, "animation_id": 14, "isOre": "true", "position": [100, 200, 300], "name": "Example123"}, 
    "102": {"id": 102, "model_id": 60049, "animation_id": 11, "isOre": "false", "position": [200, 400, 100], "name": "Random321"},
    ...
}
```
# GetLocalActor
> <a>GetLocalActor()</a> returns local actor object in a json format.
- <strong>Arguments:</strong> None.
- <strong>Return:</strong> Json string.
```json
{"id": 101, "model_id": 60079, "animation_id": 14, "isOre": "true", "position": [100, 200, 300], "name": "Example123"}
```

# SetIgnoreCollisions
> <a>SetIgnoreCollisions(int)</a> sets value for local player collisions. If set 1 = can walk through objects, if set 0 = can't walk through objects. Aka. wallhack.
- <strong>Arguments:</strong> Between 0 and 1.
- <strong>Return:</strong> None.

# ClickObject
> <a>ClickObject(int)</a> clicks on object, this is similar to double click on Mining Node or Monster. You give 'id' has argument, you can get this from Actor json.
- <strong>Arguments:</strong> Anything higher then 100.
- <strong>Return:</strong> None.

# GetPMCount
> <a>GetPMCount()</a> returns total received pm count as integer.
- <strong>Arguments:</strong> None.
- <strong>Return:</strong> Integer [0, 4294967295].

# UseItem_BySlot
> <a>UseItem_BySlot(int)</a> uses item from inventory, similar to double click on item from inventory. You give slot index as argument, first index: 1.
- <strong>Arguments:</strong> Anything higher then 0.
- <strong>Return:</strong> None.

# GetItemID_BySlot
> <a>GetItemID_BySlot(int)</a> returns item id of item from inventory slot. You give slot index as argument, first index: 1.
- ItemID's similar to: https://metin2cms.cf/items/
- <strong>Arguments:</strong> Integer [0, 4294967295].
- <strong>Return:</strong> Integer [0, 4294967295].