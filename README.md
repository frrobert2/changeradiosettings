# changeradiosettings

This is a quickie script to show how you could use rigctl from hamlib to change settings on your radio.

This script was inspired by https://www.youtube.com/watch?v=34c-d9LghdY

KM6LYW Radio

The new script was assembled by Robert W9RWB                                                                                                                                                           
The purpose is to change radio setting via the commandline on radios connected to your computer with hamlib

hamlib needs to be installed on your computer. The example settings for rigctl use rigctl -m 4 which denotes I am using fldigi for rig control.  If you are 

The script has one arqument the time in mniutes you want the script to change your radio settings before it changes the setting back.

The file command1.txt has the settings you want to change your radio to.

The file command2.txt has the setting you want to change your radio back to.

The exaple script and files are assuming you are using flrig to run your radio and that you are listening on 144.390 MHz for aprs traffic.
The script will change the frequency to 145.825 MHZ for the specified time in minutes then change the frequency back to 144.390 MHz.

You can add commands to both command1.txt and command2.txt to change additional settings if you want.  See the rigctl man page for more information
