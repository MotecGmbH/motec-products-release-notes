
Release Notes CWS Software Version 1.0.0
=========================================

To report a bug please send an email to motec.service@ametek.com

new features
------------

- configuration via website
  - number of streams up to four
  - camera input (only MJPEG) and video output (only H264) 
  - calibration of every stream
  	- automatic calibration with four tags
  	- manual calibration with four tags
  	- manual calibration with definition of camera position (x, y, z, yaw, pitch, roll)
  - define zones (red areas for warning, yellow area for information)
   	- rectangle zone with center, height and width
   	- radial zone with center and radius
   	- freeform zone can be drawn manually on the image
  - configure visualizsation settings
  	- show warning frame or/and
  	- show zone filled or unfilled or/and
  	- show detected objects with boundingbox or/and
  	- show detected objects with warn marker
  	- select colors 
  	- ...
- person detection for persons in defined zones and if configured outside warning areas
- activate every stream with GPIO-signal
- buzzer signal when a person in red area is detected
- track detected persons to improve detection rate
- including hysteris to prevent bounding box trembling
- versioning of settings
  
changes & improvements: 
-----------------------

fixes: 
------
