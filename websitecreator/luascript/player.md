# Player

A Player object is a client that is currently connected. This object is similar to ROBLOX's Player Object except more limited,&#x20;

```lua
-- Player Object
local Player = {
	["UserId"] = number,
	["Username"] =  string,
	["DisplayName"] = string,
	["AccountAge"] = number,
	["Memebership"] =  enum.MembershipType,
	["HasVerifiedBadge"] = boolean,
	['Functions'] = {
		["GetRankInGroup"] = function(groupID: number): number
		["GetFriendsOnline"] = function(maxFriends: number): {any}
		["GetRoleInGroup"] = function(groupID: number): string
		["IsFriendsWith"] = function(userID: number): boolean
		["IsInGroup"] = function(groupID: number): boolean
		["GetNetworkPing"] = function(): number
	}
}

```

Example Code

```lua
print("Your name is " .. Player.Username)

print("Your Roblox Account is about " .. Player.AccountAge .. " days old")

print("Are you inside NovarietyGames Roblox Group? " .. Player.Functions.IsInGroup(11488629))
```
