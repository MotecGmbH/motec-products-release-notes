Release Notes MDDE Software Version 1.2.0
=========================================

To report a bug please send an email to motec.service@ametek.com

new: 
----

- motorzoom menu (for MCDE5200): add/delete motorzoom cameras by ip address
- motorzoom plugin:
  - presets: store up to three presets
  - zoom: zoom in and zoom out
  - focus: automatic or manual (near, far)
  - mode: day, night
  - heater: on, off, auto
- mcp:
  - auto resolution: bitrate and resolution of connected mcp clients are set based on the view mode template
- gpio: SWG 1+2 trigger zoom in and out
    
changes & improvements: 
-----------------------

- auto detect: add ip addresses of mcp clients

fixes: 
------

- buffer alignment: check image width and height to ensure correct buffer alignment
    
