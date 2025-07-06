# sensor-interfacing-project
# Sensor Interfacing with Raspberry Pi

This project demonstrates how to interface sensors with the Raspberry Pi using the Sense HAT.

## Requirements
- Raspberry Pi 3 or newer
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
  - Temperature: 34.5°C
  - Humidity: 36.1%
  - Pressure: 979.2 hPa

## Notes
  - Ensure that the Sense HAT is securely attached to the Raspberry Pi's GPIO pins.
  - The sense_sensor.py script will continuously print sensor data to the terminal. You can stop it by pressing Ctrl+C.
  - You can modify the scripts for different use cases or experiments.

## Additional Resources
For more information about the Raspberry Pi and Sense HAT, refer to the official documentation:
  - Raspberry Pi Foundation, "Getting Started with Raspberry Pi", "https://www.raspberrypi.com/documentation/computers/getting-started.html"
  - Raspberry Pi Sense HAT Library Documentation, "https://www.raspberrypi.com/documentation/accessories/sense-hat.html"
