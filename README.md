# EXP NO:02 Design-Implementation-of-Full-Custom-2-1-MUX-using-Cadence-EDA-Tools

## Aim:
To design and implement a 2:1 multiplexer (MUX) circuit using Cadence EDA tools, analyse its functionality and performance, and understand the principles of digital logic design, including schematic creation, layout design, and simulation.

## Tools Required:

•	Personal Computer

•	Cadence Virtuoso Software


## Circuit Diagram:

![IMG-20241115-WA0003](https://github.com/user-attachments/assets/36ab9035-708c-4d5b-91be-eb0c35569e7c)


## SCHEMATIC SIMULATION:

PROCEDURE FOR CREATING THE SCHEMATIC SIMULATION
Commands to get into Cadence
1.	Right Click and open the terminal window
2.	Type the following commands as follows and press enter.
•	csh
•	source /cadence/install/cshrc
•	virtuoso 
Procedure for Schematic simulation using Cadence

1.	Now two windows must open i)virtuoso/command interpreter window ii)”Whats New…”
2.	Close the 2nd window
3.	Use 1st window i.e virtuoso window(CIW) for further processing.
i.	Create a New Library
ii.	Create Schematic Cell view.
iii.	Create the Symbol for schematic Cell view.
iv.	Create the test Cell view.
v.	Analog simulation by spectre


i)	Procedure for Creating New Library.

•	File –New – Library

•	Name : Give name for ur library Ex: VLSILAB_EXP_1

•	Enable Attach to an existing technology library, Click OK

•	Attach the library to the technology library gpdk045.Click OK
ii)	Create Schematic Cell view.
•	Go to 1st window i.e virtuoso(CIW)

•	File-New-Cell view

•	Setup the new file form
	  Library: Select the one you a created.
	  Cell : Give the experiment name Ex: Inverter View_Schematic
	  Type: Schematic press OK
•	Add the required components from the libraries and make the connections.

• Go to instance fixed menu or use shortcut key “I” from keypad to go instances

•	Click on browse. This opens the library browser

•	Now select the appropriate library for components like 
• Gpdk45 ------------------------nmos1v,  pmos1v

• Create Input and Output pins

•	Make the connections by using fixed narrow wire key

•	Click Check and Save button
![Screenshot 2024-10-18 104221](https://github.com/user-attachments/assets/b6bef034-29af-46f5-a600-ccbc39258e53)



 
iii)	Creating the Symbol for schematic Cell view

•	In the schematic window, execute 

•	Create – Cell view – From Cell view

•	The cell view from cell view window appears

•	Check Lib Name, Cell Name, From View name must be schematic Press ok

•	Now Symbol generation form appears. Click Ok If No changes required

•	A new window with with default symbol is created.

•	Edit the symbol if you want to give actual symbol shape else continue.

•	Execute Create-Cell view-from cell view

•	Library Name and Cell Name must be same which you have used for schematic. Press OK

•	Check for the position of pin side.Prss OK

•	Edit for the shape by Create-Shape-Choose required options to edit.

 ![Screenshot 2024-10-18 104159](https://github.com/user-attachments/assets/ebd979e5-a3fa-431f-8378-e0620f38ed57)



iv)	Creating the new test cell view

•	Go to CIW window, Execute File-New-Cell view

•	Setup the new file form

•	Library: Select the one you created.

•	Cell: Cell name must be different from the name used in schematic cell view. Ex: Inverter_test

•	View: Schematic

•	Type: Schematic press OK

•	Follow the step 3(ii)  to make the required connections
 ![Screenshot 2024-10-18 104134](https://github.com/user-attachments/assets/4c7f57c5-63ff-4ce2-9e4a-8932561c7a6e)


## Analog simulation by SPECTRE.
•	In test cell view window

•	Launch – ADE L(Analog Design Environment)

•	Execute Setup—Simulation/directory/Host A new window opens

•	Set the simulation window to spectre and click ok

•	Execute Analysis – Choose. A window opens.

•	Select the type and set the specifications and press OK

•	Execute Output s—to be plotted – Select on Schematic

•	Then Select the INPUT WIRE(Vin ) and OUTPUT WIRE(Vout) from your test Schematic using mouse

•	Execute Simulation -- Net list and Run
![Screenshot 2024-11-16 183632](https://github.com/user-attachments/assets/192fa63f-dcfa-4fe3-a146-ac0c352fbb43)



## For Transient Analysis Settings 
![Screenshot 2024-11-16 182843](https://github.com/user-attachments/assets/07980dfb-f24b-4028-ba28-fdd11449f8a5)


 ## Output
 ![Screenshot 2024-10-18 104840](https://github.com/user-attachments/assets/0cb606c5-fc95-4029-b503-e565f595424b)




 

## Result:
1.	The experiment successfully demonstrated the design and implementation of a 2:1 MUX using Cadence EDA tools. 
2.	The successful verification through schematic, layout, and simulation underscores the effectiveness of using Cadence EDA tools for digital circuit design.
