# Palworld server saves

Snapshots of Nistre's Palworld dedicated server world. Download them from [Releases](../../releases).

## What's in each zip
- `SaveGames/0/<world id>/`: `Level.sav` (world, bases, Pals), `LevelMeta.sav`, `Players/*.sav` (every character)
- `PalWorldSettings.ini`: the server settings at the time of the snapshot (passwords removed)

## Using a save
**Dedicated server:** stop the server, copy the `<world id>` folder into `Pal/Saved/SaveGames/0/`, and set
`DedicatedServerName=<world id>` in `Pal/Saved/Config/WindowsServer/GameUserSettings.ini`.

**Singleplayer / co-op:** copy the `<world id>` folder into
`%LOCALAPPDATA%\Pal\Saved\SaveGames\<your Steam ID>\`. Character mapping from a server save may need a converter tool.
