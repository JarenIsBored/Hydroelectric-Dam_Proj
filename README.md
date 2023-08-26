# Hydroelectric-Dam_Proj
Hydroelectric dam project for renewable energy. 30% of renewables, 7% of US power. Hydroelectric dam requires a stable water level and consistent electricity generation for a nearby town.

For this group project, I have been tasked to designed a microcontroller system for the hydroelectric dam to monitor temperature, water level, gate operations, provide alerts through sound and lights, enable manual overrides, and automatically regulate water quality by controlling inflow and exchange.

### Board Operations
To simulate a Hydroelectric damn, the target board will monitor the temperature, water level, and gate status. The temperature will be displayed on a 7-segment display. The water level will be displayed on the LCD as a percentage. When the water level is max/min, an alert will sound and the motor will be activated to open/close gate and update on lcd as well. The operator can manually open/close a gate by pressing a button. After a certain duration, the gate will automatically open to realease water and close after a while.

### Software features used
- Polling of input pins
- External Interrupt
- Timers
- Analog-to-digital conversion

### Hardware components used
- LEDs, toggle switches, push-buttons
- Seven-segment display
- 16 by 2 LCD
- Speaker
- motor
- LM35

### Personal Contributions
Used the Lcd to display the water level increments and 7seg to display the temperature
- Created a timer interrupt that increments the water level until max and decrement it until minmum and it will continously loop.
- Used adc conversion to get temperature from lm35 and display it on the 7seg.

