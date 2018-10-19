# Official Ubuntu images on Scaleway

[![Travis](https://img.shields.io/travis/scaleway/image-ubuntu.svg)](https://travis-ci.org/scaleway/image-ubuntu)
[![Scaleway ImageHub](https://img.shields.io/badge/ImageHub-view-ff69b4.svg)](https://hub.scaleway.com/ubuntu-trusty.html)
[![Run on Scaleway](https://img.shields.io/badge/Scaleway-run-69b4ff.svg)](https://cloud.scaleway.com/#/servers/new?image=ef5bc6b0-223c-4b63-ab52-0a6b394dd9df)

Scripts to build the official Ubuntu images on Scaleway

These images are built using [Image Tools](https://github.com/scaleway/image-tools) and depends on the [armhf port of ubuntu-deboostrap docker images](https://registry.hub.docker.com/u/armbuild/ubuntu-debootstrap/).

<img src="http://design.ubuntu.com/wp-content/uploads/logo-ubuntu_no®-black_orange-hex.svg" width="250px" />

---

**This image is meant to be used on a C1 server.**

We use the Docker's building system and convert it at the end to a disk image that will boot on real servers without Docker. Note that the image is still runnable as a Docker container for debug or for inheritance.**

[More info](https://github.com/scaleway/image-tools)

Available tags
--------------

- precise (12.04)
- trusty (14.04, lts)
- vivid (15.04, latest)

---

Install
-------

Build and write the image to /dev/nbd1 (see [documentation](https://www.scaleway.com/docs/create_an_image_with_docker))

    $ make install

Full list of commands available at: [scaleway/image-tools](https://github.com/scaleway/image-tools/#commands)

Links
-----

- [Community: Official Ubuntu Image](https://community.cloud.online.net/t/official-ubuntu-image/345?u=manfred)
- [Community: New Linux Distributions on C1](https://community.cloud.online.net/t/official-new-linux-distributions-debian-coreos-centos-fedora-arch-linux/229?u=manfred)

---

A project by [![Scaleway](https://avatars1.githubusercontent.com/u/5185491?v=3&s=42)](https://www.scaleway.com/) [![GuardRails badge](https://badges.production.guardrails.io/moul/image-ubuntu.svg)](https://www.guardrails.io)
