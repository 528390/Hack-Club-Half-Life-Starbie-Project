Starbie - A Tiny Digital Pet

What is this project?
Starbie is a small digital pet that runs on a custom-designed printed circuit board (PCB). This project aims to teach PCB design and programming while creating an interactive mini companion.

How does this project work?
Starbie uses a XIAO ESP32-C3 microcontroller to run its program. An OLED screen displays the pet and buttons allow the user to interact with it. An MPU6050 motion sensor lets Starbie react to movement, and a DHT11 sensor provides temperature and humidity readings. There are also customizable actions that are programmed through Arduino including dance, love, and other features to give Starbie a unique personality.

List of hardware components:

XIAO ESP32-C3 microcontroller

0.96-inch OLED display

MPU6050 sensor

DHT11 sensor

Buttons(2x) and resistor(1x)

Custom PCB designed with KiCad

My Project Status:
The PCB design is complete and the firmware is still in progress. Once the physical parts arrive, I plan to assemble it and run the code on the Starbie. My goal is to have a finished design, test Starbie on the physical hardware, and prepare the files for manufacturing.

Repository Contents:

BOM.md — Bill of materials(written from the Hack Club Half Life project page)

JOURNAL.md — Project progress and development notes(written from the Hack Club Half Life progress page)

Additional PCB design files and Arduino firmware will be added as they are organized

PCB Design:
https://github.com/528390/Hack-Club-Half-Life/blob/main/Starbie_PCB_layout.png.png 

PCB Schematic Layout:
https://github.com/528390/Hack-Club-Half-Life/blob/main/Starbie_PCB_Schematic_Layout.png.png 

PCB Images
<img width="856" height="662" alt="Starbie_PCB_layout png" src="https://github.com/user-attachments/assets/169cc237-5641-49b3-b92c-559e51959291" />
<img width="762" height="750" alt="Starbie_PCB_Schematic_Layout png" src="https://github.com/user-attachments/assets/aa867f0e-4ecf-47cb-adad-9bd1de7a70a3" />

Bill of Materials(BOM)

| Part / Material | Quantity | Unit Price | Buying Link |
|---|---|---|---|
| XIAO ESP32-C3 | 1 | $5.00 | [Seeed Studio](https://www.seeedstudio.com/Seeed-XIAO-ESP32C3-p-5431.html?srsltid=AU7gw4V6TfENxZQmkH_F8Mk83ftgqdZAT28t9kuUnMG3zEgQpXikfw4o)|
| 0.96-inch OLED display | 1 | $2.50 | [OLED display](https://www.amazon.com/dp/B0GBVWBWCR?th=1) |
| MPU6050 sensor module | 1 | $2.29 | [MPU6050 module](https://www.amazon.com/dp/B0943SGP34) |
| DHT11 temperature and humidity sensor | 1 | $2.00 | [DHT11 module](https://www.amazon.com/dp/B0BLG7R99R) |
| MX Switches | 2 | $0.18 | [Push buttons](https://www.amazon.com//dp/B0FQP8VYX4) |
| Resistor | 1 | $0.05 | [Resistor](https://www.amazon.com/dp/B0B4JFPHTW?th=1) |
| Custom PCB | 1 | $10.30 | [PCB manufacturing](https://jlcpcb.com/) |
| MX Keycaps | 2 | $0.60 | [Keycaps](https://www.amazon.com/dp/B0CQ2VLMVY?th=1) |
