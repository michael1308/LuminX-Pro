# LuminX-WLED
ESP32-based controller for individually addressable LED strips, compatible with WLED firmware.

# Features
-   ESP32-WROOM-32E
-   CH340E/G
-   USB C
-   Micro USB for power
-   2.1mm Barrel Jack w/ reversible polarity    
-   Screw Terminal power input
-   Current Measurement w/ INA219/INA180
-   5V Buck Converter
-   3.3V LDO
-   Microphone
-   IR Receiver
-   2x Digital out w/ Clock signal
-   Power Switching Relay
-   Temperature Sensor DS18B20
-   I2C Connector
-   ESP32 Debug Connector
-   Up to 10A

# Rev 1.0 (03.2023)
## Issues:
- Reverse Polarity Protection MOSFET reversed
- INA180 Resistor too large -> change to 10mOhm
- USBLC6 wrong footprint -> SOT-6


## Changes:
- Remove Micro USB
- Route Input Voltage directly to output
- Change reverse polarity protection to antiparallel diode (M7)
- Integrate PDM Microphone
- Better Integration for IR Sensor
- Better Integration for Temp Sensor
- 4 Output Channels
- Smaller Footprint
- Automotive or Glass fuse?
- Separate board for guitar -> LuminX ??
