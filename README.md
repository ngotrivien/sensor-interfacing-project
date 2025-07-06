# sensor-interfacing-project
# Sensor Interfacing with Raspberry Pi

This project demonstrates how to interface sensors with the Raspberry Pi using the Sense HAT.

## Requirements
- Raspberry Pi 5
- Sense HAT library installed on Raspberry Pi
- Python 3.x

## Installation
1. Clone this repository to your Raspberry Pi or local machine:
   ```
   git clone https://github.com/ngotrivien/sensor-interfacing-project.git
   ```
2. Install the necessary libraries:
   ```
   sudo apt-get update
   sudo apt-get install sense-hat
   ```
3. Run the Python scripts:
   - To display a message on the LED matrix:
     ```
     python3 sense_led.py
     ```
   - To read sensor data:
     ```
     python3 sense_sensor.py
     ```

## Example Outputs
- **LED Matrix Display:**
  - The message "Hello, Embedded AI!" will scroll on the LED matrix.
- **Sensor Readings:**
  - Temperature: 25.3°C
  - Humidity: 60.1%
  - Pressure: 1012.5 hPa

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
