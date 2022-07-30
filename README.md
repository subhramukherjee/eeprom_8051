# eeprom_8051
Interfacing eeprom with 8051 mcu, Assembly code
In this project we implemented interfacing of eeprom 24c04 with a 8051 microcontroller. We took inputs from a 3x4 matrix keypad. Display the input on Seven Segment Displays. Save the input as required. Display the same input at a later time whenever required.

To accomplish the project arrange the circuit as given in the zip file. A breadboard is helpfull to make the connection. Open the Keil uVision and open eeprom.uvproj inside the Keil uVision. Build it and create the eeprom.hex file. Upload the .hex file to the 8051 mcu. [We can upload the .hex file to 8051 while it is on board throgh the spi mode using mosi, miso, clk, vcc,gnd and rst pin]. Once .hex file is uploaded, give power to the 8051 mcu. Input some value through the keypad. The value will be displayed on the seven segment display. Save the number on pressing a certain key (press *). Retrieve the number from eeprom on pressing another key(press #). 
