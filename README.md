### **No longer maintained due to conflicts with the "community". I also won't give support for anyone trying to use this.**

Goodbye Beatrun.

# Beatrun

### **🚨 Important Notice**

The **only** official source for this version of Beatrun is this repository. Any uploads made elsewhere are unsupported. You're on your own if you use them.

## About

A parkour gamemode for Garry's Mod. Used to be closed source and distributed with DLL files, now *source-available*.

Want an open-source version? Go to [`JonnyBro/beatrun`](https://github.com/jonnybro/beatrun) instead.

> [!CAUTION]
> **This gamemode has additional optional modules for functionality!** Modules are required for Discord Rich Presence and Steam Presence to work due to limitations.
>
> Removing them ***will not*** affect gameplay. They are located in `lua/bin`. If you're afraid if binary executables, don't install them.

## Installation

1. **[Download this repository](https://github.com/LostTrackpad/beatrun/archive/refs/heads/master.zip).**
2. Delete the `beatrun` folder in *(your game folder)*`/garrysmod/addons`, if it exists.
3. Extract `beatrun-main/beatrun` into *(your game folder)*`/garrysmod/addons`.
4. (Optional) For Discord and Steam Presence, extract `beatrun-main/lua` to *(your game folder)*`/garrysmod`.
5. Start the game. Select the `Beatrun` gamemode in the bottom-right corner.

---

## Features and Updates

### New Features

- **Custom course database support.** Course database software is available **[here](https://git.jonnybro.ru/jonny_bro/beatrun-courses-server)**.
- **New gamemode** Deathmatch.
- Optional more accurate kickglitch implementation similar to *[Mirror's Edge](https://www.youtube.com/watch?v=zK5y3NBUStc)*.
- In-game configuration menu in the Tools menu under *Beatrun*.
- Localization support, available in **7 languages**.
- Any prop can be spawned and will save in your course.
- Various new abilities:
  - **Roll after ziplines:** Press `+duck` (*Control/CTRL* by default).
  - **Dismount ladders:** Press `+duck` (*Control/CTRL* by default).
  - **Remove ziplines created with Zipline Gun:** Press `+attack2` (*Right Mouse Button* by default).
  - **Next checkpoint arrow** for easier navigation.
- New server and client configuration variables:
  - Server:
    - `Beatrun_AllowOverdriveInMultiplayer`: Allows Overdrive in multiplayer.
    - `Beatrun_AllowPropSpawn`: Lets players spawn props and weapons without admin rights.
    - `Beatrun_HealthRegen`: Toggles health regeneration.
  - Client:
    - `Beatrun_HUDTextColor`, `Beatrun_HUDCornerColor`, `Beatrun_HUDFloatingXPColor`: Customize HUD colors.
    - `Beatrun_DisableGrapple`: Toggle the grapple ability.
    - `Beatrun_OldKickGlitch`: Switch between old and new Kick Glitch.
    - `Beatrun_QuickturnHandsOnly`: Restrict QuickTurn to the Runner Hands weapon.
- Other improvements:
  - Small camera punch effect when diving.
  - Your Steam account ID is not displayed on screen anymore.
  - Fixed playermodels showing as `ERROR` in first person.
  - Improved leaderboard sorting in gamemodes.
  - Fixed crashes and issues with Data Theft gamemode.
  - Enabled jumping while walking.
  - Grapples now follow moving entities and are visible to other players.

## Credits

- **[All contributors](https://github.com/JonnyBro/beatrun/graphs/contributors)**.
- **[Beatrun Reanimated Project](https://github.com/JonnyBro/beatrun-anims), more specifically [MTB](https://www.youtube.com/@MTB396)** for optional animations included.
- [EarthyKiller127/datae](https://www.youtube.com/channel/UCiFqPwGo4x0J65xafIaECDQ) - Original creator of Beatrun.
- [relaxtakenotes](https://github.com/relaxtakenotes) for making this project possible.
- [Fluffy Servers](https://github.com/fluffy-servers/gmod-discord-rpc) for Discord Rich Presence module.
- [YuRaNnNzZZ](https://github.com/YuRaNnNzZZ/gmcl_steamrichpresencer) for Steam Presence module.
- beatrun.ru "community" for being hostile and making me abandon Beatrun altogether
