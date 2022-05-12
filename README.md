## General Purpose 2D Collision Detection System

Documentation and examples here: http://hc.readthedocs.org/

### Additional features

- Capsule collider

Useage:
```lua
local shapes = require 'HC.shapes'
local cap = shapes.CapsuleShape(x, y, radius, length)

-- or

local world = HC.new(cellSize)
local cap = world:capsule(x, y, radius, length)

```

### Differences

- Removed shapes no longer have their tranformation functions obliterated for no reason, so they can still be used and re-registered later.
