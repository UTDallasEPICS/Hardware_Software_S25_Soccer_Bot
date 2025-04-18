# ESP32 Robots
The robots are run on:
- WEMOS **ESP32-S2-Mini** Development Board
- Repeat Robotics **Budget Ant DESC**, which drives the DC motors
- Repeat Robotics **Antweight Brushed DC Motors**
- Headway LiFePO4 **40152S Battery**
- **MT3608** DC-DC Boost Converter

### Setting Up Environment
Make sure your esp_idf toolchain is installed and you can run idf.py.
Before we build and flash our project to the microcontroller, we need to tell esp_idf what microcontroller we're flashing to (which is the ESP32-S2).

Run `idf.py set-target esp32s2`

### Setup WiFi Connection

Run `idf.py menuconfig`

1. Navigate to "Connectivity Configuration"  
2. Edit WIFI SSID and Password accordingly.
3. Save and exit.
