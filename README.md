# -TEMPERATURE-MONITORING-SYSTEM

COMPANY: CODTECH IT SOLUTIONS

NAME: SELVARAJ P

INTERN ID: CT04DH870

DOMAIN: EMBEDDED SYSTEMS

DURATION: 4 WEEKS

MENTOR: NEELA SANTHOSH
OUTPUT <img width="940" height="621" alt="Image" src="https://github.com/user-attachments/assets/e0ee9c77-e2d9-4fa5-9c36-3fa53ff20b10" />
DESCRIPTION: This internship task involves designing a temperature monitoring system using an Arduino Uno, an LM35 temperature sensor, and a 16x2 LCD display. The objective is to measure ambient temperature in real time and display the value in degrees Celsius on the LCD. The system reads the analog voltage from the sensor, converts it into a temperature value, and shows it dynamically on the screen.

The hardware setup consists of an LM35 sensor connected to the analog input pin A0 of the Arduino. A potentiometer is used to adjust the contrast of the LCD, and the LCD itself is connected to digital pins 7 through 12 for data and control. A breadboard is used to organize the circuit components efficiently and distribute power from the Arduino board.

CODE DESCRIPTION: The code uses the LiquidCrystal library to control the 16x2 LCD display. It initializes the necessary pins for LCD communication and sets the analog input pin to read data from the LM35 sensor. The sensor outputs a voltage proportional to temperature (10 mV per °C), which is read and converted using the Arduino’s analogRead() function.

The formula used for conversion is:

arduino Copy Edit Temperature (°C) = (analogRead value × 5.0 × 100.0) / 1024 This converts the analog value to voltage and then to Celsius. The result is then printed on the LCD using lcd.print(), and the display is continuously updated inside the loop for real-time monitoring.

APPLICATION: This project is an excellent introduction to analog sensors, real-time data monitoring, and interfacing LCDs with microcontrollers. It has a wide range of real-world applications such as:

Room and weather temperature monitoring systems,

Safety monitoring in industrial environments,

Smart thermostat prototypes for HVAC systems,

Environmental monitoring in greenhouses,

Educational use for learning about sensors and analog-to-digital conversion.

The task reinforces essential embedded systems concepts such as sensor interfacing, signal conditioning, data conversion, and user-friendly data presentation—making it ideal for beginner-level projects in IoT and instrumentation
