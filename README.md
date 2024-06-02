# 8085---Zadaca6
По исчитување на податок со вредност 09h од изолирана
порта со адреса 0Bh почнувајќи од адреса POCET, сериски со
брзина од 1200bps се пренесуваат 255 податока. По
пренесувањето на податоци, на излезна изолирана порта на
адреса 0Ah се пренесува податок 0Ch. Да се напише
асемблерска програма базирана µP 8085. Фреквенцијата на
осцилаторот е 4MHz.

РЕШЕНИЕ:
Ќе го искористиме тоа дека µP знае битот 7 да го пренесе при SIM инструкција на SOD пинот, само доколку битот 6 е 1.

Ts=0,5 µS

1/1200=833µS   X*7=833   X=119 

**Developed by:**

(https://github.com/nikolovskaaleksandra)


**Subject**

Microcomputer's systems

**Built With**

This project is built using the following tools:

- [8085 simulator](https://github.com/8085simulator/8085simulator.github.io?tab=readme-ov-file): Assembler and emulator for the Intel 8085 microprocessor.

**Getting Started**

To get a local copy up and running, follow these steps.

**Prerequisites**

In order to run this project you need:

A working computer
Connection to internet
Setup

**How to Run**

To run the program, you need an 8085 emulator or assembler. You can use emulators like DOSBox or TASM (Turbo Assembler). Here's how to run the program using e8085.exe:

1. Download and install 8085 simulator from [here](https://github.com/8085simulator/8085simulator.github.io?tab=readme-ov-file).
2. Clone this repository to your local machine.
3. Open 8085 simulator and load the `zadaca6.asm` file.
4. Assemble the code by pressing the Assemble button.
5. Run the program by pressing the Run button or by pressing F10.
