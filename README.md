## Docker stack

![](https://i.imgur.com/gvPreHt.png)

## HDD structure

```bash
$ tree $HDD_PATH -d -L 2

2tb
├── bazarr
│   └── config
├── jackett
│   └── config
├── plex
│   ├── config
│   ├── movies
│   └── tv
├── radarr
│   └── config
├── rutorrent
│   ├── config
│   └── downloads
├── sonarr
│   └── config
└── transmission
    ├── config
    ├── downloads
    └── watch

19 directories
```

## Setup

1. Replace `HDD_PATH` with the path of your mass storage drive
2. Run `docker-compose up -d`

## Teardown

```bash
docker-compose down
```

## Docker images

* https://hub.docker.com/r/linuxserver/plex
* https://hub.docker.com/r/linuxserver/sonarr
* https://hub.docker.com/r/linuxserver/rutorrent
* https://hub.docker.com/r/linuxserver/transmission
* https://hub.docker.com/r/linuxserver/jackett
* https://hub.docker.com/r/linuxserver/bazarr
* https://hub.docker.com/r/linuxserver/radarr

## Docs

* https://www.techrepublic.com/article/how-to-properly-automount-a-drive-in-ubuntu-linux/
