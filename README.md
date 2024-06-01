# Cradle Song Teaser (PS Vita port)
A Cradle Song Teaser port for Playstation Vita console leveraging [Ren'Py Vita](https://github.com/SonicMastr/renpy-vita) by [SonicMastr](https://github.com/SonicMastr) which in turn is a port of [Ren'Py engine](https://www.renpy.org). The game itself is a short visual novel made back in 2011 by [Dischan](https://dischan.co). If you want more stats and info you can refer to [its entry](https://vndb.org/v7568) on VNDB. 

## Requirements
* Modded PS Vita (very easy to search for loading CFW online)
* [VitaShell](https://github.com/TheOfficialFloW/VitaShell) or any other method of navigating Vita's internal memory

## Installation 
### First Time
1. Go into **Releases** section of this repository and download the _.vpk_ file
2. Transfer the file into your Vita (ie. under _ux0:VPK_ or any other folder you created) and install

The installation can take a up to 1 min 30 secs and so does the first startup of the game. Subsequent startups go from zero to operational in around 53-57 sec. All of this is expected behaviour so far.

### Updating to New Release
1. Go into **Releases** section of this depository and download the latest _**data.rpa**_ file
2. Go into **_ux0:app/CDRSLV098/game_** on your Vita and replace existing _**data.rpa**_ with the downloaded one

## Current Issues
* Occassional short lags when Ren'Py is loading new assests. Shouldn't be too much of a bother but it is still noticeable
* Lack of video support. You most likely won't notice this while playing but there are 2 very short video files - one near the last section of the game and the other being credit roll at the very end. Current state of Ren'Py Vita does not allow for video playback but I will proceed with further attempts at fixing that in the future (hopefully)

## Changelog
### Initial Release - v00.98
* Edited script to remove a code compatability error preventing the game from booting up under Ren'Py Vita
* Edited the resolution to reflect Vita's 960x544 and rescaled/converted every image asset to adjust for the change. That reduced file size by about 25% however only slightly improved overall responsivness
* Removed ability to change resolution and re-adjusted hardcoded positioning of assests on the screen


