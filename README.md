# Euridice

*Euridice* [eu.riˈdi.tʃe/] is a bash script that takes a video URL from a medium supported by `youtube-dl` and outputs a PDF document consisting of the unique frames of that video.

Its name is taken from that of [Orpheus' wife](https://www.youtube.com/watch?v=_7Wo-3DtI34) in Greek mythology.
Her name is derived from the words *ευρύς*, "wide" and *δικη*, "justice”, and serves as a metaphor for the educational and ethical gap this script was designed to bridge.

## Requirements

* youtube-dl
* ffmpeg
* imagemagick
* rdfind
* not believing in intellectual property

## Usage

Simply pass as an argument a video URL [from any website supported by *youtube-dl*](https://ytdl-org.github.io/youtube-dl/supportedsites.html), like this:

```bash
./euridice https://www.youtube.com/watch?v=ft_G8bKieNc
```

The script also reads from **stdin**

## LICENSE
[GPLv3](https://www.gnu.org/licenses/gpl-3.0.html)
