# AccessPoint
This is a part of the CarpenPi project, which aims to bring Software Carpentries to the Raspberry Pi, for use in off-grid and resource constrained environments.

To enable the Raspberry Pi's to communicate with one another (enabling training in collaborative programming) one Pi will be used as a dedicated wireless router which the other Pi's will connect to. Since we are creating a local wireless network all Pi's must have wireless capabilities. Raspberry Pi 3's and 4's all have inbuilt wireless adapters but older models will need USB wireless adapters (and the relevent drivers installed). 

RaspAP enables Raspberry Pi's to be used as wireless routers. Full documentation is available on their website https://raspap.com/.

To install:

```
# In the Raspberry Pi Terminal
curl -sL https://install.raspap.com | bash
```
The rest of the Pi's then can connect to the 'raspi-webgui' network using the password 'ChangeMe'.

# Raspberry Pi Image
This repo contains a pre-made image for a Raspberry Pi using Raspbian with RaspAP preinstalled and ready to use out of box. This assumes the Pi is 3 or greater.  
