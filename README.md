# DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING
Day-1:Inception of open-source EDA, OpenLANE and Sky130 PDK

  1.How to talk to computers

  a)Introduction to QFN-48 Package, chip, pads, core, die and IPs

ARDUINO microcontroller board has microprocessor connected to the peripherals. Pads, core and die are few components in it. 
![image](https://github.com/fsheniha/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/89065478/a97f16f8-8e0e-41c2-9234-3f882c178b7c)

RISC -V Soc is an example of the processor with components shown in below picture
![image](https://github.com/fsheniha/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/89065478/a59041a4-5f5a-45f7-a420-c84a2adfe54a)

  b) Introduction to RISC-V
Chip is connected to external pins with wires
 ![image](https://github.com/fsheniha/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/89065478/fd9425ed-0ef1-4ff8-852e-7327a8be3ce5)

  c)From software applications to hardware
High level language is converted to assembly level language by compiler. Assembler converts assembly level language to machine level language.
 ![image](https://github.com/fsheniha/DIGITAL-VLSI-SOC-DESIGN-AND-PLANNING/assets/89065478/2b14643e-e4c2-4227-8d10-1ee30d7f5cc0)

2. Soc Design and Openlane
   
		a)Introduction to all components of open-source digital ASIC design

		b)Simplified RTL2GDS flow

		C)Introduction to Openlane and strive chipsets

		d)Introduction to openlane detailed ASIC design flow

	3.Get familiar to open-source EDA tools
   
		a)Openlae Directory structure in detail

		b)Design preparation step

		c)Review files after design prep and run synthesis

		d)Openlane project git link description

		e)Steps to characterize synthesis results

II. Good floor planning considerations

	1. Chip floor planning consideration
 
		a)Utilization factor and aspect ratio
  
		b)Concept of preplaced cells
  
		c)Decoupling capacitors
  
		d)Powerplanning
  
		e)Pinplacement and logical cell placement blockage
  
		f)Steps to run floorplan using openlane
  
		g)Review floorplan files and steps to view floorplan
  
		h)Review floor layout in Magic
  
	2.Library building and placement
 
		a)Netlist building and initial place design
  
		b)Optimize placement using estimated wire length and capacitance
  
		c)Final placement optimization
  
		d)Need for libraries and characterization
  
		e)Congestion aware placement using Replace
  
	3. Cell design and characterization flows
 
		a)Inputs for cell design flow
  
		b)Circuit design steps
  
		c)Layout design steps
  
		d)Typical characterization flow
  
	4. General timing characterization parameters
 
		a)Timing threshold definitions
  
		b)Propagation delay and transition time
  Day-3: Design Library cell using Magic Layout and NGSPICE characterization
	1.Labs for CMOS inverter ngspice simulations
		a)IO placer revision
		b)SPICE deck creation for CMOS inverter
c)SPICE simulation lab for CMOS inverter
d)Switching threshold vm
e)Static and dynamic simulation  of CMOS inverter
f)Lab steps to gitclone vsdsd cell design
2. Inception of layout CMOS fabrication process
	a)create active regions
	b)formation of N-well and P-well
formation of gate terminal
lightly doped drain formation
source and drain formation
local interconnect formation
higher level metal formation
lab introduction to sky 130 basic layers layout and LEF using inverter
lab steps to create std cell layout and extract spice netlist


o	Sky130 Tech File Labs
	Lab steps to create final SPICE deck using Sky130 tech
	Lab steps to characterize inverter using sky130 model files
	Lab introduction to Magic tool options and DRC rules
	Lab introduction to Sky130 pdk's and steps to download labs
	Lab introduction to Magic and steps to load Sky130 tech-rules
	Lab exercise to fix poly.9 error in Sky130 tech-file
	Lab exercise to implement poly resistor spacing to diff and tap
	Lab challenge exercise to describe DRC error as geometrical construct
	Lab challenge to find missing or incorrect rules and fix them
•	Day 4 - Pre-layout timing analysis and importance of good clock tree
o	Timing modeling using delay tables
	Lab steps to convert grid info to track info
	Lab steps to convert magic layout to std cell LEF
	Introduction to timing libs and steps to include new cell in synthesis
	Introduction to delay tables
	Delay table usage Part 1
	Delay table usage Part 2
	Lab steps to configure synthesis settings to fix slack and include vsdinv
o	Timing analysis with ideal clocks using openSTA
	Setup timing analysis and introduction to flip-flop setup time
	Introduction to clock jitter and uncertainty
	Lab steps to configure OpenSTA for post-synth timing analysis
	Lab steps to optimize synthesis to reduce setup violations
	Lab steps to do basic timing ECO
o	Clock tree synthesis TritonCTS and signal integrity
	Clock tree routing and buffering using H-Tree algorithm
	Crosstalk and clock net shielding
	Lab steps to run CTS using TritonCTS
	Lab steps to verify CTS runs
o	Timing analysis with real clock using openSTA
	Setup timing analysis using real clocks
	Hold timing analysis using real clocks
	Lab steps to analyze timing with real clocks using OpenSTA
	Lab steps to execute OpenSTA with right timing libraries and CTS assignment
	Lab steps to observe impact of bigger CTS buffers on setup and hold timing
•	Day 5 -Final step for RTL2GDS using tritinRoute and openSTA
o	Routing and design rule check (DRC)
	Introduction to Maze Routing Ã�Â� LeeÃ�Â�s algorithm
	LeeÃ�Â�s Algorithm conclusion
	Design Rule Check
o	Power Distribution Network and routing
	Lab steps to build power distribution network
	Lab steps from power straps to std cell power
	Basics of global and detail routing and configure TritonRoute
o	TritonRoute Features
	TritonRoute feature 1 - Honors pre-processed route guides
	TritonRoute Feature2 & 3 - Inter-guide connectivity and intra- & inter-layer routing
	TritonRoute method to handle connectivity
	Routing topology algorithm and final files list post-route

