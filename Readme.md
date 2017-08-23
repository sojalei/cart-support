fork nheir/teeworlds with new features for new gamemode
## Settings

|Command |  Description | Default|
| ------ | ------------ | ------ |
|`sv_bot_slots`|  Number of slots to reserve for bots | 2 |
|`sv_bot_skin`| Bot skin | default |
|`sv_bot_allow_hook`| Bots are allowed to hook | 1 |
|`sv_bot_allow_move`| Bots are allowed to move | 1 |
|`sv_bot_allow_fire`| Bots are allowed to fire | 1 |
|`sv_bot_draw_target`| Show bot target * | 0 |
|`sv_botengine_draw_graph`| Draw graph * | 0 |

\* This settings are more suited for debuging


## autoexec
For normal games you have to write this

*sv_gametype ctf|
*sv_bot_allow_fire 0|
