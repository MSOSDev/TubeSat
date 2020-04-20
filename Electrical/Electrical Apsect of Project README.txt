The electrical aspect of the project consists of 3 main components:
- The solar array
- The power management circuit (PMC)
- The digital processing circuit (DPC)

The PMC and DPC will be placed on a single PCB that is in the general shape of a long strip.
The PCB will then be slid into the plastic caddy that also holds the batteries. The caddy
will then be slid into the core casing with header pins with filed ends used as standoffs.

Microsat_Design.ms14 contains the Multisim 14.1 design file for the PMC and DPC. The current
progress consisted of merging the Arduino Nano circuit and the cell balancing circuit shown
in the AN2344 application note.

The power leads from the solar array would be fed to the PCB via the feedthrough pins located
in the ceramic feedthrough cap. A peltier control circuit using PWM from the DPC and an OpAmp
has yet to be added to the circuit.