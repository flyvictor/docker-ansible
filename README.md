Docker-Ansible base images
===================

## Summary

Repository name in Docker Hub: **[flyvictor/ansible](https://registry.hub.docker.com/u/flyvictor/ansible/)**

This repository contains Dockerized [Ansible](https://github.com/ansible/ansible), published to the public [Docker Hub](https://registry.hub.docker.com/) via **automated build** mechanism.

It's forked from https://github.com/William-Yeh/docker-ansible to add an Ubuntu 15.10 version

## Configuration

These are Docker images for [Ansible](https://github.com/ansible/ansible) software, installed in a selected Linux distributions.

- OS: Debian (jessie, wheezy), Ubuntu (xenial, trusty, precise), CentOS (7, 6), Alpine (3).

- Ansible: three version series -

  1. the most recent *stable* version;
  2. old 1.9 version;
  3. the *experimental* version.


## Images and tags

### Stable version (installed from official PyPI repo):

- Normal series:

  - `flyvictor/ansible:ubuntu15.10`

For further instructions refer to the [upstream repo](https://github.com/William-Yeh/docker-ansible)