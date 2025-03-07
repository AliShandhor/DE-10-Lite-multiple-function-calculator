# Multiple Function Calculator on DE-10 Lite Board

## Project Overview
This project involves the design and implementation of a multi-function calculator capable of performing basic arithmetic operations (addition, subtraction, multiplication, division) and factorial calculations. The calculator is designed using **Verilog HDL** and implemented on the **DE-10 Lite Board** using the **Intel Quartus IDE** platform. The DE-10 Lite Board serves as the hardware platform for executing the calculator's logic and displaying the results.

## Features
- **Arithmetic Operations**: Addition, subtraction, multiplication, and division.
- **Factorial Calculation**: Computes the factorial of a given number.
- **User Interface**: Inputs are controlled by switches on the DE-10 Lite Board, and outputs are displayed on the seven-segment Hex(0-5) displays.
- **State Management**: The calculator transitions between different states (addition, subtraction, multiplication, division, factorial) using key buttons on the DE-10 Lite Board.

## Design Description
The calculator's design is based on combinational and sequential logic, along with state machine concepts. The system operates by transitioning between different states using input key buttons:
- Key button "0" is used to switch between functions.
- Key button "1" is used to start the operation.

The project is divided into multiple modules, with each module responsible for implementing a specific arithmetic operation. The **DE-10 Lite Board** is used to:
- Provide input through switches.
- Execute the Verilog-based logic.
- Display the results on the seven-segment displays.

## Design Simulation
You can view the design simulation image [here](https://pdf.ac/1LggnQ).

## Video Demonstration
A video demonstration of the project is available on YouTube: [Watch Video](https://youtu.be/FcSPLO7dj8A).

## Disclaimer
This project, **Multiple Function Calculator on DE-10 Lite Board**, is for educational purposes only. It was developed as part of LE/EECS 3201 Course at York University, Lassonde School of Engineering. 

- **Academic Integrity**: If you plan to use this project for school assignments, ensure you have **explicit permission from your professor or instructor**. Directly copying or submitting this work without proper understanding or authorization may violate your institution's academic integrity policies.
- **Attribution**: Credit the original authors (Ali Shandhor and Siddhrajsinh Parmar) if you use or modify this project.

By using this project, you agree to these terms.

## References
1. Visiverify. (2022, December 11). Wallace Tree multiplier. VLSI Verify. [Link](https://visiverify.com/verilog/verilog-codes/wallace-tree-multiplier)
2. YouTube. (n.d.). Route2basics. YouTube. [Link](https://www.youtube.com/@Route2basics0)
3. Admin. (n.d.). Verilog. ChipVerify. [Link](https://www.chipverify.com/tutorials/verilog)

## Contributors
- Ali Shandhor
- Siddhrajsinh Parmar

## Institution
Lassonde School of Engineering, York University
