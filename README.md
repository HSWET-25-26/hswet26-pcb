Only edited schematic
Deleted 6v back converter

Schematic
- [x] 1x5 connecter -> 1x4 connector, deleted 6v line
- [x] Resistor and diode are swapped make sure they are swapped - on safety page
- [x] 5V_BUCK label should be 4.5V_BUCK


PCB
- [ ] Trace sizes
    - [ ] Check what gauge traces going into ina (lol it's not nearly what I fixed it for but might as well keep it)
    - [ ] Use larger trace sizes if possible though, no reason not too. And power planes for 9V and turbine for extra safety
- [X] Both of the LM2596 replace with full board
    - [X] Deleted 6v buck converter
- [ ] Add pads for debugging
    - [ ] add Nets:
        - [ ] Linear actuator signal (D5)
        - [ ] Encoder (D2)
        - [ ] Safety signal (D4)
        - [ ] Turbine power 
        - [ ] Lowkey everything there’s not that many nets
- [ ] Add labels to everything!!! on the board! make it as clear as possible
- [ ] Things to double check b/c Mirabel thinks she routed it wrong:
    - [ ] vias on 2 ground pins on U4
      


- [ ] Add holes on corners for default m3 screws
