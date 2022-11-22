# Open source stuff
## Scroll down if you wan't to see plugins!

# @knit
COMING SOON!
# Administration Panel
COMING SOON!

# Plugins

# BetterRequire
How to use:
```lua
-- // Grab the require script.
local betterreq = require(game:GetService('ReplicatedStorage')['BetterRequire'])
-- // Require a module script without its directory.
local modscript = betterreq("Script") -- WARNING: You need the second argument where should it scan in.
-- ↑ You don't need to put a string, you can also put the modulescript instance as the #1 argument.
-- // Access
modscript["HelloWorld"] = function() print("Hello World!") end
modscript.HelloWorld();
```
Example:
```lua
local betterreq = require(game:GetService('ReplicatedStorage')['BetterRequire'])
betterreq("Script", game.ReplicatedStorage) -- Modulescript Name (?string), Where to scan in (?instance/nil).
-- Leaving the #2nd arg empty/"nil" will make the betterrequire module scan everywhere in the game folder for the module.
-- Giving the #2nd arg an instance will scan anywhere in the selected instance for the module.
-- You can also do this, to find a modulescript everywhere: betterreq('Script');
-- WARNING: IF YOU PUT THE 2ND ARG EMPTY THEN IT MIGHT RUIN PERFOMANCE UNTIL THE MODULE IS FOUND!
```
DOWNLOAD:
[better-req.txt](https://github.com/ROBLOXSUKSITBANS/ROBLOXSUKSITBANS.github.io/files/10069644/better-req.txt)
