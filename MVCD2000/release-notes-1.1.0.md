
Release Notes CWS Software Version 1.1.0
=========================================

To report a bug please send an email to motec.service@ametek.com

new features
------------

- read byte tracker parameters from internal settings files, not adaptable via website
      - min. probability for new_object 
      - min. probability for tracked_object
  
changes & improvements: 
-----------------------

- neural network YoloX_Tiny for ethernet and YoloX_nano for LVDS
      - yolox_tiny_coco_plus_416_B4096 -> Ethernet
      - yolox_nano_ndc_B1024 -> LVDS
- improve buzzer settings
      - add priority byte
      - add stream port byte
- differentiate between warning logging and detection logging, detection logging not to be enabled via website

fixes: 
------

- frequence of buzzer mcp commands
- dissolve detection logging variable from warning state changes
- resolve stream type version mismatch
- fix stream settings mapping
- fix zone allocation in vertical camera position
- save old calibration correctly
