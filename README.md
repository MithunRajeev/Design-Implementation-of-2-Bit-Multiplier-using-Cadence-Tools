# Ex No: 06 - Design & Implementation of 2-Bit Multiplier Using Cadence Virtuoso
## MITHUNRAJEEV V
## REG NO:212223060159

## Aim
The aim is to design and implement a **2-bit Multiplier** using **Cadence Virtuoso** and verify its functionality through transient analysis simulation.

## Tools Required
### Cadence Virtuoso Suite
- **Virtuoso Schematic Editor** (for circuit design)
- **Spectre Simulator** (for circuit simulation)

### Process Design Kit (PDK)
- CMOS technology library

### Computer System
- Minimum **4GB RAM** and a **multi-core processor**

## Procedure

### 1. Launch Cadence Virtuoso Environment:
- Open the **Cadence Virtuoso** tool and set up the working library.
- Create a new **schematic cell view** for the **2-bit Multiplier** design.

### 2. Schematic Design:
- Select **NMOS and PMOS transistors** from the library.
- Construct the **2-bit Multiplier circuit** using **AND and ADDER logic gates**.
- Connect the inputs (**A1, A0, B1, B0**) and outputs (**P3, P2, P1, P0**) properly.

### 3. Simulation:
- Check the design for **errors** and proceed with simulation.
- Launch the **Analog Design Environment (ADE)**.
- Perform **transient analysis** to verify the multiplication logic.
- Set up **input stimulus** and analyze the **output waveform**.

## Circuit Diagram

![image](https://github.com/user-attachments/assets/a56c4672-c7a5-44a8-908f-860243dc365d)


## Truth Table for 2-Bit Multiplier

![image](https://github.com/user-attachments/assets/fdb01f7d-60c1-4605-8462-c4dd954c5602)


## Schematic Diagram

### Schematicand Symbol of 2-Input AND Gate:

![Screenshot 2025-05-10 160454](https://github.com/user-attachments/assets/7a700f59-c4b4-4006-b791-0a4edf7d1e57)


### Schematicand Symbol of 2-Input EX-OR Gate:

![Screenshot 2025-05-10 160515](https://github.com/user-attachments/assets/880ad1be-e8b3-4111-b2ea-2b2c7eb1fd14)


### Schematic of 2-Bit Multiplier:
![Screenshot 2025-05-21 110341](https://github.com/user-attachments/assets/fbffb998-e0da-4646-b666-941e4ce3288f)




## Output
### Transient Analysis Output:
![anal_exp6](https://github.com/user-attachments/assets/e831fad1-683c-4a2c-8992-2884bed78ff9)
![Screenshot 2025-05-21 110212](https://github.com/user-attachments/assets/e07f480d-8041-4032-a678-ecfacf32a7df)



Run Time : 200ns

## Results
1. Successfully designed the **2-bit Multiplier** schematic using **Cadence Virtuoso**.
2. Performed **transient analysis**, verifying the correct operation of the **Multiplier**.
3. Observed **correct multiplication behavior** in response to input signals.
