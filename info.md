# Clap circuit
This circuit allows you to make Electrical home equipments will work on the basis of clapping sound. When sensor(mic) sense clapping sound and count specific number of  claps, it will generate output and by using this we can control on/off mode of equipment. It's useful for IOTs project. Here we are using Single Side copper clad board PCB([Printed Circuit Board](https://en.wikipedia.org/wiki/Printed_circuit_board)). I used [Kicad](https://www.kicad.org/) for designing the pcb layout.

## Required Components

* ### MIC:
	It's a device which can convert sound signal into electrical signal. Here we are using [dynamic MIC](https://en.wikipedia.org/wiki/Microphone#Dynamic) which is work on the principle of electromagnetic induction.

* ### Operational Amplifier:
	Basicly it is only comparing two signals value(V or I), as the name indicates, it can perform many operation(like: Addition, Subtraction, integration, diffrentiation, comparision ,ADC,DAC etc). Here we are using it for analog signal to digital signal converter. We are using simple single core monolithic ic [LM741](https://en.wikipedia.org/wiki/Operational_amplifier) which have fundamental operation.

* ### Decade Counter:
	It's also known as [Johnson counter](https://en.wikipedia.org/wiki/Ring_counter#Johnson_counter). It's used fpr low range counting application(normally 0 to 10). It's a +ve edge triggering and 16 pin IC.
  
  
## Schematic Design
![image of schematic](Schematic_diagram.JPG)

## PCB Layout Design
* ### Circuit Layaout
![image of layout](PCB_layput_of_Circuit.JPG)

* ### 3D layout
![image of 3d layout](PCB_Layout_Footprint_in3D.JPG)
