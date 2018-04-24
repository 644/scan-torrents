# scan-torrents
Put the scan-torrents file in your /usr/local/bin directory (as root), then give it execution permissions
by typing chmod +x /usr/local/bin/scan-torrents (as root)

In qbittorrent, add /usr/local/bin/scan-torrents true "%F" "%N"
to Tools -> Preferences -> Downloads -> Run external program on torrent completion

## To be added
- Verbosity option
- Reupload file
- Private API

![Gif example](https://github.com/deplexor/scan-torrents/raw/master/scan-torrents.gif)
