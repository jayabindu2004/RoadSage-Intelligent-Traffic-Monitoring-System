# 🚦 RoadSage: Intelligent Traffic Monitoring System 🚗

RoadSage is a comprehensive AI-based traffic monitoring solution that addresses major urban transportation challenges like congestion, accidents, and inefficient parking. Built with real-time computer vision and alerting systems, RoadSage is ideal for smart campuses, institutions, and urban areas looking to improve road safety, traffic flow, and parking space management.

---

## 🔍 Introduction

In today’s fast-paced urban environments, managing traffic efficiently is a growing concern. Manual surveillance is time-consuming and prone to error, while the lack of real-time systems results in delayed emergency responses and disorganized parking.

**RoadSage** offers a smart, automated, and scalable platform that integrates vehicle detection, license plate recognition, speed monitoring, accident detection, and smart parking into one cohesive system. The solution utilizes real-time CCTV footage and deep learning models to process traffic visuals, enabling immediate decisions, alerts, and visual feedback through a unified interface.

With real-world applications in smart city infrastructure, campus security, and public road safety, RoadSage brings automation, accuracy, and efficiency into traffic management systems.

---

## 🛠️ Technology Stack

| Feature | Technology Used |
|--------|------------------|
| Vehicle Detection & Speed Monitoring | YOLOv8 |
| License Plate Recognition | Haar Cascade |
| Accident Detection | CNN / VGG16 |
| Alerts System | Twilio (SMS), SMTP (Email) |
| Dashboard Interface | Streamlit |

---

## 📦 Modules Overview

### 1. 🚘 **Vehicle Detection & Speed Monitoring**  
- Uses **YOLOv8**, a state-of-the-art object detection algorithm, to detect and track vehicles in real-time.  
- Speed is calculated by tracking object movement across frames and applying distance-time computation logic.  
- Helps monitor traffic violations and analyze traffic flow dynamics.

### 2. 🔢 **License Plate Recognition**  
- Implements **Haar Cascade classifiers** trained on Indian license plates.  
- Extracts plate region from vehicle detection and applies OCR techniques to decode alphanumeric plate numbers.  
- Useful for vehicle identification, entry logging, and enforcement scenarios.

### 3. ⚠️ **Accident Detection**  
- Uses a **Convolutional Neural Network (CNN)** model based on **VGG16** architecture.  
- Trained to differentiate between normal driving frames and accident scenarios using visual patterns.  
- Helps reduce emergency response time by triggering real-time alerts.

### 4. 🅿️ **Smart Parking Detection**  
- Uses YOLOv8 to monitor predefined parking zones in a frame.  
- Each slot is treated as a bounding box; the system detects occupancy or availability in real-time.  
- Efficient for campus or commercial space parking management.

### 5. 📲 **Alert System (SMS/Email)**  
- When an accident or unauthorized event is detected, the system sends an immediate alert to registered contacts.  
- Alerts are sent via **Twilio API** (SMS) and **SMTP** (Email).  
- Can be extended to notify authorities or security personnel.

### 6. 🖥️ **Streamlit Dashboard**  
- Provides an interactive and easy-to-use UI for monitoring all modules.  
- Displays live updates, detected vehicles, alerts, and parking slot statuses.  
- Built with Streamlit for rapid deployment and accessibility through any browser.

---

## 🎯 Objectives

- Detect license plates and monitor vehicle speed in real-time  
- Identify and alert on accident events immediately  
- Visualize parking slot occupancy dynamically  
- Offer a unified interface for live tracking and control  

---

## 📊 Results

- 📸 High-accuracy plate and vehicle detection  
- 🚨 Real-time alerts for critical events  
- 🅿️ Smart visualization of parking availability  
- 🧠 Robust model performance across varied camera feeds  

---

## 🌟 Benefits

- 🚦 Safer roads with smart crash alerts  
- 🅿️ Stress-free, automated parking management  
- 🤖 AI-driven monitoring reduces manual workload  
- 🧠 Scalable system for campuses, offices, and cities  
- 📲 Real-time notifications via SMS and email  
- 💻 All-in-one simple and clean dashboard  

---

## 🚀 Getting Started

### 🔧 Prerequisites

- Python 3.7+
- OpenCV
- TensorFlow / Keras
- PyTorch
- Streamlit
- Twilio SDK
- NumPy, Pandas

Install required packages:

pip install -r requirements.txt


## 📸 Demo Snapshots

### 🔹 Vehicle Detection & Speed Estimation
<img width="2542" height="1063" alt="image" src="https://github.com/user-attachments/assets/8e4b0c8f-21e7-4700-8437-ee33200fcd33" />

### 🔹 License Plate Recognition
<img width="2409" height="965" alt="image" src="https://github.com/user-attachments/assets/f0ea704f-9cf6-42d0-b3ce-9cb40111415e" />

##### Real-time License Plate Recognition demo
<img width="2218" height="1255" alt="image" src="https://github.com/user-attachments/assets/7234411d-849e-46fb-9656-3a4600420e10" />

### 🔹 Accident Detection
<img width="2531" height="1063" alt="image" src="https://github.com/user-attachments/assets/64919a4c-92a9-45e1-8b6a-7a4d775d0267" />


### 🔹 Smart Parking Visualization
<img width="2542" height="1063" alt="image" src="https://github.com/user-attachments/assets/1c76a3e8-9d54-41fa-970b-9def82d7482f" />

### 🔹 Real-Time Alert Notification
<img width="560" height="1187" alt="image" src="https://github.com/user-attachments/assets/fcb1a8f3-cbee-4f48-ba05-a0a4c6d9b78f" />
<img width="1174" height="199" alt="image" src="https://github.com/user-attachments/assets/4a0f5555-a1dd-4b54-802e-904f918aff1a" />

### 🔹 Streamlit Dashboard Interface
<img width="2431" height="1079" alt="image" src="https://github.com/user-attachments/assets/35bd513c-e21e-49d8-b589-dcb52b149efb" />

## ▶️ Run the Application

streamlit run app.py

### 👩‍💻 Team Members
Basava Jayabindu (1MS21CI010)

Beeram Nikita (1MS21CI011)

Suha Jameel S (1MS21CI057)
