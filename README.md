# F4-220
All info about hacking a TerraMaster F4-220 to run OpenMediaVault (OMV)

## Introcution

I was offered a Terramaster F4-220 last christmas. I installed TOS (TerraMaster OS) but it is garbage. Very few fonctionalities, only half a dozen available softwares

## How to open your F4-220

I won't spend too long on this as other people have done videos about it. Particularilly this one (hardware here is a 2 disks F2-220 but it is really close to the F4) : https://www.youtube.com/watch?v=fF2DHxoc83Q 

Please note that this youtuber uses a VGA cable to install an OS (around 2:00). I won't do the same as I don't own such cable.

## Hardware upgrades

Celeron J1800
2G RAM
Boot on USB

OS is stored on an 8G bootable USB key as a primary drive. I replaced it by a more sturdy SSD disk using an USB to SATA cable

F4-220 NASes have 2G of soldered RAM but once opened, you can easilly upgrade RAM to 4G with (TerraMaster sales them on amazon using part number KBM20056)


## What distro to install

http://openmediavault.org is pretty good for a home setup. Dozens of available softwares, good forums and support. 

The big caveat for me was to do a headless install as I do not have a VGA cable. Forunatelly there are people who have already done this :

http://forum.openmediavault.org/index.php/Thread/3453-Installing-OMV-w-o-keyboard-and-monitor-using-VirtualBox/

## OMV Installation and configuration
http://wiki.openmediavault.org/index.php?title=Installation


## More links about OMV disk/partition to RAID array
http://lazic.info/josip/post/installing-openmediavault-on-raid-device/
http://www.tecmint.com/create-raid-10-in-linux/
http://www.ducea.com/2009/03/08/mdadm-cheat-sheet/
