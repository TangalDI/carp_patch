# carp_patch
Freebsd carp is not compatible with vrrp. This patch allows you to use carp with vrrp devices. Tested on freebsd 11.2, 12.1, 12.2, 13.0 and mikrotik ccr1036.

Apply

cd /usr/src

patch < carp.patch

then rebuild kernel
