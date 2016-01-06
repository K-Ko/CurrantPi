I wanted to have a simple way of checking out my Raspberry Pi's board temperature and other useful stats' so I cobbled together some php and bash to server up over [lighttpd](https://www.lighttpd.net/). 

Known Kludges
-------------
Takes 1 second to load in order to take two samples of the network Tx/Rx bit-count a second apart in order to determine the current transfer rates. 
 
Screenshot
----------
<img src="https://raw.githubusercontent.com/ColinWaddell/RPi-Board-Info/screenshots/img/screenshot.png?loadnew=true" align="left" width="384" >