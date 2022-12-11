# Layout Design of a CMOS Inverter
## It consists of the simulation of a CMOS inverter and its layout design. It might be helpful for one who wants to start with Cadence Virtuoso suite.

<p align="justify"> &emsp; Cadence Virtuoso suite is used to design and simulate the CMOS Inverter. The CMOS inverter has one pmos and one nmos; its gate terminals are connected to each other; source of the pmos is connected to vdd and source of the nmos is connected to ground; both the drains are connected to each other and the output is taken at this terminal. The diagramatic representation of the CMOS Inverter is shown in Fig. 1.</p>

<p align="center">
<img src="https://user-images.githubusercontent.com/73669849/206872969-310954d0-14a0-4432-8b9b-8269a655ce2b.png" width="200" height="300">
</p>
<p align = "center">
Fig. 1 - CMOS Inverter
</p>

<p align="justify"> &emsp;
  
### Creating a New Library and Cell View
  
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

After pressing okay in Fig. 3, a small window shown in fig. 4 opens. In that window, press **ts018_scl_prim** \.

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

### Design of a CMOS Inverter Schematic

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

The 
