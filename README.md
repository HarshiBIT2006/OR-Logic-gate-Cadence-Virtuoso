## OR-Logic-gate-Cadence-Virtuoso
This project presents the design, simulation, and verification of a 2-Input CMOS OR Gate using Cadence Virtuoso. The gate is implemented at the transistor level using Complementary Metal-Oxide-Semiconductor (CMOS) technology. The objective is to design a functional OR gate, verify its logical operation through transient simulations, and validate the layout using physical verification techniques.

Objective
Design a CMOS 2-input OR gate.
Create the transistor-level schematic.
Generate the layout.
Perform transient simulation.
Verify the design using DRC and LVS.
Analyze the output waveform.


Theory- An OR gate is a fundamental digital logic gate that performs the logical OR operation. The output becomes HIGH (logic 1) if at least one input is HIGH. The output is LOW (logic 0) only when both inputs are LOW.
Boolean Expression : Y = A + B


In CMOS implementation, an OR gate is typically realized by designing a NOR gate followed by a CMOS inverter.

Software Used-
Cadence Virtuoso
Virtuoso Schematic Editor
Virtuoso Layout Editor
Spectre Simulator
Assura/Pegasus (for DRC and LVS)


Design Flow
1. Create a new library.
2. Design the NOR gate schematic.
3. Design the CMOS inverter.
4. Connect the NOR output to the inverter input.
5. Perform schematic verification.
6. Create the testbench.
7. Run transient simulation.
8. Observe input and output waveforms.
9. Draw the layout.
10. Run Design Rule Check (DRC).
11. Run Layout Versus Schematic (LVS).
12. Verify successful design implementation.


Simulation- Transient analysis is performed by applying different input combinations to verify the logical functionality.

Expected Output:-
Output is HIGH whenever one or both inputs are HIGH.
Output is LOW only when both inputs are LOW.

Layout Verification-
1. DRC (Design Rule Check)- ✔ No DRC Errors
2. LVS (Layout Versus Schematic)- ✔ LVS Matched

Results-
Successfully designed the CMOS OR gate.
Correct logic functionality verified.
Successful transient simulation.
DRC passed without errors.
LVS matched successfully.

Applications-
Digital Logic Circuits
Arithmetic Logic Units (ALUs)
Microprocessors
Control Systems
Memory Address Decoding
Embedded Systems
Digital Signal Processing

Conclusion-
The CMOS 2-input OR gate was successfully designed, simulated, and verified using Cadence Virtuoso. The transient simulation confirmed the correct OR logic operation for all input combinations, while DRC and LVS verification ensured that the layout is fabrication-ready. This project demonstrates the complete custom IC design flow, from schematic creation to physical verification, using Cadence Virtuoso.

Author- Aditi Bhatnagar

