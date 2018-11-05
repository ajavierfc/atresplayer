Discontinued as moved to https://github.com/ajavierfc/plugin.video.simpleaddon/tree/master/lib

This script is coded to play live broadcast content from atresplayer.com

Require requests

# Usage

_Choose channel and play (check the player path in the source)_

`python get.py`

_Get channel stream link_

`python get.py <ANTENA_3|LA_SEXTA|NEOX|NOVA|MEGA|ATRESERIES>`

_Player_

Default player command is `mpv`, under windows you may want to use vlc, so set the player command as `"C:\\Program Files\\VideoLAN\\VLC\\vlc.exe"`

__Examples__

Linux: ``mpv `python get.py NEOX` ``

Windows (Powershell): `& 'C:\Program Files\VideoLAN\VLC\vlc.exe' (python get.py NEOX)`

__Notes__

* outside from spain probably wont work as is, due to geo-lock

