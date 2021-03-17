#Wake on Lan client
##A simple python script to allow one to wake a machine by name.

###Why
I have allways been stymied by the fact that to use the 'wake on lan' functionality you need to provide the mac address of a machine to wake, however the mac address is not discoverable when the machine is asleep. 
I wrote this script as a means of having the machine name and mac address pairing stored in a configuration file and the script will use this information be able to wake a machine by name.
 
###Usage
Add name and mac address pairs to the wol.cfg file to allow the script to determine the correct mac address to use to wake a machine.
 
###Installation
The installation will copy the script and configuration file to a bin directory in your home directory.

###Potential Updates
Allow the configuration file to be automaticly populated.
Provide the ability to manage the configuration file using the wol script.
