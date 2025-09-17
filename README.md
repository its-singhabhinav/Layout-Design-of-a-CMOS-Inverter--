# Layout Design of a CMOS Inverter
## It consists of the simulation of a CMOS inverter and its layout design. It might be helpful for one who wants to start with Cadence Virtuoso suite.
## Introduction:
Cadence Virtuoso suite is used to design and simulate the CMOS Inverter. The CMOS inverter has one pmos and one nmos; its gate terminals are connected to each other; source of the pmos is connected to vdd and source of the nmos is connected to ground; both the drains are connected to each other and the output is taken at this terminal. The diagramatic representation of the CMOS Inverter is shown in Fig. 1.

<p align="center">
<img src="https://user-images.githubusercontent.com/73669849/206872969-310954d0-14a0-4432-8b9b-8269a655ce2b.png" width="200" height="300">
</p>
<p align = "center">
Fig. 1 - CMOS Inverter
</p>
  
## Creating a New Library and Cell View:
  
First step is to open the Cadence Virtuoso suite and to create a new library.

<p align="center">
<img src="https://user-images.githubusercontent.com/73669849/206895372-3374e0ab-a999-4e0b-ab41-e747d3973921.JPG" width="500" height="200">
</p>
<p align = "center">
Fig. 2 - Cadence Homepage
</p>

New library is created by clicking **File --> New --> Library**

The library name **inverter** is given with a technology file setting as **Attach to an existing technology file**

<p align="center">
<img src="https://user-images.githubusercontent.com/73669849/206895452-0e26c625-0ee4-45b4-8d17-bdd959d55d80.JPG" width="300" height="200">
</p>
<p align = "center">
Fig. 3 - Library Creation
</p>

After pressing okay in Fig. 3, a small window shown in fig. 4 opens. In that window, press **ts018_scl_prim**.

<p align="center">
<img src="https://user-images.githubusercontent.com/73669849/206895518-58bcd660-2c4e-425d-a83a-12aceeedd3cd.JPG" width="300" height="200">
</p>
<p align = "center">
Fig. 4 - Attach Library to technology Library
</p>

Now, again press **file --> new --> cell view**; the window shown in fig. 5 opens. select the **library file** name **inverter**, create a **cell name** as **inverter**, set **view** as **schematic** and **type** as **schematic** as shown in fig. 6.  

<p align="center">
<img src="https://user-images.githubusercontent.com/73669849/206895659-5da3d482-e22e-489f-8315-0284f6da5544.JPG" width="300" height="250">
</p>
<p align = "center">
Fig. 5 - Cell View New window
</p>

<p align="center">
<img src="https://user-images.githubusercontent.com/73669849/206895669-73197bd7-3c6f-44f8-babf-afcacae18e5e.JPG" width="300" height="250">
</p>
<p align = "center">
Fig. 6 - Cell View New window parameters
</p>

## Design of a CMOS Inverter Schematic:

The interface as shown in fig. 7 opens to design a CMOS Inverter.

<p align="center">
<img src="https://user-images.githubusercontent.com/73669849/206895813-a575d452-4528-4d28-aa97-26836a5f1fac.JPG" width="600" height="400">
</p>
<p align = "center">
Fig. 7 - Interface to design CMOS Inverter
</p>

Transistors or any other components are added into the design by using **add instance** or **pressing a shortcut key "I"**. The window shown in fig. 8 opens.

<p align="center">
<img src="https://user-images.githubusercontent.com/73669849/206896657-a950567b-0a37-435d-9437-e4316deaff00.JPG" width="300" height="250">
</p>
<p align = "center">
Fig. 8 - Add Instance
</p>

The pmos is selected by clicking browse; selecting **library as "ts_018_scl_prim"**; **cell as "pmos_18"**; and **view as "symbol"** as shown in fig. 9.

<p align="center">
<img src="https://user-images.githubusercontent.com/73669849/206896719-6ee076e0-8de6-45f4-a4d7-e9eed0c205e1.JPG" width="600" height="400">
</p>
<p align = "center">
Fig. 9 - PMOS Selection
</p>

The PMOS is placed in the design interface by clicking on the black window as shown in fig. 10.

<p align="center">
<img src="https://user-images.githubusercontent.com/73669849/206897739-eef3f8c4-b338-457a-81e1-1ab5f73f16a7.JPG" width="200" height="200">
</p>
<p align = "center">
Fig. 10 - PMOS in Design Interface
</p>

Similarly, NMOS is placed in the inteface and the design is completed with wires as shown in fig. 11.

<p align="center">
<img src="https://user-images.githubusercontent.com/73669849/206898434-699fe521-a5bd-4421-bbe9-d39180e2478a.JPG" width="300" height="300">
</p>
<p align = "center">
Fig. 11 - CMOS Inverter Schematic
</p>

The input, output, vdd and gnd pins are connected by clicking the pin symbol ![12  pin symbol](https://user-images.githubusercontent.com/73669849/206898676-9ed92932-1e32-4ef8-856f-6bcd1933eb11.JPG). The window as shown in fig. 12 opens. The direction is input for input pins; output for output pins; and input output for both vdd and gnd. Each pins are created using the cerate pin window; dragged to the right place and clicked to get connected.

<p align="center">
<img src="https://user-images.githubusercontent.com/73669849/206898711-5173b765-5757-4308-8798-9e5937b8dbc3.JPG" width="300" height="300">
</p>
<p align = "center">
Fig. 12 - Create pin window
</p>

Once the Above steps are completed, the complete schematic diagram as shown in fig. 13 is obtained.

<p align="center">
<img src="https://user-images.githubusercontent.com/73669849/206899016-7a229371-10d1-45da-b784-28c1dd57afc0.JPG" width="300" height="300">
</p>
<p align = "center">
Fig. 13 - Complete Schematic Diagram
</p>

The cell view is created by **create --> cellview --> from cellview**, the window as shown in fig. 14 opens; click ok in it. 

<p align="center">
<img src="https://user-images.githubusercontent.com/73669849/206899953-01e12335-673f-4da6-9d30-79ac3fa89401.JPG" width="300" height="300">
</p>
<p align = "center">
Fig. 14 - Cellview from cellview
</p>

The **symbol generation options** window opens where the position of the pins are assigned. The positions as shown in fig. 15 are given and click ok.

<p align="center">
<img src="https://user-images.githubusercontent.com/73669849/206900149-ff72ea66-b05b-467f-9b3f-b954f800d9de.JPG" width="300" height="250">
</p>
<p align = "center">
Fig. 15 - symbol generation options
</p>

The symbol as shown in fig. 16 is created.

<p align="center">
<img src="https://user-images.githubusercontent.com/73669849/206900218-ea4c524f-fb59-44e8-89b8-27a2bbf14b72.JPG" width="400" height="250">
</p>
<p align = "center">
Fig. 16 - CMOS Inverter Symbol
</p>

## Simulation of a CMOS Inverter:

A new window is created using **File --> new --> cellview**. In the cellview window the **library** is **Inverter** which is created previously; the **cell name** is **Inverter_test**; **view** is **schematic**; and **type** is **schematic**. The symbol created is added into the design interface using **add instance --> library is Inverter --> cell is Inverter --> view is symbol**; the power supply is added using **add instance --> library is analoglib --> cell is vdc --> view is symbol**; the ground is added using **add instance --> library is analoglib --> cell is gnd --> view is symbol**; and the pulse input to check the functionality of the CMOS inverter is added using **add instance --> library is analoglib --> cell is vpulse --> view is symbol**. The necessary connections are given as shown in fig. 17; the value of vdc (vpulse) is adjusted in the properties by clicking on the vdc (vpulse) and pressing "q". The value of vdc is 1.8 V and vpulse is 1.8 V with time period of 20 ns and pulse width of 10 ns. The pins are connected at the input and output sides to monitor the responses. The complete schematic is shown in fig. 17.

<p align="center">
<img src="https://user-images.githubusercontent.com/73669849/206902920-a63f47c5-0945-4054-8278-04195c407c6c.JPG" width="400" height="250">
</p>
<p align = "center">
Fig. 17 - Inverter Simulation Setup
</p>

After designing the above design for simulation purpose, click **Launch --> ADE L**. The window as shown in fig. 18 opens.

<p align="center">
<img src="https://user-images.githubusercontent.com/73669849/206903384-3e69ec88-88d0-41be-950f-b8c5e504b838.JPG" width="400" height="250">
</p>
<p align = "center">
Fig. 18 - Simulation Window
</p>

click **Setup --> Model Libraries**, the window as shown in fig. 19 opens. Choose the model file as the file path of the **ts18sl_sci.lib** and section as **tt_18**.

<p align="center">
<img src="https://user-images.githubusercontent.com/73669849/206903630-7bd9b56b-86fe-4cde-a5f4-c6cac209a957.JPG" width="400" height="250">
</p>
<p align = "center">
Fig. 19 - Model Library Window
</p>

Once the model library setting is over, click **Analyses --> choose** in the simulation window. The window shown in fig. 20 opens. Select **analyses** as **trans** with **stop time** as **20 ns** and **accuarcy defaults** as **moderate**.

<p align="center">
<img src="https://user-images.githubusercontent.com/73669849/206903980-b75d70e9-2d9a-4309-bd11-ccbc103c0d07.JPG" width="400" height="500">
</p>
<p align = "center">
Fig. 20 - Choose Analyses
</p>

Then click **Outputs --> to be plotted --> select on design**. Further, the cursor moves to the design where we need to select the input and output pins. Now, press the green play button in the layout window to simulate the design. while the simulation is running, the window as shown in the fig. 21 opens.

<p align="center">
<img src="https://user-images.githubusercontent.com/73669849/206904429-83010080-b469-4df1-80b2-725ab9ec24a4.JPG" width="400" height="500">
</p>
<p align = "center">
Fig. 21 - Simualtion running window
</p>

Once the simulation is over, the simulation output window as shown in fig. 22 opens. It is clear from the output that the output is inverted with respect to the input. 

<p align="center">
<img src="https://user-images.githubusercontent.com/73669849/206905544-61868526-42b0-462f-a857-7287550bbca6.JPG" width="700" height="500">
</p>
<p align = "center">
Fig. 22 - Simualtion Output window
</p>

Once the Simulation output is obtained as expected, the layout design of a CMOS Inverter will be done.

## Layout Design of a CMOS inverter
In the Design Schematic window, click **Launch --> Layout XL**. The startup window as shown in fig. 23 opens. **Layout** option as **create new** and **Configuration** as **Automatic**.

<p align="center">
<img src="https://user-images.githubusercontent.com/73669849/206905913-f45ee99e-5380-49b7-96c1-2449bddd74dd.JPG" width="250" height="250">
</p>
<p align = "center">
Fig. 23 - Layout Startup option
</p>

The Layout Newfile as shown in fig. 24 opens. **Library** as **Inverter**; **Cell** as **Inverter**; **view** as **layout**; and **Type** as **Layout**.

<p align="center">
<img src="https://user-images.githubusercontent.com/73669849/206906289-37b2ae90-3314-4f8a-aac8-31ea07bbb6b9.JPG" width="250" height="250">
</p>
<p align = "center">
Fig. 24 - Layout NewFile option
</p>

The layout Suite as shown in fig. 25 opens.

<p align="center">
<img src="https://user-images.githubusercontent.com/73669849/206906547-5140727c-6ed8-4540-b524-7f5363c56e13.JPG" width="700" height="500">
</p>
<p align = "center">
Fig. 25 - Layout Suite
</p>

In the layout suite, Click **Connectivity --> Generate --> All from source**. The generate layout window as shown in fig. 26 opens. Uncheck the PR Boundary option and click ok in it.

<p align="center">
<img src="https://user-images.githubusercontent.com/73669849/207061578-b92187cd-497e-4646-bdb5-afe7085292b4.JPG" width="400" height="500">
</p>
<p align = "center">
Fig. 26 - Generate Layout 
</p>

The layout of the CMOS Inverter without connections as shown in fig. 27 is created. The PMOS transistor layout is in the top; NMOS transistor is in the bottom; and four blue colour pins at the leftmost top indicates the four pins of the CMOS Inverter.

<p align="center">
<img src="https://user-images.githubusercontent.com/73669849/207062502-cd144f75-7994-4674-abb0-ec7c0eed5c0f.JPG" width="300" height="400">
</p>
<p align = "center">
Fig. 27 - Layout of the CMOS Inverter without connections 
</p>

The distance between the PMOS and NMOS is 0.44 scale (Similarly based on the design rules for a particular technology node the distance between each components vary); all the pins are dragged and placed at the right place; all the necessary connections with proper material (metal layer 1, metal layer 2, polysilicon etc) are made. The final layout of the CMOS Inverter with proper connections as shown in fig. 28 is completed.

<p align="center">
<img src="https://user-images.githubusercontent.com/73669849/207065317-a566f8da-5f87-4ad4-be32-2c77b2d7aeef.JPG" width="300" height="300">
</p>
<p align = "center">
Fig. 28 - Layout of the CMOS Inverter 
</p>

The label is given to all the four terminals by clicking **create --> Label**. The **label pattern** as **vdd gdn in out** and **Select layer** as **M1 layer** are given as shown in the fig. 29. The labels are properly mapped with the terminals in the layout.

<p align="center">
<img src="https://user-images.githubusercontent.com/73669849/207073714-7190564a-7021-4b3d-8ecb-c064061e25f8.JPG" width="300" height="400">
</p>
<p align = "center">
Fig. 29 - Label Creation
</p>


## DRC and LVS Check
Now, the layout is checked with the Design rules of a particular technology node considered. The clean report is generated to procedd further. Layout Suite runs the **Design Rule Check** by clicking **Calibre --> Run nmDRC**. The DRC file path is given in the calibre interaction window and run DRC is clicked as shown in fig. 30.

<p align="center">
<img src="https://user-images.githubusercontent.com/73669849/207068437-4970a524-621b-4915-962c-0e1401b394e0.JPG" width="700" height="450">
</p>
<p align = "center">
Fig. 30 - Calibre Interaction Window 
</p>

Once the DRC is clean, the Layout Versus Schematic (LVS) is checked by clicking **Calibre --> Run nmLVS**. The LVS file path is given in the calibre interaction window and run LVS is clicked as similar to the DRC. The LVS is clean, when the layout and the schematic are similar to each other. 

## Conclusion:
Thus, the CMOS inverter is designed and simulated. The layout of the same also completed with a clean DRC and LVS.


