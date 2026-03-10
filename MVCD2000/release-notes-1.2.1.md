
Release Notes CWS Software Version 1.2.0
=========================================

To report a bug please send an email to motec.service@ametek.com

new features
------------

  
changes & improvements: 
-----------------------

- GPIO based detection trigger adaption
  - The application starts in detection mode as default (different than in the previous releases).
  - A settings file can overwrite the behavior to enable GPIO based detection activation. This needs to be done during production and can not be adapted afterwards.

fixes: 
------

- Restrict streaming ports to the range of 1023 to 65535; excluding 8080, 8554 and 8885.
