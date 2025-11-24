# Introduction
This repository will serve as a place to store all of the small projects I've worked on to learn how the Lattice ICE40 HX1K FPGA works. Each project in this repository will be from the book Getting Started With FPGAs by Russel Herrik and will be ran on the nandland.com Go Board. I will provide links to all relevant resources below.

Links:  
[nandland.com](https://nandland.com/)  
[Getting Started With FPGAs Book](https://nandland.com/book-getting-started-with-fpga/)  
[The Go Board](https://nandland.com/the-go-board/)

## Project 1 - Switches to LEDs
This project was super simple, but was still very important to learning how to use this FPGA. Since I have some experience programming in Verilog the main thing that I learned was how to use the necessary tools to configure, compile, and flash the FPGA with my code.  

To configure the FPGA I had to learn about creating .pcf files that route the pins of the FPGA to the named inputs and outputs of my program. For compiling and flashing the program however, I had to look to external tools. In the case of the Lattice ICE40 HX1K FPGA, or any Lattice FPGA for that matter, compiling can be done with the iCEcube2 IDE and flashing can be done with their Diamond Programmer application. I will link both of these tools below for ease of use.

Note: Contrary to what the iCEcube2 IDE site claims, the IDE does actually have a hobbyist license. To get this license you have to email Lattice Semiconductors directly with specific information. They will then send you the hobbyist license for your use.

## Project 2 - LED with AND Gate

## Project 3 - Toggling LED with Flip-Flop

## Project 4 - Switch Debouncing