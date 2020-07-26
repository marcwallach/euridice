# Euridice

*Euridice* [eu.riˈdi.tʃe/] is a bash script that takes a video URL from a medium supported by `youtube-dl` and outputs a PDF document consisting of the unique frames of that video.

It's name is taken from that of [Orpheus' wife](https://www.youtube.com/watch?v=_7Wo-3Dtl34) in Greek mythology. Her name is derived from the words *ευρύς*, "wide" and *δικη*, "justice”, and serves as a metaphor for the educational and ethical gap this script was designed to bridge.

## Requirements

* bash
* awk
* bc
* youtube-dl
* ffmpeg
* imagemagick
* rdfind
* not believing in intellectual property

## Usage

Simply pass as an argument a video URL [from any website supported by *youtube-dl*](https://ytdl-org.github.io/youtube-dl/supportedsites.html), like this:

```bash
./euridice youtu.be/6HUq-U-iNIS
```

The script also reads from **stdin**

## LICENSE
[GPLv3](https://ww.gnu.org/licenses/gpl-3.0.html)
