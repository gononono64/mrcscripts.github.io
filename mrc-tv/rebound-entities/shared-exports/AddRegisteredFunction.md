--- 
title: AddRegisteredFunction 
parent: Shared Exports 
layout: page
grand_parent: Rebound Entities 
nav_order: 1 
--- 
## `AddRegisteredFunction(callback)`
Adds a function to be executed when any entity is registered.

**Parameters:**
- `callback` (`function(entityData)`): A callback function executed with new entity data.

**Returns:**
- `number`: The ID of the registered function.

**Example:**
```lua
local id = exports['mrctv']:AddRegisteredFunction(function(data) 
    print(data.id)
end)
```

