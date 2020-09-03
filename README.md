<!-- Please do not change this html logo with link -->
<a href="https://www.microchip.com" rel="nofollow"><img src="images/microchip.png" alt="MCHP" width="300"/></a>

# Low-BOM Microphone Interface Using the Analog Signal Conditioning (OPAMP) Peripheral
<p align="left">
  <img width=800px height=auto src="images/setup.png">
</p>

A new feature introduced in the AVR® DB MCU is the Analog Signal Conditioning (OPAMP) peripheral. In this example, the OPAMP is used to amplify a weak signal up to the 100-millivolt range so that it can be detected by an analog comparator in the microcontroller (MCU) or converted to a digital signal by the MCU’s analog-to-digital converter (ADC). 
Three internal op amps are available for configuration in the AVR DB. The configuration for this example can be seen in the figure above. Including the MCU the setup uses an external electret microphone, a resistor, and a capacitor. For more information about setup and code, see the [application note](https://microchip.com/DS00003631).

## Related Documentation

* [AN3631 - Low-BOM Microphone Interface Using the Analog Signal Conditioning (OPAMP) Peripheral](https://microchip.com/DS00003631)
* [AVR128DB48 Curiosity Nano User Guide](https://www.microchip.com/DS50003037)
* [AVR128DB48 Device Page](https://www.microchip.com/wwwproducts/en/AVR128DB48)

## Software Used
* [Atmel Studio](https://www.microchip.com/mplab/avr-support/atmel-studio-7) 7.0.2397 or later
* Atmel Studio AVR-Dx_DFP version 1.3.67 or later
* For the MPLAB X version of this project, please go to [this repository](https://github.com/microchip-pic-avr-examples/avr128db48-low-bom-mic-interface-using-opamp-mplab)

## Hardware Used

* [AVR128DB48 Curiosity Nano](https://www.microchip.com/DevelopmentTools/ProductDetails/PartNO/EV35L43A)
* Electret microphone
* One 2.2kΩ resistor
* One 1µF capacitor

## Setup

* Connect the hardware together as seen in the schematic of the application note

## Operation
* Connect the AVR128DB48 Curiosity Nano to a computer using a USB cable
* Download the zip file or clone the example to get the source code
* Open the .atsln file with Atmel Studio
* Press *Start Without Debugging* (CTRL+ALT+F5) to run the application

## Conclusion
After going through this example, you should have a better understanding of how to set up the OPAMP peripheral to amplify weak signals from sensors into detectable signals for the MCU.  

