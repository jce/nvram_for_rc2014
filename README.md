NVRAM module for the RC2014.
Pages the lower 32K out when the ROM module is present. Does not forget its content even when powered off. Therefore can be used as program storage in addition to remanent data.

<img src="IMG_20260324_112853_093.jpg" alt="PCB 1.1 front" width="600" height="400">
<img src="IMG_20260324_112924_110.jpg" alt="PCB 1.1 back" width="600" height="400">
<img src="Screenshot at 2026-03-25 11-48-28.png" alt="PCB 1.1 kicad" width="600" height="400">

Errata for building pcb V 1.1 (actual, and in picture):
- Typo in ic name: 74HTC32 should be 74HCT32
- Resistor and capacitor value not in drawing / on silkscreen

Errata for building of the V 1.0 proto:
- 74LS32 should be 74HTC32
- RC2014bus pin1 is not indicated
- IC types are not on silkscreen
- Pull up resistor value is missing: 10K
- Partlist missing
- Ground issues. Bridge some ground planes if you want to use this proto!
- Top memory is the bottom ic, ic's are reversed.

