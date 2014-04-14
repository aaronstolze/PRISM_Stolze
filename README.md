PRISM_Stolze
============

Lab 4 Prism 


# Design

The first thing I had to create was the ALU.  In order to do this, a different type of cast had to be made for each of the eight components to be implemented (AND, NEG, NOT, ROR, OR, IN, ADD, LD).  Each of these components were coded using signed and unsigned type casting in order to efficiently create all cases.  

The AND command took the Data information and combined it with the Accumulator.

The NEG command took the 2's complement of whatever is in the Accumulator.

The NOT command took the 1's complement of whatever is in the Accumulator.

The ROR command shifted the Accumulator values by 1.

The OR command takes what is is in the Data path and OR's it with the Accumulator before combining it with the Accumulator.

The IN command takes the Data information and replaces the value of the Accumulator.

The ADD command combines the Data and Accumulator.

The LD command loads the value into the Accumulator. 




The following waveform was created when testing the ALU: 

![alt text](https://raw.githubusercontent.com/aaronstolze/PRISM_Stolze/master/ALU_Waveform.PNG "ALU Waveform")




Once the ALU was completed the next step was to create the datapath.  Following the given directions in the Datapath shell, the necessary registers were implemented.  The following waveform was generated: 

