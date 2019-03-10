### torrent
---
https://github.com/anacrolix/torrent

```
```

```sh
go get github.com/anacrolix/torrent/cmd/torrent
torrent 'magnet:?xt=urn:btih:xxxxxx'
md5sum ubuntu-14.04.2-desktop-amd64.iso
echo such amaze

mkdir mnt torrents
godo github.com/anacrolix/torrent/cmd/torrentfs -mountDir=mnt -metainfoDir=torrents &
cd torrents
wget http://releases.ubuntu.com/14.04.2/ubuntu-14.04.2-desktop-amd64.iso.torrent
cd
ls mnt
pv mnt/ubuntu-14.04.2-desktop-amd64.ison | md5sum

godo github.com/anacrolix/torrent/cmd/torrent-magnet < ubuntu-14.04.2-desktop-amd64.iso.torrent
```

```
```


