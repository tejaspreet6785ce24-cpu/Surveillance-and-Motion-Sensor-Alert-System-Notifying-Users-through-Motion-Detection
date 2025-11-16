# Surveillance-and-Motion-Sensor-Alert-System-Notifying-Users-through-Motion-Detection
💻SUBMISSION STATEMENT:

This project titled “Surveillance and Motion Sensor Alert System Using Cisco Packet Tracer” is submitted by Group 6 as part of the Applied Industrial Internet of Things (IIoT) coursework.

👥GROUP-6 MEMBERS:

Tejas(Roll no-2410996785), Surya(Roll no-2410996784), Tigmanshu(Roll no-2410996786), Sourabh(Roll no-2410996783), Tushar(Roll no-2410996787)

We hereby announce that the work that had been done in the submission is original, made by all members of Group-6 and prepared in accordance with the guidelines provided.

♦AIM:

Develop an advanced alert system utilizing motion detection and the surveillance infrastructure to promptly notify the user of any detected motion, implemented through CiscoPacket Tracer.

📋PROBLEM STATEMENT:

The objective is to develop a surveillance-integrated motion detection system in Cisco Packet Tracer that can sense movement and issue prompt alerts to the user. This solution enhances safety by enabling rapid detection and reporting of potential intrusions.

📡NETWORK ARCHITECTURE:

Our topology includes:Server-PT(1.1.1.1), 2950-24 Switch0, Webcam(1.1.1.3), Motion Detector(1.1.1.2), MCU-PT(MCU0), LED(iot1), Motion Sensor(iot0), 3560-24PS Multilayer Switch0, 7960 IP Phone0. Motion detection can be seen and controlled in the Switch0.

🔧 REQUIRED SOFTWARE COMPONENTS:

Cisco Packet Tracer (IoT supported version) Any text editor (Notepad/VS Code) GitHub for uploading project Virtual Hardware (inside Packet Tracer) Switch0 (2950-24) MCU0 (MCU-PT) & IOT devices (webcam, motion detector, LED, motion sensor, IP phone)

⚙️ AUTOMATION RULES:

1️⃣ Motion Detector → Webcam Automation

Image is shown when motion is detected.

🔔If motion detected → Webcam ON

🔔If motion NOT detected → Webcam OFF

2️⃣ Motion Detector → Light Automation

Light turns ON when motion is detected, a message will be sent and call will be placed to the police.

🔔If motion detected → Light ON

🔔If motion NOT detected → Light OFF

Programming Steps in Cisco Packet Tracer:

Open MCU-PT(MCU0) → Programming tab

📢Condition: Webcam == Motion detected → Webcam ON → Image ahowm

📢Condition: Webcam == Motion not detectes → Webcam OFF → No image shown.





<img width="848" height="699" alt="Cisco Packet Tracer - C__Users_TEJAS_OneDrive_Desktop_motion_detector iot project pkt 16-11-2025 17_14_36" src="https://github.com/user-attachments/assets/8a6f2f4e-5ca2-4c14-8434-83654d21778c" />
