# KicadBerkerPower2
Black board

![Power](Kicad%20BerkerPower2a%203D.png)
# Mix project
The board consists of 5 separate sections that can be separated. On the backside its easy to see the different ground planes and where to cut the board if needed.
## Wemos D1 mini - section 1
![Section1](Kicad%20BerkerPower2%20Schematic%20-%20sect%201.png)
### I2S connector 
D1, D2
### AM2320 
D1, D2
### Relay
D3
### HLK-PM03 PSU
+3v PSU
### Pull down LED
D8
## ESP12S - Section 2
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
