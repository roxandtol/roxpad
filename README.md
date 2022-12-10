# rOxpad v1
A simple 3k keypad with QMK and VIA support, designed with osu! in mind

I've designed the keypad using [KiCad](https://www.kicad.org/) for the PCB, and [OnShape](https://www.onshape.com/en/) for the case.

---
# Making it
**⚠️⚠️⚠️ This keypad is still a WIP, but I've laid down all the fundamental things I want (except QMK) ⚠️⚠️⚠️**

You will need:
1) The components:
    |Component|Quantity|LSCS code|
    |---|---|---|
    |Atmega16u2-AU|1|C59019|
    |16 Mhz Crystal|1|C13738|
    |Polyfuse|1|C151162|
    |USB Type-C female connector|1|C165948|
    |Diode array|1|C2827688|
    |Diodes|3|C81598|
    |0.1uF Capacitor|2|C49678|
    |1uF Capacitor|1|C28323|
    |10uF Capacitor|1|C15850|
    |22pF Capacitor|2|C1804|
    |22Ω Resistor|2|C17561|
    |5.1kΩ Resistor|2|C27834|
    |10kΩ Resistor|2|C17414|
    |Kailh MX hotswap sockets|3|C2803348|
    
1) The PCB design in [The releases tab](https://github.com/r0xANDt0l/rOxpad/releases/latest)
1) The DXFs in [The case folder](/rOxpad-case/) cut with a laser cutter or a CNC at the height it says on the name of the file
1) A soldering iron
1) Solder with a flux core
1) Flux
1) 4 m3*22 screws with their nuts
1) Hot glue (for the feet)

Note that since it's SMD, it would be a lot easier with a hot air station, but most ICs except the diode array, which is QFN, are TQFP

Now, to make the keypad, you will start by:
1) Soldering everything to the board, starting with the USB-C, to the 16Mhz Crystal, then the MCU 
(make sure to check the sides! There should be a dot on the corner of the MCU, and that dot should be on the upper side), And finally the resistors, capacitors
and the Keilh hotswappable socket

1) Stacking the first 2 layers of the Acrylic and then putting the PCB on top
  
  First layer (Should be 3mm):
  
  ![image](https://user-images.githubusercontent.com/41841903/206813507-63869746-9e3e-439c-aea7-37886cf41ae6.png)
  
  
  Second layer (Should be 3mm):
  
  ![image](https://user-images.githubusercontent.com/41841903/206813535-c3493d8a-3d35-4e91-ba91-51a4845ba40c.png)


3) Add the rest of the layers to the Acrylic

  Third layer (Should be 3mm)
  
  ![image](https://user-images.githubusercontent.com/41841903/206813784-6be1ace9-781f-42ff-8756-dd2de4f81942.png)

  
  Fourth layer (Should be 5mm)
  
  ![image](https://user-images.githubusercontent.com/41841903/206813802-b4b9171d-da5c-4ae8-bd38-0fc1b03694e2.png)

  
  Fifth layer (Should be 3mm)

  ![image](https://user-images.githubusercontent.com/41841903/206813811-f75b4caf-532e-40dc-9644-3f013e980472.png)
