# modbus
modbus tcp connection between two arduino uno :
first in this project i used
2 arduino uno
1 enc28j60 (mni) ethernet module
1 wiznet w5500 ethernet module
jumpers 

//////////////////////////////////////////////////////////////
arduino to ethernet module connection :


Arduino                       w5500              
  5v                            5v
 MISO                          MISO
 MOSI                          MOSI
SS-D10                         SCS
 SCK                           SCLK
 RST                           RST
 GND                           GND
-----------------------------------------------------------------------------------------------
ARDUINO                   MNI ENC28J60
 3,3V                        VCC
  D8                         CS
 D11                         SI
 D12                         SO
 D13                         SCK
 GND                         GND
 
