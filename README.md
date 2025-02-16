# Uneven-Seven-Sided-Dice-Roller-Digital-System-Design-

## Overview

This project implements an **Uneven-Seven-Sided Dice Roller** using digital design techniques. Unlike traditional dice with six sides, this project explores a **7-sided dice roller** with varying probabilities for each outcome. The project was developed as part of the **DSD Capsule** at the **Electrical and Electronics Engineering Department** of Abdullah Gül University.

## Authors

- **Abdullah Rihawi** - [abdullah.rihawi@agu.edu.tr](mailto:abdullah.rihawi@agu.edu.tr)
- **Husein Mohamed Faarah** - [husein.faarah@agu.edu.tr](mailto:husein.faarah@agu.edu.tr)

## Project Description

The **Uneven-Seven-Sided Dice Roller** is an electronic circuit designed to generate **random numbers between 1 and 7** using sequential circuits. The circuit consists of:

- **1-bit Data Generator (Timer)** – Generates the initial random data.
- **Clock1** – A 400Hz clock signal ensuring synchronization.
- **Intermediate Register (R1)** – Temporarily stores generated data.
- **2-bit Full Adder** – Ensures random number addition and prevents overflow.
- **Clock4** – Derived from Clock1 for additional timing synchronization.
- **Output Register (R0)** – Displays the final dice roll result.

## Circuit Components

- **555 Timer IC** – Used for stable oscillations.
- **Arduino Uno** – Generates the clock signals.
- **CMOS Digital Circuits** – For logic operations and state storage.
- **Shift Registers & Flip-Flops** – Ensuring data synchronization.
- **Logic Gates (AND, OR, XOR)** – Implementing arithmetic operations.

## Working Principle

1. A **1-bit data generator** creates random bits.
2. The **clock signal (CLK1)** ensures data is processed at consistent intervals.
3. The **intermediate register** captures and holds the data until processed.
4. The **2-bit full adder** sums the values while handling overflow (ensuring numbers remain in the 1-7 range).
5. The **output register** stores and displays the final result.

## Simulation & Results

- The circuit was simulated using **digital logic simulation tools**.
- The probability of each number was analyzed through **timing diagrams**.
- The final output was successfully mapped to the **7-sided dice face**.

## Applications

- **Board games** requiring non-standard dice.
- **Educational tools** for probability and random number generation.
- **Randomized decision-making tools**.

## Conclusion

This project successfully demonstrates an **electronic 7-sided dice roller** using digital logic design. By implementing a **random number generator, registers, and a full adder**, the project provides a functional model for **uneven-sided dice simulation**.

## References

1. *Digital Design* – M. Morris Mano
2. *CMOS Digital Integrated Circuits* – Sung-Mo Kang & Yusuf Leblebici

---

## How to Use

1. **Assemble the circuit** following the schematic.
2. **Upload the Arduino code** (if applicable) to generate the clock signal.
3. **Power the circuit** and observe the **random 7-sided dice outputs**.

### Future Improvements

- **Optimizing the probability distribution** for better randomness.
- **Implementing an FPGA-based version** for improved performance.
- **Adding a digital display** for better visualization of results.

---

## License

This project is open-source under the **MIT License**.

