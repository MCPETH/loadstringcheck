# loadstringcheck
Roblox Game Map Loader with Loadstring Check: a simple Lua script designed for Roblox games that require specific map-related functionality. The script utilizes loadstring in conjunction with a map check based on the game's PlaceId. It allows users to dynamically load external Lua scripts tailored for different game maps.

## Example Usage :
```lua
if game.PlaceId == #paste id here then
    loadstring(game:HttpGet("example.com"))()
elseif game.PlaceId == #paste id here then
    loadstring(game:HttpGet("example.com"))()
elseif game.PlaceId == #paste id here then
    loadstring(game:HttpGet("example.com"))()
else 
    game.Players.LocalPlayer:Kick("Games Not Supports")
end
```
