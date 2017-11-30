# EPSI_git

Pre-requisit: 
  - download anaconda3 for python
  - in a terminal "conda install pyserial"


1/ Connect EPSI and your laptop with an FTDI serial device. The python reader will an issue if you have more than one FTDI device. It is possible to set the name of the device in read_SBE49_EPSI_hex_2.0.py. TODO: give the user a choice if more than 1 device is available

2/ in a terminal: python read_SBE49_EPSI_hex_2.0.py

3/ in  another terminal: python plot_SBE49_EPSI_hex_realtime_maptest.py 

4/ in  another terminal: python plot_SBE49_EPSI_hex_realtime_spectrum_maptest.py

