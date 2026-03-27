# 🌱 Smart Crop Protection System (IoT)

An IoT-based smart crop protection system simulated in **Wokwi** to monitor field conditions and protect crops from animals or threats using sensors and actuators.

## Features
- Sensor-based crop monitoring
- Automated alert/protection mechanism
- Wokwi online simulation support
- Simple, modular IoT logic

## Tech Stack
- ESP32
- Wokwi Simulator
- Sensors (Ultrasonic / PIR / etc.)

## Programming Languages
- C++(wokwi)
- Python

## Project Structure
```
Smart-crop-protection-system-using-IOT-in-wokwi-main/
├── output.docx        # Wokwi circuit design with output
├── wokwi_code.txt     # Wokwi source code
├── Project_code.py    # Source code written in python
├── Wokwi link         # Wokwi project link
├── README.md
```

## How to Run (Wokwi)
1. Open https://wokwi.com/
2. Create a new project (ESP32)
3. Set up `IBM cloud`
4. Set up `Node-Red`
5. Paste `wokwi_code` and `use necessary sensors` and create the project diagram
6. Copy and paste the code in 'project_code.py' in a python file
7. Start simulation in `wokwi`
8. Run the python file.
9. Create mobile app using `MIT APP Inventor` and install it in your mobile
    
The data collected using sensors in wokwi is send to ibm cloud and it will be displayed in the app.  For clear reference see the `output.docx`


## Interactive Design in wokwi
<img src="Interactive design in wokwi.png"/>

## Notes
- Designed for learning and prototyping
- Can be extended with GSM, IoT cloud, or mobile alerts
