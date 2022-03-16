## Release Notes
* version 4.2.x
* release date: xx March 2022
### What is new
* Improved the motion compensation algorithm. 
** Wave profile is now compensated on the heave on the moving vessels
Better data quality on the moving vessels
* Improved the wave profile calculation when lost signal (raw range= 0) and the 2nd time around echo.
Enhancing the data quality (such as low wind and absence of ripples causing missing signal) and the 2nd time echo
Easier installation and remove the dependency on using a fixed tracking window. 
* NMEA output enhancements
Possible to send NMEA output up to 50 Hz (serial and /or TCP)
Clean up the NMEA output sentences (removed obsolete sentences and added relevant ones)
Allow users to export data (locally or remotely) at an increased resolution. 
Fixed the MRU status code definition in the PMIRR sentence
NMEA output UI improvements
Easier to identify the output frequency used when sending the data (locally or remotely)
* Cloud subscriptions:
Possible to sent range data at high frequency to the cloud (up to 10Hz). 
Increasing data resolution download in the cloud.
Possible to download raw range from the cloud
Allowing easier data quality troubleshooting
* Enhanced the UI 
Added the Status menu
Easier to identify the sensor status (hardware, system and output) making it easy for troubleshooting. 
Added the Service menu
Easier to install the sensor and run quality checks on the data. 
Useful for troubleshooting on the data quality
Added the Configuration menu
Easy to access and change the configuration
Aligning the menu setup with the other Miros products. 
Data pages updates
Focus on the data graph displays and clean up the layout. 
Aligning the data pages with the other Miros products
Motion page to appear only on the installations with the MRU enabled
Easy to install the sensor on the floating sites, enhancing the plug-and-play functionality
Added the reboot functionality from the UI (under the Service page)
Easier to reboot the sensor without accessing any backend commands. 
Updated the Help menu
Easier to configure the sensor with specific information and default values to each parameter. 
* Architecture upgrades
Improved the sweep processing performance in the code
CPU resource utilization enhancements
* Bug fixes:
NMEA sentences over TCP causing missing data and on serial output.
Fixed the Tp2 parameter calculation and export both on Cloud and Local.
Fixed Prod command which not working on data serial port. 
Fixed the MRU status code definition in the PMIRR sentence

### FW download 
* The new FW is available in the Blob: xxxx
* The new FW is also found under the RangeFinder SW folder internally: xxxx

## PoE
* ALL aaS RangeFinders will be updated to the PoE version as hardware. The cabling and setup: connecting to the old cabling setup as per the exisiting installation. 
* New PoE installations recommended to use the standard PoE setup with the PoE injector. 

## DNV Alpha factor
* According to the DNV standard for marine operations, the α-factor for waves can be increased if the wave sensor have a documented accuracy of better than +/-5% of measured value.
* 

