
Release Notes MDDE Software Version 1.0.0
=========================================

To report a bug please send an email to motec.service@ametek.com

new features
------------

- display settings menu
  - backlight
    - automatic mode: backlight is set based on the ambient light sensor information
      - day mode: manual mode where brightness can be set between 0 and 100
      - night mode: manual mode where brightness can be set between 0 and 100
  - orientation: switch between horizontal and vertical ui orientation
    - short cuts
      - add: add a view mode to the short cut list
      - remove: remove a view mode from the short cut list
      - short cut timer: set a timer to toggle continuously through the view mode short cuts

- image source menu
  - add: add a new image source by entering the destination port of the source
  - remove: remove an image source
  - change: change an image source (change the port)
  - preview: when an image source is selected, its image is shown in the preview window

- view mode menu:
  - templates: single, split horizontal, split vertical, triple top, triple bottom, triple right, triple left, h, quad, pip
  - add: add a new view mode (choose a template and add image sources to the slots)
  - remove: remove a view mode
  - change: change a view mode (change the template and/or change the image sources at the slots)

- interface menu: 
  - ethernet settings: set / change the ip address and the netmask of the device

- system menu: 
  - information: show system information: serial number, item number, software version, mac address
  - languages: englisch, german, french, spain, portuguese, polish, russian
  - licenses: directory containing all licenses

- admin menu: 
  - pin: admin menu is locked with a pin
  - diagnostics: copy logfile to sd card
  - update: updates can be done via website (http://<ip address>:8080)
  - factory defaults: reset configuration to factory defaults
  - reset pin: reset admin pin
  - yocto version: hardknott
  
changes & improvements: 
-----------------------

fixes: 
------
