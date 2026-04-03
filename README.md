# how_to_use_pxe_server_to_boot_iso_files
use this tecniques to boot windows iso or Macrium or Acronis or Aomei recovery boot PE

AOMEI backupper can be used for cloning and restoring windows computer only,AOMEI backupper has pxe boot option and MAcrium Reflect techniciaan plus doesnt have pxe boot option.
AOMEI backupper may fail if u close the entire hard drive while Operating system is running.For cloning just Operating System and MBR, cloning can be done successfully with AOMEI 
backupper is running. To clone entire hard drive which doesnt have linux (only winodws operating system)should be present, this compete disk cloning has to be done by booting computer
with AOMEI rescue usb ,this rescure usb drive can be created using AOMEI backupper software.

Maacrium Reflect Technician plus can only deploy cloned image to other computers in LAN using rescue usb pendrive creatd using Macrium Reflect.

To make Macrium Reflect rescute media to work in LAN as PXE boot then u have to use AOMEI pxe server present in this project repository and use DHCP option present in 
AOMEI pxe server software if the router doesnt allow PXE boot.

alternatively u can use Serva PXE server to boot any Windows operating system iso or Macrium or Acronis or Aomei recovery boot PE.
follow the exact file names which were used in the below videos,otherwise Serva pxe server will not work and while ISO is pxe booting using Serva software,
dont use internet as it will fail the PXE boot (that is TFTP server) due to repeated timeouts caused in its communication.

if u have router which provides DHCP then follow this procedure where u should not provide any static ip address to your Ethernet Adapter.

https://www.youtube.com/watch?v=4zPvvr-4zZc&list=WL&index=3&t=654s

if u dont have have router then follow this procedure where u should create static ip address to your Ethernet Adapter.

https://www.youtube.com/watch?v=-gSNOoWoya4&t=120s

Ventoy PXE server, DLC boot and  Tiny PXE server ,these softwares didnt work for me. If anyone wants to try it , they can check youtube tutorials


