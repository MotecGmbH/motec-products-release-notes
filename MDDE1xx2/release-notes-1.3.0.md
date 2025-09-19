Release Notes MDDE Software Version 1.3.0
=========================================

To report a bug please send an email to motec.service@ametek.com

new: 
----

- buzzer functionality recieving via MCP:
  - volume : min /max 
  - pitch: min /max 
  - pattern_on_ms: buzzer on duration 
  - pattern_off_ms: buzzer off duration
  - max_signal_length: break till the next MCP command
  - allow_mute: if the buzzer can be muted
- buzzer functionality recieving via UI:
  - volume: in percentage
  - pitch : in percentage
  - mute/unmute

changes & improvements: 
-----------------------

fixes: 
------

- brightness initialization for day/night mode 
    
