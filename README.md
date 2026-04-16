# Smart Sanitary Disposal System with Web Monitoring

## Overview  
This project integrates a smart sanitary disposal hardware system with a website for real-time monitoring. The system is designed to ensure hygienic disposal of sanitary waste while displaying important data such as bin status and weight level through a web interface.

## Features  
- Touchless disposal using sensors  
- Automatic lid operation using servo motor  
- Real-time weight monitoring using load cell  
- Bin level detection using ultrasonic sensor  
- Website display for live status updates  
- Hygienic and user-friendly system  

## Technologies Used  
### Hardware  
- ESP32 Microcontroller  
- Ultrasonic Sensor  
- Load Cell with HX711  
- Servo Motor  
- OLED Display  
- Battery (Power Supply)  

### Software  
- HTML (Website Interface)  
- Arduino IDE (Programming ESP32)  

## Project Structure  
```
/project-folder
│── index.html
│── hardware/
│   │── sensors
│   │── esp32_code
│── images/
```

## Working Principle  
1. The ultrasonic sensor detects user presence or waste.  
2. The ESP32 processes the input signals.  
3. The servo motor automatically opens and closes the lid.  
4. The load cell measures the weight of waste in the bin.  
5. The system updates the status (bin level, weight).  
6. The website (index.html) displays real-time information about the system.  

## How to Run  
1. Upload the code to ESP32 using Arduino IDE  
2. Connect all hardware components properly  
3. Open the index.html file in a browser  
4. Monitor bin status and weight level through the website  

## Purpose  
The purpose of this project is to improve sanitary waste management by combining automation with real-time monitoring through a web interface.

## Future Improvements  
- Add IoT integration for remote access  
- Mobile app support  
- Alert system for bin full notification  

## Author  
Tulasiram V  

## License  
This project is for educational and research purposes.
