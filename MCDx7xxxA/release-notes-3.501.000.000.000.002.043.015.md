
Release Notes MDDE Software Version 3.501.000.000.000.002.043.015
=========================================

To report a bug please send an email to motec.service@ametek.com

new features
------------

- AVB video Streaming
- PTP / gPTP time synchronisation
- A=Control configuration for RTSP
- Image configuration is possible while RTSP is streaming
- Added configurability for Stream-VLAN-ID
- Added Configure IP via MAC function


  
changes & improvements: 
-----------------------

- RTSP Port is now 554 instead of 8554


fixes: 
------

- Resolved an issue where the camera would lose its configuration during an Update
- Resolved a bug where the camera would always reboot with 29 FPS reported as >1100
- Resolved an issue where a certain range of MAC addresses would be reset during a Softwareupdate ( 2C:26:5F:51:00:00 – 2C:26:5F:5F:FF:FF )
- Resolved an issue where the camera would get stuck and not reboot after a software update
- fixed issue of needing a power-cycle when changing the subnet
- fixed using custom-destination-mac if set in factory_defaults ( FD to or from Multicast-IP )

