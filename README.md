# ctssh
A simple SSH session manager

This script will create a ~/.ctssh folder. This will contain your server definitions.
The directory structure is simple:
1. Create a file, the filename is the hostname you want to connect to
   Later on several settings in this file will be supported, but the mean idea
   is that you configure the servers via ~/.ssh/config.
2. Create a directory, to group several SSH sessions together
   The directoryname will be used as a groupname in CTSSH.
