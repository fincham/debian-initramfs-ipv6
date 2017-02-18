# debian-initramfs-ipv6

Bring up an IPv6 address during early boot. A quick hack to be used until this is fixed properly upstream ([Debian bug](http://bugs.debian.org/cgi-bin/bugreport.cgi?bug=627164), [Ubuntu bug](https://bugs.launchpad.net/ubuntu/+source/klibc/+bug/1621507)).

This is a mash up of inspiration from various sources:

* https://www.danrl.com/2015/10/21/debian-jessi-ssh-fde-unlock.html
* https://github.com/cornelinux/yubikey-luks
* The existing IPv4 mechanism (ip= kernel parameter)
