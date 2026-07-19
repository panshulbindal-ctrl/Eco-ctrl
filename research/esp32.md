# ECO-CTRL Research work

1. What is a Microcontroller?
A microcontroller is a compact, tiny computer built onto a single integrated circuit. Designed specifically for embedded systems, it integrates a central processing unit, memory, and programmable input/output peripherals carrying out a dedicated task unlike PCs.

2. What is the ESP32?
The Esp32 is a low-cost microcontroller developed by Espressif systems. It is widely used for IoT devices, robotics and smart home projects because it has a high speed processor, enough memory and integrated wifi and bluetooth on a single chip.

3. Specifications:
- CPU architecture - Tensilica Xtensa L6
- Clock speed - 2.4GHz
- RAM - 520KB
- Flash memory - 4MB
- Wi-Fi - Yes (Wi-Fi 6)
- Bluetooth - Yes (Bluetooth 5)
- Operating voltage - 3.3v 

4. Communication protocols:
- l2C: Typically uses GPIO 22 and GPIO 21 by default to connect oled displays and multiple sensors
- SPI: Serial peripheral interface used for high speed devices like SD card modules 
- UART(Hardware serial): Used for programming and debugging

5. What makes Esp32 better than Arduino Uno for IoT?
Esp32 has in-built Wi-Fi and Bluetooth so it doesn't require any external modules. It has a way better clock speed and RAM than Arduino Uno which enables it to multitask easily. The Esp32 also has lower power usage than Arduino Uno, as it has a deep sleep mode, which wakes uo instantly to transmit data.
