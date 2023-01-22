# Container Images Mirror

Images are hosted on Github Container Registry [here](https://github.com/onedr0p?ecosystem=container&tab=packages).

## Purpose

This is to get around Docker Hub rate-limiting (100 pulls / 6 hours, or authenticated 200 pulls / 6 hours). It is considered a stop-gap until the maintainers of the applications below support a different Container Registry.

## Supported images

When upstream maintainers add support for an additional registry, the images here will be purged after awhile.

| Name                                                                                            | Upstream Issue                                                                                                                                                                                   |
|-------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [node-red](https://github.com/node-red/node-red)                                                | [![GitHub issue status](https://img.shields.io/github/issues/detail/state/node-red/node-red/3107)](https://github.com/node-red/node-red/issues/3107)                                             |
| [prometheus-qbittorrent-exporter](https://github.com/esanchezm/prometheus-qbittorrent-exporter) | [![GitHub issue status](https://img.shields.io/github/issues/detail/state/esanchezm/prometheus-qbittorrent-exporter/12)](https://github.com/esanchezm/prometheus-qbittorrent-exporter/issues/12) |
| [grafana](https://github.com/grafana/grafana)                                                   | [![GitHub issue status](https://img.shields.io/github/issues/detail/state/grafana/grafana/27677)](https://github.com/grafana/grafana/issues/27677)                                               |
| [loki](https://github.com/grafana/loki)                                                         | [![GitHub issue status](https://img.shields.io/github/issues/detail/state/grafana/loki/4143)](https://github.com/grafana/loki/issues/4143)                                                       |
| [reloader](https://github.com/stakater/Reloader)                                                | [![GitHub issue status](https://img.shields.io/github/issues/detail/state/stakater/Reloader/255)](https://github.com/stakater/Reloader/issues/255)                                               |

## Docker OSS Program

Certain containers may not be rate limited if they are in Docker Hub's OSS Program. Below is a list of applications I have discovered to be part of this program.

- bitnami/*
- intel/intel-deviceplugin-operator
- intel/intel-gpu-plugin
- nodered/node-red
- rook/ceph
