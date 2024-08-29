Components:
Arduino Uno
OLED Display (SSD1306, 128x64)
Voltage Sensor (Optional, depending on the voltage range of signals you want to measure)
Jumper Wires
Breadboard
Circuit Diagram:
Connections:
OLED Display (SSD1306):

VCC → 5V (or 3.3V, depending on your OLED)
GND → GND
SCL → A5 (SCL)
SDA → A4 (SDA)
Voltage Signal Input:

Signal (+) → A0 (Analog Input on Arduino)
Signal (-) → GND
