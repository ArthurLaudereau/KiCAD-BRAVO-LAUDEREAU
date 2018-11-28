# Project Title

Clément BRAVO & Arthur LAUDEREAU 's KiCAD gas sensor project

### The project step by step

Firstly we creted a project using the Arduino UNO template on KiCAD.

Then, we created a symbol for each component : 
    - RN2483_Breakout
    - LTC1050
    - Gas sensor TO-5-4

And their footprints.

```
NOTE : We used a 8-pins connector to replace the RN2483_Breakout because it was too big, but the footprint created is still in the library "projet" located in the folder
```

After the designing of the electrical schema
![ElectricalSchema](pcbschema.png)

And assigning a footprint to each component,

We did the wiring on the PCB :
![PCB](pcb.png)

And to finish our "Piste Verte", we rendered our PCB in 3D !
![PCB2D](pcb2d.png)
![PCB3D](pcb3d.png)

## Bonus 

There is a backup of the wiring named "avant_remplissage", although it is not used
we decided to keep it to be safe.
