# SIGHT - System Identifying Geospatial Hazards and Threats
Welcome to the GitHub organization of S.I.G.H.T. – a real-time geospatial surveillance and anomaly detection system for educational institutions. Our organization is dedicated to providing a comprehensive solution for enhancing security on educational campuses using advanced technologies.

## Overview
S.I.G.H.T. stands for "System Identifying Geospatial Hazards and Threats." It's a comprehensive surveillance system designed to enhance security on educational campuses. Our system uses a combination of CCTV cameras, machine learning, and real-time analytics to detect and alert authorities about any potential anomalies or threats.


## Architecture
SIGHT follows a distributed architecture to handle real-time data streams from CCTV cameras efficiently. Key components include:
- Data Ingestion: CCTV cameras capture video footage.
- Data Capture and Encoding: The central processing server captures and encodes frames.
- Data Streaming: Preprocessed frames are streamed to a message queue.
- Real-Time Analytics: Machine learning models analyze frames for anomalies.
- Alert Generation and Notification: Alerts are sent to security personnel.
- Data Cleanup: Mechanisms manage data storage and retention.

## Technologies Used
- Video Processing: OpenCV
- Machine Learning: YOLO (You Only Look Once)
- Streaming: Apache Kafka
- Real-Time Notifications: Firebase Cloud Messaging
- Databases: NoSQL databases (e.g., MongoDB)
- Frontend: React
- Backend: Flask (or Django with Django Channels for WebSocket support)

## Features
- Real-time Anomaly Detection: Our system uses advanced machine learning models to analyze live video feeds from CCTV cameras in real-time. It can detect incidents like fights, thefts, or unauthorized entries.
- User-Friendly Web Interface: We provide a user-friendly web application that allows users to monitor live camera feeds, view historical incidents, and generate reports.
- Notifications: Users receive real-time notifications when anomalies are detected. These notifications can be configured to deliver alerts through various channels, including email and SMS.
- Analyzer: The system includes an analyzer module that allows users to upload video footage for analysis. The system provides timestamps for any anomalies detected in the video.
- Secure User Authentication: We prioritize security, ensuring that only authorized users can access the system.

## License
All repositories within this organization are licensed under the MIT license
