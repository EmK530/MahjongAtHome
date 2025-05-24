# MahjongAtHome
Recreation of the main server for Mahjong Fight Girl.<br>
This will be open-sourced when CPU games are functional.

## How to test
Download the [testing plugin](https://github.com/EmK530/MahjongAtHome/releases/tag/asphyxia-only) for Asphyxia CORE.<br>
This does not manage the game but rather point you to my testing server.<br>
<b>The testing server is made for 2024100800, make sure you are running it!</b>

## Current status
- Boots to main menu, data saves but game does not acknowledge it, could be from lack of playing a full game.<br>
- Only CPU games are allowed at the moment, gets stuck after dealing the hands.<br>
- Gacha button is greyed out, fixing it is currently not prioritized but rather making a CPU game work.

## Testing server changelog
To view preview videos, ask me for permission.

#### [2025-05-24](https://youtu.be/FsT5J7rpLgU)
New config system, CPUs no longer use gacha characters.<br>
Added stub for TsumoChoices letting the player discard tiles but causes a network malfunction due to lack of `/gpost` support.

#### 2025-05-22
Added a proper handler for game commands, the server now sends a valid KyokuStart to the player.<br>
Added support for command "Tsumo", letting the first player draw a tile which makes the hands show up.<br>
Leaving at this stage is now possible, but will cause a network malfunction.

#### [2025-05-15](https://youtu.be/oWbFGxj97IM)
Initial release.
