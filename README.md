# plant_Moisture_Sensor

Arduino-Based Irrigation System with I2C Device Scanning : **Control over - Overwatering and Underwatering to the plants.**

Components Required:
* Arduino board (e.g., Arduino Uno)
* I2C-enabled LCD (e.g., 16x2 LCD with I2C module)
* Moisture sensor connected to A0 (Analog Input)
* Relay module (to control the water pump)
* Water pump
* Wires and power supply

Steps: 

Step 1: Hardware Setup:

Connect I2C-enabled LCD, moisture sensor, relay module, and water pump to the Arduino.

Step 2: Upload I2C Device Scanning Code:

Upload the "I2C Device Scanning" code to the Arduino to find the LCD's I2C address.

Step 3: Identify I2C Address:

Open Serial Monitor to see the LCD's I2C address and note it down.

Step 4: Upload Irrigation System Code:

Replace the LCD's address with the obtained I2C address in the "Irrigation System" code.
Upload the modified "Irrigation System" code to the Arduino.

Step 5: Run the Combined System:

The Arduino will monitor soil moisture levels with the sensor.
If moisture is low, the water pump turns on and LCD displays "Water Pump is ON."
If moisture is sufficient, the pump turns off and LCD shows "Water Pump is OFF."

Step 6: Monitor the System:

Use the Serial Monitor to observe sensor values and system status.

Step 7: Adjust Thresholds:

Modify moisture thresholds in the code if needed.

Step 8: Power Supply:

Ensure the Arduino and pump have a stable power supply, considering the pump's requirements.

Step 9: Testing:

Test the system by placing the moisture sensor in soil to verify its operation.

Step 10: Customization (Optional):

- Customize LCD messages or add more sensors/features as required.
