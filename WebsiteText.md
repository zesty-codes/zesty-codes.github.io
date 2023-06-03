WatchCheat: Unlimited protection (RubyAnticheat Reborn i guess)
This anticheat is not yet released.
FEATURES:
Custom API shared with every scripts (FREE, use _G)

Premium (PAID) (Buy with: paysafecard, robux. If it will get accepted, make a ticket in the WatchCheat discord server, and then say that you bought the gamepass license, include your name and userid)

Speed Checks (FREE)

Teleport Checks (FREE)

Godmode Checks (FREE)

Future Client AnticheatBypass Checks (FREE)

Client Modification Checks (FREE)

Tryhard Protection (PAID FEATURE)

Anti Flight (PAID FEATURE)

Anti Crash (PAID FEATURE)

Anti Chat Bypass (PAID FEATURE) (Supports: Vadrifts Bypasser)

Detection Bypass Checks (Supported: Future Client, Zestyhub)

Ban On Detection (PAID FEATURE, BETA)

After ban on detection isn't on beta, it will be free.

To use bans on detection, you must have datastores enabled.

API Features:

Accessing the API:
```lua
local CheatWatchAPI = _G.CheatWatchAPI
```

Teleporting the player without triggering the anticheat:
```lua
-- _G.CheatWatchAPI.Teleport(player: Player?, CFrame: CFrame? | Vector3?)
_G.CheatWatchAPI.Teleport(game.Players:FindFirstChild("Target"), CFrame.new(25, 63, 24))
-- and:
_G.CheatWatchAPI.Teleport(game.Players:FindFirstChild("Target"), Vector3.new(25, 63, 24))
```

