# Subdermal Implant: E Ink NFC-enabled tattoo

Project to create subdermally implantable NFC-enabled device with a flexible E Ink display.

The likelyhood of success is extremely small due to low chance of getting clear enough image when reflected light passes through many layers of the skin. Glow-in-the-dark or reflictive material used for the light side of spheres within the E Ink display could potentially improve the visibility of the image.


## Development

### Phase 1
Proof of concept. A prototype featuring a flexible E Ink display, NFC coil, and a microcontrolle with a firmware. The display will serve as well as a memory device, there should be no need for external RAM or NAND modules outside of the microcontroller.  No battery needed, NFC should be able to provide enough power for operation of the device. NFC with the prototype could be performed by using Arduino or a similar development board. Embed unique security key into the firmware of the microcontroller to prevent the displayed information from being changed without knowing the key.

### Phase 2
Switch to using flexible PCB material. Test visibility using pig skin. Develop a smartphone app.

### Phase 3
Final prototype coated in thin bio-compatible material.


## References
 - http://www.plasticlogic.com/products/displays/
 - https://www.nfcworld.com/2013/11/20/326962/passive-nfc-chip-can-power-lights-sounds/
