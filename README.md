# ubuntu_chroot_onAndroid

inet:gid 30003 group,_apt :user
usermod -g inet _apt

telnet 192.168.43.134 5023

cd /data/local/mnt
chroot . /bin/bash

linux deploy stop container 

export TMTDIR=/tmp

/bin/bash no such file,rootfs must be arm64 not amd64
