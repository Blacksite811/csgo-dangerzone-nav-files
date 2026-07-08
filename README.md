# CS:GO Danger Zone Nav Meshes

Ready-to-use clean `.nav` files (navigation meshes) for bots on **Ember** and **Vineyard** maps. Valve never released official navigation files for these maps, and generating them manually often crashes the game.

## Included files:
* `dz_ember.nav`
* `dz_vineyard.nav`

## Installation:
1. Download `dz_ember.nav` and `dz_vineyard.nav` from this repository.
2. Copy the files to your CS:GO maps folder:
   `...SteamLibrary\steamapps\common\csgo legacy\csgo\maps\`
3. Add bots using: mp_do_warmup_offine 1; mp_warmup_start; game_mode 0; game_type 6; bot_quota 18; bot_difficulty 5; bot_autodifficulty_threshold_high 20; sv_infinite_ammo 2; mp_restartgame 1.
