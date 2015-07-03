# openvswitch
On 2015-7-2, Open vSwitch version pumped to 2.3.1. Works now with OpenWrt trunk.
openvswitch
===========

UPDATE: Works now with OpenWrt "Barrier Breaker" (Bleeding Edge)

Open vSwitch 2.3.1 (OvS) package for OpenWrt

Installation
------------

Install this as a feed!

### Installation in OpenWrt

> cd $TOPDIR
> 
> echo 'src-git openvswitch git://github.com/liujindi/openvswitch.git' >> feeds.conf
>
> ./scripts/feeds update openvswitch
>
> ./scripts/feeds install -a -p openvswitch
> 
> make menuconfig
>
> select Network -> openvswitch-switch, openvswitch-controller
>
> echo '# CONFIG_KERNEL_BRIDGE is not set' >> .config



Development
-----------

Please fork on github and send pull requests.
