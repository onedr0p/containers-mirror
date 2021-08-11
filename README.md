# Container Images Mirror 

Images are hosted on Github Container Registry [here](https://github.com/orgs/k8s-at-home/packages?ecosystem=container&visibility=public).

## Purpose

This is to get around Docker Hub rate-limiting (100 pulls / 6 hours, 200 pulls / 6 hours). It is considered a stop-gap until the maintainers of the applications below support a different Container Registry.

## Supported images

| Name                                                                                 | Upstream Issue                                                                                                                                                                                   |
|--------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [code-server](https://github.com/cdr/code-server)                                    | [![GitHub issue status](https://img.shields.io/github/issues/detail/state/cdr/code-server/3335)](https://github.com/cdr/code-server/issues/3335)                                                 |
| [node-red](https://github.com/node-red/node-red)                                     | [![GitHub issue status](https://img.shields.io/github/issues/detail/state/node-red/node-red/3107)](https://github.com/node-red/node-red/issues/3107)                                             |
| [prometheus-qbittorrent-exporter](https://github.com/esanchezm/prometheus-qbittorrent-exporter) | [![GitHub issue status](https://img.shields.io/github/issues/detail/state/esanchezm/prometheus-qbittorrent-exporter/12)](https://github.com/esanchezm/prometheus-qbittorrent-exporter/issues/12) |

## Contributing

- If not already created, create an issue upstream asking for them to support an additional registry.
- Open a PR adding a new application to the `apps` folder, update the `README.md` with the issue link, and then update `.github/renovate.json5` to auto merge it.
- Remind us to make the image public after the PR is merged ;)
