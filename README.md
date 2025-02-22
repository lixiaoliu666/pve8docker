# pve8docker
pve8docker based from detain 12 bookworm

参考项目 https://github.com/Chocrates/qemu-build 而来

Reference project: https://github.com/Chocrates/qemu-build

在debain12 docker基础上安装pve8的源，用于编译pve8上的各种软件使用，比如项目https://github.com/lixiaoliu666/pve-anti-detection 就在使用这个docker进行编译pve-qemu deb

This Docker image is based on Debian 12 with Proxmox VE 8 repositories configured, designed for compiling various software packages on Proxmox VE 8. For instance, the project https://github.com/lixiaoliu666/pve-anti-detection uses this Docker environment to compile PVE-QEMU Debian packages.

https://github.com/lixiaoliu666/pve7docker 也可以使用这个用于pve7上编译使用

The repository https://github.com/lixiaoliu666/pve7docker can also serve as a reference for compiling software on Proxmox VE 7 systems.

如何使用：

Usage:

docker pull ghcr.io/lixiaoliu666/pve8docker:main
