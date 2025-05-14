# 🧠 Smart Curtain System
This project is a Smart Curtain System designed using logic gates (AND, OR, NOR, NOT), switches, resistors, and an LDR sensor. It automates curtain control based on light intensity and user inputs.

## ⚙️ Project Description
The smart curtain system is built with basic logic gates to simulate an automatic curtain that responds to both light conditions and manual override switches.

The main inputs are:

LDR (Light Dependent Resistor): Detects ambient light.

LC (Local Control): Manual curtain control.

SO (System Override): Forces curtain open or closed.

SC (Set Control): Additional control signal.

The outputs are processed using:

AND, OR, NOR, and NOT gates (7400 series ICs).

A final output connected to an LED (as an indicator for Error).

## 🖥️ Simulation & PCB
The schematic circuit was designed and simulated using Proteus.

PCB layout was created for real-world implementation, including labels for all inputs/outputs.

All logic is implemented through TTL logic ICs (7400 series), without any microcontroller.

## 🔧 Schematic Preview

## 🧾 PCB Layout

## 📌 Features
Fully hardware-based logic design.

Uses LDR to control curtain based on light intensity.

Manual override using toggle switches.

Educational circuit that demonstrates the power of digital logic in automation.

## 📎 Tools Used
Proteus for schematic and simulation.

Altium for PCB layout.

