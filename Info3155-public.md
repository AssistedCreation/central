#Information Security and Assurance - INFO3155
##Sandbox Set up

###Overview
* Component Overview
* Architecture
* Issues

### Component Overview
#### Computers
* Three Dell optiplex 990 desktops with core-i5 processors and 4 GB of RAM 
* The desktops are loaded with Windows 7, Windows 8 and Ubuntu 14.04 respectively.

####Networking Equipment
* Cisco 1900 Switch 
* D-link home Wi-Fi router


## System Setups
# Windows 8 
* File and Printer Sharing enabled
* XAMPP server started and online

# Ubuntu
* 

# Windows 7 
* File and Printer Sharing enabled
* XAMPP server started and online 

###Architecture
* The desktops are connected to the switch.
* The router is also connected to the switch. 
* There is no internet connection.

###Issues
* The windows 7 install was unable to find the network drivers for the Ethernet controller. In order to resolve this we had to use another computer to find the drivers online and install it.
* We were unable to setup the cisco switch with ssh access, instead we have resorted to using telnet in the interest of time. 
