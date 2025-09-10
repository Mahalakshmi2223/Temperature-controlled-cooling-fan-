# Temperature Controlled Cooling Fan

## Overview
This project uses an Arduino Uno and a DHT11 temperature sensor to control a cooling fan.  
If the temperature exceeds a threshold (30°C), the fan automatically turns ON.  
If the temperature is below the threshold, the fan remains OFF.  

## Hardware Required
- Arduino Uno
- DHT11 Temperature Sensor
- DC Motor (as fan)
- Transistor (TIP122) + Diode (1N4007) for motor driver
- Power supply (9V battery or adapter)
- Jumper wires

## Features
- Automatic cooling fan control based on room temperature.  
- Energy-efficient system – runs only when needed.  
- Simple to build and cost-effective.  

## Circuit Diagram
(Insert circuit_diagram.png here)

## How to Run
1. Connect the components as per the circuit diagram.  
2. Upload `temp_fan.ino` to Arduino using Arduino IDE.  
3. Open Serial Monitor to view live temperature readings.  
4. Observe fan operation based on temperature changes.  

## Future Improvements
- Display temperature on LCD/7-segment display.  
- Variable fan speed using PWM.
