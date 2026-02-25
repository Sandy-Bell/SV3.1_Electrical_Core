# To-Do List

Find everything that needs done in this file. 

1. Task management
    1. Create detailed action plan, use Gantt chart.
    2. Create subtasks.
    3. Assign owners to tasks.
    4. Add those tasks here if possible
2. Create more detailed function requirements. 
3. Create Dependency Matrix


# Development To-Do

 1. Control System - Ezra, Sandy, Alfie, Ben
	1. ~~MCU Selection~~
			1. ~~Assess pin requirements - Ben~~
				1. ~~Assess I/O interaction with other systems~~
				2. ~~Assess suitable communication protocols between systems~~
			2. ~~Research power filters~~
				- ~~How do other MCU's do it?~~
			3. ~~Price  - Ben~~
				-~~Delivery~~ 
				- ~~Board cost - 5 for £5 pre-assembled~~
				- ~~Assembly cost~~
			4. ~~Assess power requirements~~
			5. ~~Assess RTOS compatibility~~
	2. Assess Software Architecture - Owen
		1. ~~RTOS vs Bare Meta - RTOS~~
		2. General file structure
		3. Set consistent coding guidelines (MRSA standard)
	3. MCU coding - everyone
		1. Manual Thruster algorithm
			1. Feedback required?
    	4. Reading and responding to state inputs
	5. KiCAD schematic of whole system. 
	6. ~~Assess Board Level Components~~
		1. ~~LED component~~
		2. ~~Headers/ Interfaces~~
			- ~~USB - Jetson~~
			- ~~Assess Physical Layout Impact~~
			- ~~Scalability - extra pins~~

2. Diagnostic System - Sandy, Alfie, Michael, Eli
	1. Assess what to measure - Eli - FUNCTIONAL REQUIREMENTS
	2. Asses How to Measure it - Eli
		1. BMS - Sandy
			1. Battery visibility 
		2. JETSON - Eli
			1. GPS data?
			2. JETSON health monitoring and mission data
		3. Sensors required - Eli
			1. Evaluate price
			2. Evaluate precision
			3. Compare
	3. Packet Structure - Michael
		1. Validation of data packets
	4. Radio system - Michael
		1. Assess Legality - UK & Norway
		2. Frequency
		3. Exact radios to use, evaluating cost and other variables
	5. Mission UI wireframe - Alfie
		- How to display the diagnostic data in an approachable way?
	6. Diagnostic MCU board - Alfie, Michael
		1. Assess pin requirements
		2. Assess communication protocols
		3. Could use a simple Arduino
	7. Create KiCAD Schematic
	8. Code Diagnostic MCU
		1. Initialise
		2. Loop 
			1. Poll sensors
			2. Structure packets
			3. Send to shore
		3. End 

4. Custom ESC - Ben

5. Physical Layouting - Sandy
	1. Server racks idea
	2. Leak Sensors
	3. ESCS
		1. Seperate box with cooling and multiple inside
	4. Explore DIN Rail idea
	5. Doige connector orange and grey for power cables and rails
	6. Mounting standard
		1. current 20x20 aluminium extrusions -  better fitting would be nicer 
		2. shear/ tension forces
			- clamps
6. ~~Get engine room free - Owen~~

