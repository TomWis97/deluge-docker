# Deluge on Docker
This repository contains the source for two Docker images for Deluge: an image for deluged and an image for the webinterface.

## deluged container
This image is available as tomwis97/deluged on the Docker hub.

Ports:
- `56646`: Connection to control Deluge

Volumes:
- `~/.config/deluge` for deluged configuration.
- `~/Downloads` for Downloaded torrents

## deluge-web
This image is available as tomwis97/deluge-web on the Docker hub.

Ports:
- `8112`: For access to the webinterface

Volumes:
- `~/.config/deluge`
