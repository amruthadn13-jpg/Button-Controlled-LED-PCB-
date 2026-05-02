Button Controlled LED PCB (KiCad Project)
📌 Project Overview
This project demonstrates the complete PCB design flow using KiCad, starting from schematic design to PCB layout and Gerber file generation.

The circuit is a simple button-controlled LED, where the LED turns ON when the push button is pressed.

🎯 Objectives
Learn schematic design

Understand PCB layout and routing

Generate manufacturing-ready Gerber files

Gain hands-on experience for PCB design interviews

🔌 Circuit Description
The circuit consists of:

DC Voltage Source (5V)

Push Button Switch (SPST)

Resistor (220Ω)

LED (represented using diode for simulation)

Ground

Working:
When the button is pressed → circuit closes → current flows → LED glows

When released → circuit opens → LED turns OFF

🧪 Simulation
Simulation performed using KiCad SPICE simulator

LED behavior approximated using a diode model

Verified voltage and current flow in the circuit

🧱 PCB Design
Tool used: KiCad PCB Editor

Components placed based on signal flow

Routing done using 45° tracks

Ground plane added for better performance

📦 Gerber Files
Gerber files were generated for PCB manufacturing, including:

Top Copper (F.Cu)

Bottom Copper (B.Cu)

Silkscreen (F.SilkS, B.SilkS)

Solder Mask (F.Mask, B.Mask)

Board Outline (Edge.Cuts)

Drill File (.drl)

📁 Project Structure
Button_LED_PCB/
 ├── Schematic/
 ├── PCB/
 ├── Gerber/
 ├── Images/
 └── README.md
🛠️ Tools Used
KiCad (Schematic & PCB Design)

KiCad Gerber Viewer

🎓 Key Learnings
Difference between schematic symbol and footprint

Importance of Design Rule Check (DRC)

PCB routing techniques

Gerber file generation process

🎤 Interview Preparation
This project helps answer:

What is a PCB design workflow?

What are Gerber files?

What is DRC and why is it important?

How do you design a simple PCB?

🚀 Future Improvements
Add power supply module (7805 regulator)

Use SMD components

Perform advanced SPICE simulations

Design multi-layer PCB

👤 Author
Amrutha D N

