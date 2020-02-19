
LoRaShield2.1 Hardware


These are the hardware design files for the LoRaShield2.1 electronics.

These hardware files were created with KiCAD. 
You may need the KiCAD libraries available here: https://github.com/mogar/KiCAD_libs
When opening these projects in KiCAD, you may need to change the path to the libraries from the above link.
This can be done in preferences->libraries in both the schematic editor and the layout editor.
Make sure the libraries noted there point to wherever you put the above KiCAD_libs repo.

# Arduino Library

Check out these libraries:

* https://github.com/EnhancedRadioDevices/LoRaHam
* https://github.com/EnhancedRadioDevices/LoRaChat

# LoRaShield 2.1 Pinout

LoRaShield uses the SPI pins on your Arduino. It also uses a couple of digital pins for reset and interrupt.

    Arduino <-> LoRaShield
    D2          interrupt
    D3          reset
    D10         SPI SS
    D11         SPI MOSI
    D12         SPI MISO
    D13         SPI SCK
    


