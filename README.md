**eudev** is a standalone dynamic and persistent device naming support (aka
userspace devfs) daemon that runs independently from the init system.
**eudev** strives to remain init system and linux distribution neutral. It is
currently used as the devfs manager for more than a dozen different linux
distributions.

This git repo is a fork of git://anongit.freedesktop.org/systemd/systemd with
the aim of isolating udev from any particular flavor of system initialization.
In this case, the isolation is from systemd.

This is a project started by Gentoo developers and testing was initially being
done mostly on OpenRC. We welcome contribution from others using a variety of
system initializations to ensure **eudev** remains system initialization and
distribution neutral. On 2021-08-20 Gentoo decided to abandon eudev and a new
project was established on 2021-09-14 by Alpine, Devuan and Gentoo
contributors (alphabetical order).

Homepage: https://github.com/eudev-project/eudev

Tarballs of releases: Clone this repo.

The eudev community gathers on [Libera.Chat](https://libera.chat/):  
ircs://irc.libera.chat:6697/#eudev  
https://web.libera.chat/#eudev
