# Container Images Mirror

Stop-gap container registry mirror of upstream applications that only use Docker Hub

## Purpose

This is to get around Docker Hub rate-limiting (100 pulls / 6 hours, or authenticated 200 pulls / 6 hours). It is considered a stop-gap until the maintainers of the applications below support a different Container Registry.

## Supported images

When upstream maintainers add support for an additional registry, the images here will be purged after awhile.

| Name                                                                                                      | Upstream Issue                                                                                                                                                                                   |
|-----------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [1password/*](https://github.com/1Password/connect)                                                       | [![GitHub issue status](https://img.shields.io/github/issues/detail/state/1Password/connect/56)](https://github.com/1Password/connect/issues/56)                                                 |
| [ansible-semaphore/semaphore](https://github.com/ansible-semaphore/semaphore)                             | [![GitHub issue status](https://img.shields.io/github/issues/detail/state/ansible-semaphore/semaphore/1149)](https://github.com/ansible-semaphore/semaphore/issues/1149)                         |
| [filebrowser/filebrowser](https://github.com/filebrowser/filebrowser)                                     | [![GitHub issue status](https://img.shields.io/github/issues/detail/state/filebrowser/filebrowser/2376)](https://github.com/filebrowser/filebrowser/issues/2376)                                 |
| [glauth/glauth](https://github.com/glauth/glauth)                                                         | [![GitHub issue status](https://img.shields.io/github/issues/detail/state/glauth/glauth/298)](https://github.com/glauth/glauth/issues/298)                                                       |
| [vectordotdev/vector](https://github.com/vectordotdev/vector)                                             | [![GitHub issue status](https://img.shields.io/github/issues/detail/state/vectordotdev/vector/6715)](https://github.com/vectordotdev/vector/issues/6715)                                         |

## Docker OSS Program

Certain containers may not be rate limited if they are in Docker Hub's OSS Program or verified publishers. Below is a list of applications I have discovered to be part of these program.

- bitnami/*
- grafana/*
- intel/intel-deviceplugin-operator
- intel/intel-gpu-plugin
- nodered/node-red
- rook/ceph
