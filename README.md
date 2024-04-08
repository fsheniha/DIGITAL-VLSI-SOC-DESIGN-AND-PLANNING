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
