![Laclede's LAN ioQuake3 Dedicated Freeplay Server](https://raw.githubusercontent.com/LacledesLAN/gamesvr-ioquake3-freeplay/master/.misc/banner-quake3-freeplay.png "Laclede's LAN Quake3 Dedicated Freeplay Server")

This repository is maintained by [Laclede's LAN](https://lacledeslan.com). Its contents are heavily tailored and tweaked for use at our charity LAN-Parties. For third-parties we recommend using this repo only as a reference example and then building your own using [gamesvr-ioquake3](https://github.com/LacledesLAN/gamesvr-ioquake3) as the base image for your customized server.

## Linux Container

[![](https://images.microbadger.com/badges/version/lacledeslan/gamesvr-ioquake3-freeplay.svg)](https://microbadger.com/images/lacledeslan/gamesvr-ioquake3-freeplay "Get your own version badge on microbadger.com")
[![](https://images.microbadger.com/badges/image/lacledeslan/gamesvr-ioquake3-freeplay.svg)](https://microbadger.com/images/lacledeslan/gamesvr-ioquake3-freeplay "Get your own image badge on microbadger.com")

### Download

```shell
docker pull lacledeslan/gamesvr-ioquake3-freeplay;
```

### Run Self Tests

The image includes a test script that can be used to verify its contents. No changes or pull-requests will be accepted to this repository if any tests fail.

```shell
docker run -it --rm lacledeslan/gamesvr-ioquake3-freeplay ./ll-tests/gamesvr-ioquake3-freeplay.sh;
```

## Run simple interactive server

```shell
docker run -it --rm --net=host lacledeslan/gamesvr-ioquake3-freeplay /app/ioq3ded.x86_64 +exec server-ffa.cfg +exec playlists.cfg +vstr stock-dm-1 +set rconpassword "EXAMPLE"
```

## Getting Started with Game Servers in Docker

[Docker](https://docs.docker.com/) is an open-source project that bundles applications into lightweight, portable, self-sufficient containers. For a crash course on running Dockerized game servers check out [Using Docker for Game Servers](https://github.com/LacledesLAN/README.1ST/blob/master/GameServers/DockerAndGameServers.md). For tips, tricks, and recommended tools for working with Laclede's LAN Dockerized game server repos see the guide for [Working with our Game Server Repos](https://github.com/LacledesLAN/README.1ST/blob/master/GameServers/WorkingWithOurRepos.md). You can also browse all of our other Dockerized game servers: [Laclede's LAN Game Servers Directory](https://github.com/LacledesLAN/README.1ST/tree/master/GameServers).
