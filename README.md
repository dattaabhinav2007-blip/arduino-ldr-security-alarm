# arduino-ldr-security-alarm
Arduino UNO security alarm using LDR, LED and buzzer.
# Arduino UNO LDR Security Alarm

A simple Arduino UNO-based security alarm system that uses an LDR to detect changes in light intensity and provides visual and audible alerts using LEDs and a buzzer.

## Components

- Arduino UNO
- LDR (Light Dependent Resistor)
- 10kΩ Resistor
- Red LED
- Green LED
- Buzzer
- 220Ω Resistors
- Breadboard
- Jumper Wires

## Pin Configuration

| Component | Arduino Pin |
|---|---|
| LDR Output | A0 |
| Green LED | D6 |
| Red LED | D7 |
| Buzzer | D8 |

## Working

- The LDR continuously monitors the surrounding light intensity.
- Under normal lighting conditions, the green LED remains ON and the buzzer stays OFF.
- When the light falling on the LDR is blocked, the Arduino detects the change in the sensor value.
- The red LED turns ON and the buzzer is activated to indicate a possible intrusion.
- The system continuously monitors the LDR and returns to normal status when the light condition is restored.

## Concepts Used

- Arduino UNO
- Analog Input
- LDR Sensor
- Voltage Divider
- `analogRead()`
- Conditional Statements
- LED Indication
- Buzzer Control
- Basic Security-System Logic

## Future Improvements

- PIR sensor for motion detection
- Keypad-based security control
- LCD/OLED status display
- Multiple sensors
- GSM-based alert system
- ESP32-based IoT monitoring

##Demo-Video: ⏯️ "https://drive.google.com/file/d/1qlJgZtiwjXBttaBOm6Hio8TJxKpNOm_j/view?usp=drivesdk"
