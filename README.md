# Arduino Temperature Monitoring System

## Objective

To monitor the output of a temperature sensor using Arduino and indicate
a high temperature condition using an LED.

## Components

- Arduino Uno
- Temperature sensor
- LED
- 220Ω resistor
- Breadboard
- Jumper wires

## Working

The Arduino reads the analog output of the temperature sensor through
analog pin A0. The sensor value is displayed on the Serial Monitor.
When the sensor value exceeds 500, the LED is switched ON.

## Expected Output

The sensor value should be displayed continuously in the Serial Monitor.
The LED should turn ON when the sensor value exceeds the threshold.

## QA Approach

The project is tested for:

- Sensor connection
- Analog input pin
- Temperature threshold
- LED indication
- Serial communication
- Program compilation
