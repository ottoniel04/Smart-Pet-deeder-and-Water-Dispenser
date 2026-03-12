# Smart-Pet-deeder-and-Water-Dispenser
AI-powered smart pet feeder using ESP32 and Raspberry Pi with MindSpore for pet detection (dog/cat) and intelligent food and water dispensing.
# AI Smart Pet Feeder

## Huawei ICT Competition 2025–2026 | Innovation Track

### Team Information
Team Name: MECAHN  
University: UNITEC 
Country: Honduras 

---

# Project Overview

The AI Smart Pet Feeder is an intelligent system designed to automate and improve pet feeding management. The system dispenses both food and water and integrates artificial intelligence to detect the presence of pets and classify them as dogs or cats.

The project combines IoT hardware and AI technologies using an ESP32 microcontroller, a Raspberry Pi for AI processing, and the MindSpore framework for computer vision.

The goal of this system is to provide a smarter and more reliable feeding solution while enabling future behavioral monitoring of pets.

---

# Problem Statement

Many pet owners cannot always monitor their pets' feeding habits due to work or travel. Traditional automatic feeders dispense food at fixed times without verifying whether the pet is actually present or consuming the food.

Additionally, mechanical sensors used in common feeders can fail due to food residue or hardware limitations.

This project aims to solve these problems by integrating artificial intelligence to detect the presence of pets and enable intelligent feeding decisions.

---

# Proposed Solution

The proposed solution is an AI-powered smart feeder capable of:

• Detecting the presence of a pet using computer vision  
• Classifying the animal as a dog or cat  
• Dispensing food and water remotely  
• Preventing unnecessary food dispensing when no pet is present  

Future improvements will allow the system to analyze feeding behavior patterns and generate alerts when abnormal eating behavior is detected.

---

# System Architecture

The system is composed of the following components:

### Hardware
- ESP32 microcontroller
- Raspberry Pi
- Camera module
- Servo motor for food dispensing
- Water pump for water dispensing
- Water sensor
- Push botons
- Leds and resistences
- 12vdc Power supply system

### Software
- MindSpore AI framework
- Python for AI processing
- Embedded code for ESP32
- Communication between Raspberry Pi and ESP32

---

# System Workflow

1. The camera captures an image of the feeding area.
2. The Raspberry Pi processes the image using a trained AI model.
3. The AI model detects whether a pet is present.
4. The model classifies the animal as either a dog or a cat.
5. If a pet is detected, the system allows the feeder to dispense food or water.

---

# Artificial Intelligence Implementation

The artificial intelligence component of the project was developed using the MindSpore deep learning framework.

### AI Functionality

The AI system currently performs:

• Pet presence detection  
• Pet classification (dog or cat)

### Model Type

A convolutional neural network (CNN) was trained to classify images of pets captured by the camera.

### Dataset

The training dataset contains images of:

- Dogs
- Cats

Images were collected from public datasets and additional custom images captured during system testing.

### Training Process

1. Dataset preprocessing
2. Image labeling
3. Model training using MindSpore
4. Model validation and testing
5. Exporting trained weights for inference

---

# Future Improvements

Future versions of the project will expand the use of artificial intelligence to include:

• Learning pet feeding habits using machine learning  
• Detecting abnormal feeding behavior  
• Sending alerts to pet owners when irregular consumption patterns are detected  
• Visual verification of food consumption using computer vision  

This will allow the feeder to act as an intelligent assistant for pet care.

---

# Repository Structure
