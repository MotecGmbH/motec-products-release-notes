Release Notes MDDE Software Version 1.5.1
=========================================

To report a bug please send an email to motec.service@ametek.com

new: 
----
- Display sends DHCP heartbeat and is discoverable via NCC/MSV
- Icons appearing showing when the connection drops packets, stream is corrupted, no stream is received.


changes & improvements: 
-----------------------
- Pipeline performance improvements: Quad mode working with 640x400 
- Day/Night brightness adaptations working for the old & new Skoopia Module
- the buzzer can now handle messages from several sources, this was limited to one source simultaneously

fixes: 
------

- display does not crash when a MCDE3000 is connected before startup
- no bluescreen on the display after being idle for a while
- Pip in vertical mode working now just like in horozontal mode was
- Freezing display: sending DHCP Heartbeat solved a freezing display problem

    
