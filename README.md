# ipmitool Docker image

[![CircleCI](https://circleci.com/gh/urzds/ipmitool-docker.svg?style=shield)](https://circleci.com/gh/urzds/ipmitool-docker)

ipmitool in a Docker image for easy consumption in e.g. CoreOS

## Patches

ipmitool 1.8.16 needs some patches to build for Alpine Linux:

* ipmitool-1.8.16-imbapi-include-stddef-h.patch
* ipmitool-1.8.16-imbapi-include-socket-h.patch
* ipmitool-1.8.16-imbapi-pagesize.patch"

See-Also: https://sourceforge.net/p/ipmitool/bugs/426/
