# NPC Animations 0.0.1 (Burning Water)
Animate your ROBLOX NPC for your game (in an easy way!)

0.0.1 (Last release!)
https://create.roblox.com/marketplace/asset/15028306221/NPC-Animator-Burning-Water

# Code
Put this code in your NPC model! Make sure the NPC has the `Animator` object in `Humanoid` to make it work.
And put the location of the module in "YOUR LOCATION" so to make it work. Enjoy!
```lua
-- // Variables // --

local anim = require(YOUR LOCATION)
local newanimation = anim.newAnimScript()
local animation = workspace.Animate

-- // Code // --

animation.Parent = script.Parent
animation.Enabled = true
```
