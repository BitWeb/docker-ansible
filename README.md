# docker-ansible

Docker image for using Ansible in CI pipelines, based on `python:3.12-slim-bookworm`.

**Included Packages:**
- `jq`
- `git`
- `openssh-client`
- `rsync`
- `sshpass`

Images are publised to Docker Hub [bitweb/ansible](https://hub.docker.com/r/bitweb/ansible).

Supports `amd64` and `arm64` architectures.

Maintained by: [Bitweb OÜ](https://bitweb.ee). Updates are published every Sunday.

# Supported tags

Ansible core package

* `latest`,`1-core`

Ansible full package with extra community extensions

* `1-full`

