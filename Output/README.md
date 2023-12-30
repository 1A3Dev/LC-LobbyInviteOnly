# LobbyInviteOnly

## Information

This mod adds a new button when hosting a lobby which allows you to set it as invite-only. It was designed for people who want to play alone or with a specific group of friends without uninvited people being able to join.

This is also useful if you or someone in your lobby has their steam "game details" privacy setting as public as that allows anyone to join a friends-only lobby by clicking the join button on the person's public steam profile.

Note: Only the lobby host needs the mod installed (the mod isn't required to join an invite-only lobby).

## Support For Other Mods (For Mod Creators)

If the host of a lobby is using this mod you will have access to the following information:

Invite Only: `GameNetworkManager.Instance.currentLobby.GetData("inviteOnly") == "true"`

Lobby Type (Private/Friends Only/Public): `GameNetworkManager.Instance.currentLobby.GetData("lobbyType")`

## Changelog

### 1.0.3

- Added invite only state & lobby type to the lobby data so other mods can easily check whether the currently lobby is invite only e.g. discord rich presence mods not showing the join button for invite only lobbies.

### 1.0.2

- Added a bit of extra detail to the README.md
- Updated the icon

### 1.0.0

- Initial Release
