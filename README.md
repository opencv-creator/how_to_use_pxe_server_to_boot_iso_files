# how_to_use_pxe_server_to_boot_iso_files
use this tecniques to boot windows iso or Macrium or Acronis or Aomei recovery boot PE

AOMEI backupper can be used for cloning and restoring windows computer only,AOMEI backupper has pxe boot option and MAcrium Reflect techniciaan plus doesnt have pxe boot option.
AOMEI backupper may fail if u close the entire hard drive while Operating system is running.For cloning just Operating System and MBR, cloning can be done successfully with AOMEI 
backupper is running. To clone entire hard drive which doesnt have linux (only winodws operating system)should be present, this compete disk cloning has to be done by booting computer
with AOMEI rescue usb ,this rescure usb drive can be created using AOMEI backupper software.

for AOMEI pix boot and cloning and hard drive image restiration u can follow this youtube video, AOMEI pxe iso is present in this project repository and also in the below youtube link.

https://www.youtube.com/watch?v=YetBzzYwIcQ

only Macrium Reflect Technician plus software version can only deploy cloned image to other computers in LAN using rescue usb pendrive creatd using Macrium Reflect.

https://www.youtube.com/watch?v=I0IjbOyJqRA&t=95s

To make Macrium Reflect rescute media to work in LAN as PXE boot then u have to use AOMEI pxe server present in this project repository and use DHCP option present in 
AOMEI pxe server software if the router doesnt allow PXE boot.


******* Settings for all PXE servers (Screen shots) are present in this respoitory)

alternatively u can use Serva PXE server to boot any Windows operating system iso or Macrium or Acronis or Aomei recovery boot PE.
follow the exact file names which were used in the below videos,otherwise Serva pxe server will not work and while ISO is pxe booting using Serva software,
dont use internet as it will fail the PXE boot (that is TFTP server) due to repeated timeouts caused in its communication.

if u have router which provides DHCP then follow this procedure where u should not provide any static ip address to your Ethernet Adapter.

https://www.youtube.com/watch?v=4zPvvr-4zZc&list=WL&index=3&t=654s

if u dont have have router then follow this procedure where u should create static ip address to your Ethernet Adapter.

https://www.youtube.com/watch?v=-gSNOoWoya4&t=120s

link for Tiny PXE server, if u have Router then ProxyDHCP,BINL and HTTP options have to be selected and dont provide static ip address to computer.

https://erwan.labalec.fr/tinypxeserver/pxesrv.zip &emsp;(Tiny Pxe server download link) 

https://www.youtube.com/watch?v=o8wOb6KdzoQ&t=50s

DLC boot sofware also contains Tiny PXE server only 

https://drive.usercontent.google.com/download?id=1IgCT7OKMuDCCdhSUAmtDirlPeBaIisSS&export=download&authuser=0&confirm=t&uuid=ea78671f-fe55-4129-b653-0cedecb60d3b&at=AGN2oQ26cwJPvWgCwJTcrp3Tn4Ie%3A1774915194476
 
iVentoy PXE server (for iventoy pxe server, to make use of internal dhcp server which can provide ip address to the computers in the LAN, use the setting DHCP server mode as internal and seconday DHCP off.)
https://github.com/ventoy/PXE/releases

u can also use AOMEI PXE server old version which can be dowblaoded from this respoitory or from below download link

https://aomei-pxe-boot-free.software.informer.com/1.5/

if AOMEI pxe server says that ports 67,69 ports are occupied, use the below link to solve the problem

https://www.ubackup.com/help/pxe-port.html

