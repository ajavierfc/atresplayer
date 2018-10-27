This script is coded to play live broadcast content from atresplayer.com

Require requests

# Usage

_Choose channel and play (check the player path in the source)_

./get.py

_Get link channel_

./get.py <ANTENA_3|LA_SEXTA|NEOX|NOVA|MEGA|ATRESERIESe>

__Examples__

Linux: ``mpv `./get.py NEOX` ``

Windows (Powershell): `& 'C:\Program Files\VideoLAN\VLC\vlc.exe' (python .\get.py NEOX)`