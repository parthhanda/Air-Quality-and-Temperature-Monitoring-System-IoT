# Air Quality & Temperature Monitoring System using IoT

## Project Overview
The **Air Quality & Temperature Monitoring System** is an IoT-based solution designed to provide real-time data on air quality and temperature. This project addresses critical environmental challenges like pollution and temperature fluctuations by empowering users with actionable insights.

## Problem Statement
Urbanization and industrialization have led to increased pollution and temperature fluctuations, adversely impacting public health and daily life. Existing monitoring systems are often costly, complex, and lack real-time accessibility. This project aims to develop an affordable, compact, and user-friendly system for real-time monitoring, contributing to public health and environmental sustainability.

## Key Features
- **Real-time Monitoring:** Provides continuous updates on air quality and temperature.
- **Data Visualization:** Displays data on an LCD screen and uploads it to the ThingSpeak platform.
- **User Accessibility:** Enables remote monitoring through IoT integration.
- **Alerts:** Notifies users about hazardous pollution levels.
- **Compact Design:** Utilizes cost-effective components for scalability.

## Components Used
### Hardware
1. **NodeMCU ESP8266:** Microcontroller with built-in Wi-Fi for IoT connectivity.
2. **MQ135 Gas Sensor:** Detects air pollutants like ammonia and carbon dioxide.
3. **DHT22 Sensor:** Measures temperature and humidity.
4. **16x2 LCD Display with I2C Module:** Displays data locally.
5. **Additional Accessories:**
   - Breadboard
   - Jumper wires
   - Power supply cables

### Software
- **Arduino IDE:** For programming the microcontroller.
- **ThingSpeak:** For data visualization and cloud storage.
- **Libraries Used:**
  - ESP8266WiFi
  - ThingSpeak
  - DHT
  - LiquidCrystal_I2C

## Methodology
1. **Research & Planning:** Identified essential parameters and selected suitable components.
2. **Component Integration:** Connected sensors and microcontroller to capture and process data.
3. **Circuit Design:** Designed the layout for hardware connections.
4. **Software Development:** Wrote Arduino code to:
   - Initialize and read sensor data.
   - Process data and calculate air quality indices.
   - Transmit data to ThingSpeak.
5. **Testing:** Conducted tests in various environments to ensure accuracy and reliability.
6. **Data Visualization:** Developed dashboards on ThingSpeak for user-friendly interpretation.

## Working Principle
- **Sensors:**
  - MQ135 detects gas concentrations and outputs analog data.
  - DHT22 measures temperature and humidity.
- **Data Processing:** NodeMCU processes sensor data and prepares it for display and transmission.
- **Data Display:** The LCD screen shows real-time readings.
- **Data Transmission:** The ESP8266 module uploads the data to ThingSpeak for remote access.

## Applications
- **Urban Areas:** Monitors air quality to protect residents from pollution.
- **Agriculture:** Assists farmers in optimizing irrigation and protecting crops.
- **Natural Disasters:** Provides critical data during events like wildfires.
- **Industrial Settings:** Ensures workplace safety by monitoring emissions.
- **Educational Use:** Demonstrates IoT applications in academic projects.

## Results
- The system successfully detects changes in temperature, humidity, and air quality with high accuracy.
- Reliable performance in various environments, including indoors, outdoors, and near pollution sources.
- Data visualization on ThingSpeak enhances usability and decision-making.

## Future Scope
- Integration with mobile apps for personalized alerts.
- Use of advanced sensors for detecting a broader range of pollutants.
- Expansion to a smart city framework for large-scale deployment.

## Project Images
![Circuit_Diagram](images\Circuit_Diagram.png)
![ThingSpeak_Dashboard_1](images\ThingSpeak_Dashboard_1.jpg)
![ThingSpeak_Dashboard_2](images\ThingSpeak_Dashboard_2.jpg)

- Integration with mobile apps for personalized alerts.
- Use of advanced sensors for detecting a broader range of pollutants.
- Expansion to a smart city framework for large-scale deployment.

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/parthhanda/air-quality-monitoring.git
   ```
2. Open the project in Arduino IDE.
3. Install necessary libraries (ESP8266WiFi, ThingSpeak, DHT, LiquidCrystal_I2C).
4. Connect the components as per the circuit diagram.
5. Update the code with your Wi-Fi credentials:
   ```cpp
   char ssid[] = "Your_SSID";
   char pass[] = "Your_PASSWORD";
   ```
6. Upload the code to NodeMCU using Arduino IDE.
7. Monitor data on the LCD display or ThingSpeak dashboard.

## Contributing
We welcome contributions to enhance the project. To contribute:
1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature description"
   ```
4. Push to your fork:
   ```bash
   git push origin feature-name
   ```
5. Create a pull request on the original repository.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
For any queries or feedback, please contact:
- **Parth Handa**
- Email: [parth32131handa@gmail.com](mailto:parth32131handa@gmail.com)
- GitHub: [https://github.com/parthhanda](https://github.com/parthhanda)
