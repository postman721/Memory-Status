# Memory-Status
Memory-Status repository(Bash)

Memory Status is a Bash program that I originally released with PostX Gnu/Linux  0.3 version. The program prints out information about memory usage and type. It can be executed via terminal with the command:

sh memory.sh

OR

sh /some_user/some_location/memory.sh

The commands used by the Memory Status are: uname, free and dmidecode. Uname and free should be already included by default within most modern Linux distributions. You will in most cases need to install dmidecode, which should be fairly easy. For example, in Debian family and within a terminal client: sudo apt-get install dmidecode

Be advised that dmidecode part uses sudo. You should be able to easily override the sudo behavior by running the program as a root user from the start. Generally, it is not advised to run programs directly as a sudo or root, so before you proceed make sure you understand exactly what you are doing. The code of Memory Status is relatively simple, so there should be no issues in checking it out before running it. 

![memory x70132](https://user-images.githubusercontent.com/29865797/28173357-e2b60646-67f6-11e7-9758-d2d538920ff0.jpg)

____________________________
Original post is at:
http://www.techtimejourney.net/memory-status-bash-program/
