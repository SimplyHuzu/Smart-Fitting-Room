# Smart-Fitting-Room

AI-Integrated Smart Fitting Room System with hardware-software interaction for enhanced retail experiences
Overview

The Smart Fitting Room is an innovative hardware-software system designed to enhance security and improve the shopping experience in retail environments. It integrates RFID technology, microcontrollers, and a system dashboard to monitor and manage products in fitting rooms, reducing theft and ensuring accountability.

Key Features

RFID-based product tracking: Customers scan items with RFID tags when entering the fitting room.

Secure exit protocol: All products scanned in must be scanned out before leaving.

Real-time system dashboard: Provides live monitoring of all scanned items and fitting room activity.

ESP32 Microcontroller integration: Manages RFID reader data and communicates with the dashboard system.

Hardware-software interaction: Ensures seamless coordination between physical sensors and software logic.

Theft reduction: Designed specifically to prevent product loss in retail environments.

Technologies Used

Hardware: ESP32 microcontroller, RFID readers, RFID tags

Software: [Insert software language, e.g., Python / Java / Node.js] for system logic and dashboard

Database: MySQL / PostgreSQL (or whatever you used for dashboard)

AI Tools / Prompt Engineering: Used AI-assisted coding to accelerate development and optimize software logic

System Workflow

Customer enters fitting room and scans products using RFID tags.

ESP32 microcontroller reads tag information and updates the dashboard system in real time.

Customers must scan all products before exiting. The system verifies that all scanned items match the items taken in.

If items are not properly scanned out, the system prevents exit and alerts staff.

Purpose

The system was developed to:

Reduce theft in retail stores by enforcing strict inventory accountability

Provide a real-time monitoring system for staff and management

Demonstrate hardware-software integration and AI-assisted development

Project Resources

Full Source Code: Included in repository

Hardware Schematics: Diagrams of RFID setup and ESP32 connections

Demonstration Video: Shows system in action

Documentation: Instructions for setup, deployment, and usage


