# Docker Storage

## File System

Docker stores its files in /var/lib/docker path.

## Layered Architecture

![docker-storage](../images/docker-storage-1.jpg "docker-storage")

![docker-storage](../images/docker-storage-2.jpg "docker-storage")

## Volumes

Volumes are used to maintain persistence data by saving the data in host and map the data to the container.

> docker volume create data_volume

it create a folder data_volume under volumes folder in /var/lib/docker

> docker run -v data_volume:/var/lib/mysql mysql

![docker-storage](../images/docker-storage-3.jpg "docker-storage")

## Storage drivers

* AUFS
* ZFS
* BTRFS
* Device Mapper
* Overlay
* Overlay2

