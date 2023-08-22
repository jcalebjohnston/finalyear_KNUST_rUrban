**Automated Irrigation System__________
An intelligent irrigation system controlled via a web interface and USSD. Built using ESP32 and interfaced with a range of sensors for real-time feedback.

Features_________
Real-time humidity, temperature, soil moisture, and water level monitoring using sensors.
Manual control options via a web interface and USSD.
Automated irrigation based on set conditions and thresholds.
Database storage for logging sensor data.
Web interface to view the last ten farm records.
USSD interface for mobile interactions.
Getting Started________
Prerequisites__
Web server with PHP support (e.g., Apache).
MySQL Database.
ESP32 with necessary sensors wired.
Installation______
Clone the repository:


Copy code_________
git clone https://github.com/jcalebjohnston/finalyear_KNUST_rUrban.git
Update database connection parameters in the provided PHP scripts.

Deploy the web application to your server.

Flash the ESP32 with the provided Arduino code and ensure it's connected to the same network as your server.

Usage________
Navigate to the web interface to view the latest sensor readings and control the irrigation system.
Dial the USSD code from your mobile device for mobile-based controls and readings.

Contributing_________
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
