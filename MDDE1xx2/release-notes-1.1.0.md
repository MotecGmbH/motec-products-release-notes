Release Notes MDDE Software Version 1.1.0
=========================================

To report a bug please send an email to motec.service@ametek.com

new: 
----

- dhcp lite: auto detection of motec cameras including configuration of the streaming ip and streaming port
- image source settings: 
  - fit: fit the image to the slot boundaries
  - mirror: mirror the image horizontal and/or vertical
  - rotation: rotate the image in 90° steps
  - zoom: zoom into the image and shift the zoom window
    
- overlays: 
  - line: add line overlays and configure the thickness, style, color
  - text: add text overlays and configure the size, color and rotation
    
- can: 
  - configuration: configure node id and baud rate
  - feature: set a view mode
    
changes & improvements: 
-----------------------

- freeze detection : show user information if the resolution is not supported
  
fixes: 
------

- race condition : fix condition variable in the command queue
- active view mode name : set a new active view mode if the active one was deleted
- delete last view mode in short cut list : results in adding the first view mode in the view mode list to the short cut list
    
