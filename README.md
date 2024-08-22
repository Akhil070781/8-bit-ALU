# 8-bit ALU Design in Proteus ISIS

This project involves designing an 8-bit Arithmetic Logic Unit (ALU) using Proteus ISIS. The ALU is capable of performing a variety of logical and arithmetic operations and sets specific flags based on the outcomes of these operations.

## Project Overview

The 8-bit ALU is designed to handle fundamental operations, such as addition, subtraction, NOR, and XNOR, and to set corresponding flags, like the zero flag and the parity flag. The operations are controlled by a 3-bit binary code, where each code represents a specific operation. A multiplexer is used to select the appropriate operation based on the binary code provided.

### Key Features

- **Logical and Arithmetic Operations**:
  - **NOR Operation**: Sets the zero flag if the result is zero.
  - **XNOR Operation**: Sets the parity flag based on the evenness of the number of 1s in the result.
  - Additional operations include basic arithmetic like addition and subtraction.
  
- **Operation Selection**:
  - Each operation is assigned a 3-bit binary code.
  - A multiplexer interprets the binary code to select the desired operation from the ALU.

- **Flag Setting**:
  - The ALU is equipped to set specific flags, such as the zero flag and the parity flag, depending on the operation performed and the result obtained.

## Implementation Details

### Combinational Circuits

The ALU is based on combinational logic circuits, where the output is determined directly by the current inputs without the need for sequential logic elements. The design leverages fundamental combinational circuits to perform operations and set flags in real-time.

### Tools & Technologies

- **Simulation Software**: Proteus ISIS, a popular tool for designing and simulating electronic circuits, was used to create and test the ALU.
- **Key Concepts**: The project involves combinational circuit design, the use of multiplexers, and the implementation of flag-setting mechanisms.

## Getting Started

### Prerequisites

To work with this project, you will need:
- Proteus ISIS for circuit design and simulation.
- Basic knowledge of digital logic design, particularly combinational circuits.

### Running the Simulation

1. Clone this repository to your local machine.
2. Open the Proteus ISIS project file in your Proteus software.
3. Simulate the ALU to observe its behavior under different input conditions.
4. Modify the 3-bit control code to test different operations and verify the correct setting of flags.

