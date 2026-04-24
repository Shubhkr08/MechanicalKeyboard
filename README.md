# Mechanical-Keyboard
I wanted to make a **mecanical keyboard** ,So i Choose a **60% layout** Keyboard as it is compact and funtional enough.
We will be using switch matrix wo we need less gpio pins

## Features

- Base on Raspberry pico
- Has 61 keys ( 60% Keyboard Matrix)

### Schematic
<img width="1388" height="979" alt="Screenshot (64)" src="https://github.com/user-attachments/assets/ff7585e7-83f1-4861-9735-c09dc8402372" /><br>
###  PCB Design
<img width="1542" height="712" alt="Screenshot (66)" src="https://github.com/user-attachments/assets/21599c3a-e502-4f89-9539-fa10148f88dd" /><br>
### 3D Design
<img width="1231" height="576" alt="Screenshot (62)" src="https://github.com/user-attachments/assets/c650e6b1-2e0c-4345-8f24-47e8c138a22a" /><br>
<img width="1292" height="559" alt="Screenshot (61)" src="https://github.com/user-attachments/assets/2be1bcd8-0ea9-48d2-860e-70d501d48dd8" /><br>



- ## Bill of Materials (BOM)

| Item | Quantity | Description | Unit Price (USD) | Link |
|-----:|---------:|-------------|------------------:|------|
| Cherry MX Switch (MX2A-HC1B) | 61 | Mechanical key switch | 1.95 | https://www.digikey.in/en/products/detail/cherry-americas-llc/MX2A-HC1B/21738427 |
| 1N4148 Diode | 61 | Switching diode for key matrix | 0.041 | https://www.digikey.in/en/products/detail/onsemi/1N4148TR/458811 |
| Raspberry Pi Pico (RP2040) | 1 | Main microcontroller board | 5.00 | https://www.digikey.in/en/products/detail/raspberry-pi/SC0917/16608257 |
| Keycaps Set | 1 | Backlit mechanical keyboard keycaps | 38.68 | https://www.amazon.in/Keycaps-Backlit-Mechanical-Keyboard-Switches/dp/B08R5YPYCD |
| PCB + Shipping (JLCPCB) | 1 | PCB fabrication and shipping | 29.51 | https://jlcpcb.com |

**Estimated Total Hardware Cost:** **USD 194.64**

## Hardware
- Raspberry Pico 
- Cherry MX compatible Switches
- Diode
- 2 layer PCB

## Firmware
- It is Based on KMK and Circuit Python
