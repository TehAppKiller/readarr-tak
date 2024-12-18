# readarr-tak
[![readarr-tak](https://snapcraft.io/readarr-tak/badge.svg)](https://snapcraft.io/readarr-tak)
![snap arch](https://badgen.net/snapcraft/architecture/readarr-tak)
![snap size](https://badgen.net/snapcraft/size/readarr-tak/amd64/stable)

## Snap Description
Canonical Snap for Readarr\
https://snapcraft.io/readarr-tak

## Readarr Description
<img src="/icon.svg" width="100">
Readarr is an ebook and audiobook collection manager for Usenet and BitTorrent users.
It can monitor multiple RSS feeds for new books from your favorite authors 
and will grab, sort, and rename them. Note that only one type 
of a given book is supported. If you want both an audiobook and ebook 
of a given book you will need multiple instances.

See https://readarr.com for more details.

## Information

The web interface is accessible by default at http://localhost:8787

Readarr is currently in beta testing\
Service is restarted on any condition.

Post install commands required to access media folders and see resources :
```
sudo snap connect readarr-tak:removable-media
sudo snap connect readarr-tak:mount-observe
```

**!!! Files can only be written in a directory owned by 'root' !!!**\
**!!! Home base directory content is not readable !!!**

This is due to current behavior and restrictions of snaps by Canonical.\
Check common doc in FAQ if you want to setup data in /home directory.

## FAQ
See my common doc about [FAQ](https://github.com/TehAppKiller/Snapcraft-common-doc/tree/main#FAQ).

## Building
See my common doc about [building a snap](https://github.com/TehAppKiller/Snapcraft-common-doc/tree/main#Building).
## Versionning
See my common doc about [versionning](https://github.com/TehAppKiller/Snapcraft-common-doc/tree/main#Versionning).
