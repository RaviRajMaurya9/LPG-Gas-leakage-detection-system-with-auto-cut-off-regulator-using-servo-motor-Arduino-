# LPG-Gas-leakage-detection-system-with-auto-cut-off-regulator-using-servo-motor-Arduino-

Working Method:--
The MQ2 sensor continuously monitors the air for the presence of gas.
When gas leakage is detected and its concentration exceeds a predefined threshold, the MQ2 sensor sends a signal to the Arduino.
Upon receiving the signal from the sensor, the Arduino triggers the following actions:
Activates the buzzer to produce an audible alarm, alerting individuals of the gas leakage.
Rotates the servo motor to a predefined angle (e.g., 180 degrees) to perform a specific action, such as closing a valve or activating a safety mechanism.
Turns on the relay module, which in turn activates the cooling fan to improve ventilation and disperse any leaked gas.
After a certain period (e.g., 5 seconds), the Arduino returns the servo motor to its original position (e.g., 0 degrees) and turns off the buzzer and cooling fan if the gas concentration returns to a safe level.
