Release Notes MDDE Software Version 1.4.0
=========================================

To report a bug please send an email to motec.service@ametek.com

new: 
----

- image source - multicast feature:
  - multicast ip: multicast ip address for the device
- wireless module:
  - mode assignment: assign the module connected to the display as client or access point
  - signal quality: show the signal quality in the wireless menu
- motorzoom plugin:
  - signal quality: show the signal quality of the wireless module in the motorzoom plugin
  - channel switch indication: mark the signal quality red to recommand a channel switch indication
  - active motorzoom camera: show with a blue frame which motorzoom camera is activated an will be configured by the ui


changes & improvements: 
-----------------------

- with a long press on the camera image the active motorzoom can be switched

fixes: 
------

- motorzoom plugin: motorzoom control possible if motorzoom ip was changed
- overlay feature: overlay list is displayed correctly
- auto detection: no crash when running with MCDE3000 (old variant)
- auto detection: creates a valid image source list when running with cameras configured to the same port (before it created number-of-cameras^2 image sources)

    
