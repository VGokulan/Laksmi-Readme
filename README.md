# Lakshmi Smart Waste Management System

## Overview
Even in developing areas, garbage overflow and waste on the streets persist, despite waste collection systems in place. Poor waste management practices lead to environmental issues and public health concerns. So we introduce **Lakshmi Smart Waste Management System** is an innovative solution designed to tackle waste management challenges in urban areas. Leveraging real-time data and predictive analytics, Lakshmi optimizes waste collection, prevents overflow, and ensures timely responses to cleanliness issues, enhancing resource efficiency and environmental sustainability.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features
1. ### **Optimized Waste Collection**: Real-time sensor data tracks bin levels, ensuring efficient collection and reduced operational costs.

  ![Screenshot 2025-01-07 102626](https://github.com/user-attachments/assets/73f2acb5-cdcd-41e9-aa34-07f1347d41d2)

2. ### **Preventing Overflow & Littering**: Predictive models anticipate waste patterns, preventing overflow during public events.
   
   ![Screenshot 2025-01-07 102652](https://github.com/user-attachments/assets/002b7e7a-d0c0-4a19-a169-6bed088c5ed6)

3. ### **Dynamic Event-based Allocation**: If there is a evernt notified it allocates necessary resources for the garbage collection there via our app.
 
   ![Screenshot 2025-01-07 102412](https://github.com/user-attachments/assets/8623452d-126f-4129-b493-da59d25bbce1)

   ![Screenshot 2025-01-07 102739](https://github.com/user-attachments/assets/d2bb238e-000f-425b-848d-55442be44109)


4. ### **Immediate Response to Cleanliness Issues**: Public photo-reporting feature for quick action on cleanliness complaints.
 
   ![Screenshot 2025-01-07 102513](https://github.com/user-attachments/assets/e55a5e52-dc91-4e3e-883d-9f853d933465)
   
   ![Screenshot 2025-01-07 102749](https://github.com/user-attachments/assets/6ae5a22d-b055-4e38-ba84-7476e664ff0e)


5. ### **Efficient Fleet Utilization**: Predictive vehicle allocation optimizes fleet use, reducing wear and tear.

![Screenshot 2025-01-07 102809](https://github.com/user-attachments/assets/7dfba954-db23-4a84-990a-c32378eb6b46)

6. ### **Announcements**: Event and updates can be announced to user and authorities.

![Screenshot 2025-01-07 102529](https://github.com/user-attachments/assets/35c15af0-4d41-409f-aa0a-974ff15b1cfe)

![Screenshot 2025-01-07 102859](https://github.com/user-attachments/assets/c3f1d7f4-fe13-4f5a-875b-a99b13005cb2)

## Installations

## Installation
### Step 1: Clone the Repository
```bash
git clone https://github.com/username/smart-waste-management.git
cd smart-waste-management
```
### Step 2: Install Required Libraries
It is recommended to set up a virtual environment:
```
python -m venv env
source env/bin/activate    # Linux/MacOS
env\Scripts\activate       # Windows
```
Install the dependencies:
```
pip install -r requirements.txt
```
### Step 3: Setup Backend
Ensure you have installed and configured the backend files on your system .

```
python app.py
```
### Step 4: Setup Frontend (AHP32)
Ensure you have installed and configured the frontend files  on your system .
```
npm run build 
```
### Step 5: Setup IoT Sensors (AHP32)
Configure the AHP32 ultrasonic sensors for real-time data collection:

-Ensure proper connection and setup of sensors with the bins.
-Set up an MQTT broker or other IoT communication protocols to send data to the system.


## Usage
### Running the System
1. **Start the Sensor Data Collection:** The system will collect real-time data from the AHP32 Ultrasonic Sensors and log fill levels.
```
python sensor_data_collection.py
```
2. **Run Predictive Model:** The ensemble machine learning model will predict future waste levels and trigger vehicle routing based on predictions.
```
python waste_prediction.py
```
3. **Dashboard Access:** Open the dashboard in your browser to monitor real-time fill levels, vehicle routing, event schedules, and user queries.
```
python dashboard.py
```
4. **User Interaction:** Users can interact with the Lakshmi chatbot for event registration, complaint reporting, and garbage classification.
```
python chatbot.py
```

## Technologies Used

1. **Front-End** : HTML , CSS , JavaScript
2. **Back-End** : MongoDB , Flask
3. **FrameWork** : Tensorflow , Google Map API , PyTorch
4. **Models** : Ensemble Model (Random Forest , XGB Regressor ,Gradient Boosting ) , KNN Models
5. **IOT Sensors** : ESP32u , UltraSonic Sensor
6. **IOT modules** : Wifi.h , httpclient.h , newping.h
7. **Storage** : MongoDB

## Project Structure

![image](https://github.com/user-attachments/assets/be5bb119-7b27-4e64-a66c-50029ab00a90)

## Contributing 
Team Members:
  - Senthanee
  - Srikanth
  - Vicky
  - Gokulan

## Contact
- Leader Email() PhoneNo()
- Member Email() PhoneNo()




