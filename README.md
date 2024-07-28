Name: YADAV MANENDRAKUMAR VINODKUMAR                                    <br>
Company: CODTECH IT SOLUTIONS                                            <br>
ID: CTO8DS3773                                                            <br>
Domain: Embedded Systems                                                   <br>
Duration: July to April 2024                                              <br>
Mentor: Neela Santosh Kumar                                                  <br>


Project Overview: Arduino DHT22 Temperature and Humidity Sensor

Project Description:
This project involves interfacing a DHT22 (AM2302) sensor with an Arduino Uno to measure temperature and humidity. The sensor readings are displayed on a serial monitor, providing real-time environmental data.

Components Used:
*Arduino Uno: Acts as the microcontroller to read data from the sensor and output it to the serial monitor.
*DHT22 Sensor: A digital sensor capable of measuring temperature and humidity with high accuracy.
*Connecting Wires: Used to establish electrical connections between the Arduino and the DHT22 sensor.

Functionality:
1.Initialization:
The Arduino initializes serial communication at a baud rate of 115200 and sets up communication with the DHT22 sensor.
2.Reading Sensor Data:
In the loop() function, the Arduino reads temperature and humidity values from the DHT22 sensor using the readTemperature() and readHumidity() methods provided by the DHT library.
3.Error Handling:
Checks are performed to ensure valid readings. If a reading is invalid (NaN), an error message is displayed on the serial monitor, and the loop continues without displaying the erroneous data.
4.Displaying Data:
Valid temperature and humidity readings are printed to the serial monitor in a formatted manner (Humidity: XX.X% Temperature: XX.X°C).
5.Delay:
After each reading, there is a delay of 2 seconds (delay(2000)) to prevent rapid consecutive readings, which can overload the sensor or flood the serial monitor.

Project Benefits:
*Real-time Monitoring: Provides continuous monitoring of temperature and humidity levels.
*Easy Integration: Simple hardware setup and straightforward software implementation using Arduino IDE.
*Educational Value: Helps in understanding sensor interfacing, data acquisition, and basic error handling in embedded systems.

Applications:
*Home Automation: Monitoring indoor climate conditions.
*Greenhouses: Controlling and optimizing growing conditions for plants.
*Weather Stations: Collecting data for weather monitoring and analysis.

Challenges:
*Sensor Accuracy: Ensuring accurate readings by calibrating the sensor if necessary.
*Environmental Factors: External factors such as airflow or heat sources can affect sensor readings.

Future Enhancements:
*Data Logging: Store sensor readings in a memory card or send them to a cloud platform for further analysis.
*Display Integration: Interface with a graphical LCD or OLED display for local data visualization.

Conclusion:
This project demonstrates a fundamental application of sensor interfacing and data acquisition using the Arduino platform. It offers a practical introduction to monitoring environmental parameters and serves as a basis for more advanced IoT (Internet of Things) projects involving sensor networks and data analytics.

output (simulation on WOWKI):

![code tech task2](https://github.com/user-attachments/assets/58736948-e8a3-40ff-b2ad-10aa88474a40)

