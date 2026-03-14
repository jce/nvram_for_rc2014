NVRAM module for the RC2014.
Pages the lower 32K out when the ROM module is present. Does not forget its content even when powered off. Therefore can be used as program storage in addition to remanent data.

PCB V1.1 is under development.

Errata since building of the V 1.0 proto:
- 74LS32 should be 74HTC32
- RC2014bus pin1 is not indicated
- IC types are not on silkscreen
- Pull up resistor value is missing: 10K
- Partlist missing
- Ground issues. Bridge some ground planes if you want to use this proto!
- Top memory is the bottom ic, ic's are reversed.

