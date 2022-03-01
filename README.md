 #  Two-input NAND gate in 28nm technology
This repository presents the design of Two input NAND gate using Synopsis Custom Compiler on 28nm CMOS Tecgnology
# Table of contents
[Introduction](https://github.com/Sriram68/two-input-NANDgate/blob/main/README.md#introduction)

[Reference cicuit diagram](https://github.com/Sriram68/two-input-NANDgate#reference-circuit-diagram)

[Circuit details](https://github.com/Sriram68/two-input-NANDgate#circuit-details)

[Truth table](https://github.com/Sriram68/two-input-NANDgate/blob/main/README.md#truth-table)

[Tools used](https://github.com/Sriram68/two-input-NANDgate/blob/main/README.md#tools-used)

[Circuit diagram in Synopsys Custom Compiler](https://github.com/Sriram68/two-input-NANDgate/blob/main/README.md#circuit-diagram-in-synopsys-custom-compiler)

[Netlist](https://github.com/Sriram68/two-input-NANDgate/blob/main/README.md#netlist)

[Output waveform of the circuit](https://github.com/Sriram68/two-input-NANDgate/blob/main/README.md#output-waveform-of-the-circuit)

[Author](https://github.com/Sriram68/two-input-NANDgate/blob/main/README.md#author)

[Acknowledgements](https://github.com/Sriram68/two-input-NANDgate/blob/main/README.md#acknowledgements)

[References](https://github.com/Sriram68/two-input-NANDgate/blob/main/README.md#references)

# Introduction
   Complementary metal–oxide–
semiconductor (CMOS) is a type of MOSFET
fabrication process that uses complementary and
symmetrical pairs of p-type and n-type MOSFETs
for logic functions. CMOS technology is used for
constructing IC chips, including microprocessors,
microcontrollers, memory chips and other digital
logic circuits. CMOS technology is also used for
analog circuits such as image sensors (CMOS
sensors), data converters, RF circuits (RF
CMOS), and highly integrated transceivers for
many types of communication.
# Reference circuit diagram
![image](https://user-images.githubusercontent.com/100473775/155977790-f91fabbf-01cc-422f-998c-af3a539cf38b.png)
# Circuit details
As shown in the figure we have a CMOS two-input NAND
gate. P-channel transistors Q1 and Q2 are
connected in parallel between +V and the output
terminal. N-channel transistors Q3 and Q4 are
connected in series between the output terminal
and ground. With Q3 and Q4 transistors “on” and
Q1 and Q2 transistors “off”, the output is a logic
0. This condition happens when both inputs, A
and B, are logic 1.
With logic 0 in inputs A and B, Q3 and Q4
transistors are “off”, and Q1 and Q2 transistors
are “on”, producing a logic 1 output.
When one of the inputs is a logic “1” and the
other one is a logic “0”, either Q3 is “off” and Q2
is “on” or Q4 is “off” and Q1 is “on.” The output
in both cases is a logic “1”.
# Truth table
![image](https://user-images.githubusercontent.com/100473775/155979567-eb7ce9dc-68f0-4985-a433-2292b0ae5cbe.png)
# Tools used
• Synopsys Custom Compiler:

 The Synopsys Custom Compiler™ design environment is a modern solution for full-custom analog, custom digital, and mixed-signal IC design. As the heart of the Synopsys Custom Design Platform, Custom Compiler provides design entry, simulation management and analysis, and custom layout editing features. This tool was used to design the circuit on a transistor level.

• Synopsys Primewave:

 PrimeWave™ Design Environment is a comprehensive and flexible environment for simulation setup and analysis of analog, RF, mixed-signal design, custom-digital and memory designs within the Synopsys Custom Design Platform. This tool helped in various types of simulations of the above designed circuit.

• Synopsys 28nm PDK:

 The Synopsys 28nm Process Design Kit(PDK) was used in creation and simulation of the above designed circuit.

 # Circuit diagram in Synopsys Custom Compiler
 
The schematic of "two input NAND gate" has been created using 2 pmos and 2 nmos transistors as shown in the below figure.


 ![circuit diagram NAND](https://user-images.githubusercontent.com/100473775/156037022-8d4d4da2-7315-450d-9943-69893bd65114.png)

 
 # Netlist
 Refer to the netlist of the NAND gate [netlist](https://github.com/Sriram68/two-input-NANDgate/blob/main/NAND.cir.out)
 
 # Output waveform of the circuit
 After creating and saving the schematic go to 'Tools' and open 'Primewave' to start the simulation. In the Primewave select the 'model file' i.e the '28nm PDK's .lib file present in the HSPICE folder. After this select the 'tran' analysis in the analysis window. Then add the inputs and outputs which needs to be plotted.
 
Then go to 'Simulations -> Netlist and Run' to generate a netlist and run the simulation.

When both the inputs are high(i.e.,1.05v) the output of the NAND gate is low(i.e.,0v) and vice-versa. When one of the inputs is high and the other one is low, then the output will be high.

Lower reference voltage, Vlow for this circuit is 0v and higher reference voltage, Vhigh is 1.05v.
 ![output waveform NAND](https://user-images.githubusercontent.com/100473775/156036923-d9ea5e16-abef-413e-aec3-c02d695bee6f.png)

 Here the red and violet waves indicate the inputs and the green wave indicates the output.
 # Author
 
 Sriram G V, B.Tech(ECE), Sastra Deemed to be University, Thanjavur.
 # Acknowledgements
• [Cloud Based Analog IC Design Hackathon](https://www.iith.ac.in/events/2022/02/15/Cloud-Based-Analog-IC-Design-Hackathon/)
 
• [Synopsys India](https://www.synopsys.com/)

• [VLSI System Design (VSD) Corp. Pvt. Ltd India](https://www.vlsisystemdesign.com/)
# References
1. International Journal of Scientific &
Engineering Research, Volume 7, Issue 1,
January-2016 ISSN 2229-5518

2. [MOSFET model of a NAND gate](https://forum.digikey.com/t/a-mosfet-model-of-a-nand-gate/13998)
 
