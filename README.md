# Hierarchical-Design-Formal-Verification
This repository contains a comprehensive project focused on hierarchical design and formal verification techniques essential for complex circuit development.



## Introduction

This project focuses on the essential concepts of hierarchical design and formal verification techniques required for complex circuit design. The primary objective is to design a two-input AND gate using NAND and inverter gates, implement its layout, and perform various verification processes to ensure its correctness.

## Theory

In digital circuit design, **hierarchical design** involves building complex systems by integrating simpler sub-modules. This approach enhances manageability and scalability. **Formal verification** is a crucial step in chip design to ensure that the circuit performs its intended function correctly. Given the complexity of modern chips, functional verification through simulation is essential before physical implementation.

## Implementation Steps

1. **Design a Two-Input AND Gate Schematic Using NAND and Inverter Symbols**

   - **Schematic Creation**: Utilize NAND gates and inverters to construct the AND gate. Recall that an AND gate can be implemented by inverting the output of a NAND gate.

2. **Design a NAND Gate Layout**

   - **Transistor-Level Design**: Create the physical layout of the NAND gate, defining the arrangement of transistors and connections.

3. **Perform DRC and LVS Checks on the NAND Gate Layout**

   - **Design Rule Check (DRC)**: Ensure the layout adheres to manufacturing constraints.
   - **Layout Versus Schematic (LVS) Check**: Verify that the layout matches the schematic design.

4. **Combine the NAND Gate Layout and the Inverter Layout to Create an AND Gate Layout**

   - **Hierarchical Layout Design**: Integrate the previously designed NAND gate and inverter layouts to form the AND gate.

5. **Perform DRC and LVS Checks on the AND Gate Layout**

   - **Verification**: Confirm that the combined AND gate layout complies with design rules and corresponds accurately to the schematic.

6. **Perform Equivalence Checking on the AND Gate Layout**

   - **Functional Verification**: Use formal methods to ensure the implemented layout functions as an AND gate.

7. **Perform Schematic Simulations for Input Transitions**

   - **Simulation Scenarios**: Analyze the AND gate's response to input transitions: 00 → 11, 01 → 11, and 10 → 11.
   - **Timing Analysis**: Measure propagation delays and observe output behavior.

8. **Calculate Rising and Falling Propagation Delays**

   - **SPICE Netlist Analysis**: Utilize SPICE simulations to determine the propagation delays for rising and falling edges, providing insight into the gate's performance.

## Conclusion

Through this project, we developed a two-input AND gate from fundamental components, analyzed its functionality, and evaluated its performance metrics, including propagation delays and power consumption. Key findings include:

- **Transistor Sizing**: Increasing transistor width reduces propagation delays but increases power consumption.
- **Load Capacitance**: Higher load capacitance leads to increased power consumption and propagation delays.

This hands-on experience underscores the importance of hierarchical design and formal verification in creating reliable and efficient digital circuits.


