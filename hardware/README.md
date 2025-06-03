# **Schematic**

<div align="center">
    <a href="resources/unit_sch_v_0_1_0_ue0087_tps61023_boost.pdf">
        <img src="resources/img/Schematics_icon.jpg?raw=false" width="500px"><br/> 
        Schematics (PDF)
    </a>
</div>

---

# **Pinout**

<div align="center">
    <a href="#">
        <img src="resources/unit_pinout_ue0087_tps61023_boost_v_1_0_0_en.jpg" width="450px"><br/> 
        Pinout Diagram
    </a>
</div>

---

## **Pin Descriptions**

<div align="center">

| **Pin Group**  | **Label**     | **Function**                                                               |
|----------------|---------------|----------------------------------------------------------------------------|
| **Input**      | VIN           | Positive input voltage. Connect your supply’s positive terminal here.     |
| **Input**      | GND Input     | Ground reference for input. Connect the supply’s negative terminal here.  |
| **Output**     | VOUT          | Boosted positive output. Provides regulated higher voltage.               |
| **Output**     | GND Output    | Output ground. Connect to your load's ground or system ground.            |
| **Adjustment** | POT           | Multi-turn potentiometer to set the output voltage precisely.             |

</div>

---

# **Board Topology**

<div align="center">
    <img src="resources/unit_topology_v_0_1_0_ue0087_tps61023_boost.png?raw=false" width="500px"><br/><br/>

| **Reference** | **Component**                 | **Description**                                     |
|---------------|-------------------------------|-----------------------------------------------------|
| **U1**        | TPS61023                      | Main boost converter IC by Texas Instruments        |
| **RV1**       | Potentiometer (multi-turn)    | Allows precise adjustment of the output voltage     |
| **L1**        | Power Indicator LED           | Lights up when input voltage is present             |
| **F1**        | Resettable Fuse (1 A)         | Protects the circuit from overcurrent conditions    |
| **JP1**       | VIN+ Pad                      | Positive terminal for power supply input            |
| **JP2**       | VIN– Pad                      | Ground terminal for power supply input              |
| **JP3**       | VOUT+ Pad                     | Positive terminal for boosted output                |
| **JP4**       | VOUT– Pad                     | Ground terminal for boosted output                  |

</div>

---

# **Dimensions**

<div align="center">
    <a href="#">
        <img src="resources/unit_dimension_v_0_1_0_ue0087_tps61023_boost.png" width="600px"><br/>
        Mechanical Dimensions
    </a>
</div>
