# KicadBerkerPower2
Black board

![Power](Kicad%20BerkerPower2a%203D.png)
# Mix project
The board consists of 5 separate sections that can be separated. On the backside its easy to see the different ground planes and where to cut the board if needed.
## Wemos D1 mini - section 1
Section 1 is the largest section on the board. It is intended as a development board for section 2 and 3.
Section 1 has an AM2320, a relay and a power supply. Besides this it has breakout of several pins and an LED for debug/information.
### Issues
There is one flaw with section 1 that should be addressed: The pins on the power connector are too close for 230V operation as the centerpin of the relay bridges the live and neutral (calculated to be min 2,3mm between open terminals - 3,2mm for certification) 

![Section1](Kicad%20BerkerPower2%20Schematic%20-%20sect%201.png)
### I2S connector 
D1 - SCL
D2 - SDA
### AM2320 
D1 - SCL
D2 - SDA
### Relay
D3 
### HLK-PM03 PSU
+3v PSU supply if mounted (bad footprint)
### Pull down LED
D8
## ESP12S - Section 2
Section 2 is the smaller than section 1 but with most features of it.
### AM2320 
### Relay
### HLK-PM03 PSU
## ESP12S - Section 3
### AM2320 
### Relay
### HLK-PM03 PSU
## PSU - Virtual GDN - "Floating ground section"
### Input +/- supply
### Output + 0 - supply
### Output regulated +5v GND (78L05)
## PSU
### Input + 0 - supply
### Output + 0 - regulated supply (78xx and 79xx)
