# Automatic_Inudtrial_Saftey_and_Security_System
🔑 Core Idea
A standalone IoT-based safety and security system for industries, built around the ARM7 LPC2148 microcontroller, integrating multiple sensors and a GSM module to provide real-time monitoring and emergency alerts.

⚙️ Hardware Components
Controller: ARM7 LPC2148 (central processor, handles all sensor inputs and outputs).

GSM Module (SIM800A): Sends SMS alerts to the industrial owner.

Sensors:

IR + PIR → intrusion/motion detection

Fire sensor → flame detection

MQ2 → LPG/gas leakage

MQ3 → alcohol vapor detection

LM35 → temperature monitoring

LDR → ambient light detection

Outputs: Relays for fan/AC, lighting, motor, sprinkler; buzzer; 16x2 LCD display.

🔄 Working Principle
Priority-based control loop:

Fire or gas leak → sprinkler ON, motor OFF, buzzer ON, SMS alert.

Alcohol detection → motor OFF, buzzer ON, SMS alert.

Routine automation → temperature-based fan control, LDR-based lighting, intrusion detection display.

IoT + GSM: Sensor data pushed to remote server + SMS notifications for emergencies.

LCD Display: Shows live sensor readings, system status, and alerts.

🛠️ Tools Used
Keil µVision → firmware development.

Flash Magic / JTAG → programming the microcontroller.

Proteus → simulation.

PuTTY → GSM module testing.

Multimeter, soldering tools, regulated power supply → hardware assembly and debugging.

✅ Advantages
Remote monitoring and control.

Quick emergency alerts.

Reduced labor and error probability.

Energy-efficient automation (LED + LDR, temperature-based fan).

⚠️ Disadvantages
Maintenance complexity.

Dependence on GSM/IoT connectivity.

📌 Applications
Industrial plants, offices, hospitals, labs.

Home automation.

Robotics and manufacturing.

Environmental monitoring.

Ships, aircraft, seminar halls.

🧪 Output
A working prototype integrating sensors, relays, GSM, and LCD, successfully tested for fire, gas, alcohol, and intrusion scenarios with SMS alerts and automated responses.


