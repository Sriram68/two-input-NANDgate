   # Two-input NAND gate design
This repository presents the design of Two input NAND gate using Synopsis Custom Compiler on 28nm CMOS Tecgnology
# Table of contents
[Introduction](https://github.com/Sriram68/two-input-NANDgate/blob/main)

[Reference cicuit diagram]()

[Circuit details]()

[Truth table]()

[Tools used]()

[Circuit diagram in Synopsys Custom Compiler]()

[Netlists]()

[Plots]()

[Author]()

[Acknowledgements]()

[References]()

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
 • Synopsys Custom Compiler:
 The Synopsys Custom Compiler™ design environment is a modern solution for full-custom analog, custom digital, and mixed-signal IC design. As the heart of the Synopsys Custom Design Platform, Custom Compiler provides design entry, simulation management and analysis, and custom layout editing features. This tool was used to design the circuit on a transistor level.

• Synopsys Primewave:
 PrimeWave™ Design Environment is a comprehensive and flexible environment for simulation setup and analysis of analog, RF, mixed-signal design, custom-digital and memory designs within the Synopsys Custom Design Platform. This tool helped in various types of simulations of the above designed circuit.

• Synopsys 28nm PDK:
 The Synopsys 28nm Process Design Kit(PDK) was used in creation and simulation of the above designed circuit
 # Circuit diagram in Synopsys Custom Compiler
 
