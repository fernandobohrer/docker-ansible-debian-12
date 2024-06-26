# Debian 12 Ansible Test Image

[![github actions workflow status][github-actions-workflow-status-badge]][github-actions-workflow-status-link]
[![docker image pulls][docker-image-pulls-badge]][docker-image-pulls-link]
[![amd64 docker image size][amd64-docker-image-size-badge]][amd64-docker-image-size-link]
[![arm64 docker image size][arm64-docker-image-size-badge]][arm64-docker-image-size-link]

This repository contains a `Dockerfile` that is used to create a **Debian 12** based docker container image with `ansible` and `systemd` preinstalled.

## 🚀 Motivation

The container image that is created from this repository can be used for Ansible role testing.

The `systemd` package is installed so that this container image can be used to test Ansible roles that deploy services.

## 📦 Build process

This container image is built and uploaded automatically to Docker Hub once a week and any time a commit is made or merged to the `main` branch.

## 🧑‍💻 Image details

To get the container image that is created from this repository, execute: `docker pull fernandobohrer/docker-ansible-debian-12:latest`

## 🏷️ Tags

- `latest`: Latest stable version of `ansible`.

## ⚠️ Warning

Use this repository and the docker image that it creates at your own risk!

[amd64-docker-image-size-badge]: https://img.shields.io/docker/image-size/fernandobohrer/docker-ansible-debian-12?arch=amd64&style=flat-square&logo=docker&logoColor=white&label=amd64%20image%20size&labelColor=black&cacheSeconds=300
[amd64-docker-image-size-link]: https://hub.docker.com/r/fernandobohrer/docker-ansible-debian-12/tags/
[arm64-docker-image-size-badge]: https://img.shields.io/docker/image-size/fernandobohrer/docker-ansible-debian-12?arch=arm64&style=flat-square&logo=docker&logoColor=white&label=arm64%20image%20size&labelColor=black&cacheSeconds=300
[arm64-docker-image-size-link]: https://hub.docker.com/r/fernandobohrer/docker-ansible-debian-12/tags/
[docker-image-pulls-badge]: https://img.shields.io/docker/pulls/fernandobohrer/docker-ansible-debian-12?style=flat-square&logo=docker&logoColor=white&label=pulls&labelColor=black&cacheSeconds=300
[docker-image-pulls-link]: https://hub.docker.com/r/fernandobohrer/docker-ansible-debian-12/
[github-actions-workflow-status-badge]: https://img.shields.io/github/actions/workflow/status/fernandobohrer/docker-ansible-debian-12/build-test-and-push-docker-image.yml?branch=main&event=push&style=flat-square&logo=github&logoColor=white&label=Build%2C%20test%20and%20push%20docker%20image&labelColor=black&cacheSeconds=300
[github-actions-workflow-status-link]: https://github.com/fernandobohrer/docker-ansible-debian-12/actions/workflows/build-test-and-push-docker-image.yml
