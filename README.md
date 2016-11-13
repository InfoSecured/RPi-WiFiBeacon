# RPi-WiFiBeacon
This short python script for the Raspberry Pi 3 is set to run in the background will check for the presence of your cell phone's (static) IP address every 10 seconds.  It will then sleep for 30 minutes and confirm you are still there. It is also setup to send an HTTPS post which will work with apps like Stringify or IFTTT.

Please edit the IP address in the script to match that of the device you wish to check.  I would strongly suggest giving that device a static IP address.  You'll also want to setup the HTTPS post address.
