# Raspberrypi_Config
## Install_GPSD

1: pi@raspberrypi:~$ sudo apt-get install gpsd gpsd-clients python-gps
2: pi@raspberrypi:~$ sudo gpsd /dev/ttyUSB0 -F /var/run/gpsd.sock



