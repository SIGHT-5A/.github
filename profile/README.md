# SIGHT - System Identifying Geospatial Hazards and Threats

## Overview

SIGHT is a real-time anomaly detection and notification system designed for college campus surveillance. 
It leverages machine learning, computer vision, and CCTV camera footage to detect various anomalous events. 
This README provides an overview of the project, its architecture, features, and how to get started.

## Table of Contents

- [Architecture](#architecture)
- [Technologies Used](#technologies-used)
- [Features](#features)

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

- Real-time anomaly detection.
- Webcam feed streaming for live monitoring.
- Historical incident playback.
- Alert management and reporting.
- User authentication and security.
