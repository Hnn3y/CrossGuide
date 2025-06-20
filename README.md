# CrossGuide

**Smart, Self-Pwered Road Safety System Designed for Urban & Rural Nigeria**

---

## About the project
CrossGuide is a smart zebra crossing that protects pedestrians especially scholchldren using:
- **Piezoelectric Sensors**: Detects pedestrians and vehicles and harvest footstep energy.
- **Motion sensors** to detect crossing intentions and vehicle directions.
- **LED visual alerts** to ensure pedestrians safety and incoming vehicles.
- **Self-charging battery system** for 24/7 operation.
- **Solar Hybrid System** for sustainable energy use and consistent energy supply.
- **GSM module** for real-time alerts to traffic control centers to report high-traffic or dangerous crossings.
- **Smart Data Logging**: Tracks activity to assist with roUTE plannning and traffic management.

---

## Problem Solving

**CrossGuide** addresses the critical issue of pedestrian safety in Nigeria, where road accidents are prevalent due to inadequate infrastructure and lack of awareness. By integrating smart technology, it aims to offer an energy independent , low maintenence solution that is modular and community buildable.

---

## SDG Alignment
- **SDG 3**: Good Health and Well-being - Reducing pedestrian accidents.
- **SDG 11**: Sustainable Cities and Communities - Enhancing urban infrastructure.
- **SDG 9**: Industry, Innovation, and Infrastructure - Promoting smart city solutions.
- **SDG 13**: Climate Action - Utilizing renewable energy sources.

--- 

## TECH Stack and Architecture
- **Arduino Uno**
- **Piezoelectric Discs Sensors**
- **PIR Motion Sensors**
- **LED Strip**
- **Relay Module**
- **Rechargeable 12V Battery**
- **Diodes + Capacitors (Rectifier Circuit)**
- **GSM Module (SIMB00L)**


| Component                | Description                                  |
|-------------------------|----------------------------------------------|
| Arduino Uno / ESP32     | System controller                            |
| Piezoelectric Discs     | Energy harvesting from pressure              |
| PIR + Ultrasonic Sensor | Detects motion & vehicle proximity           |
| LED Strip (12V)         | Visual road alerts                           |
| Relay Module            | Switching control for LED alerts             |
| 12V Rechargeable Battery| Stores harvested or solar energy             |
| Solar Panel (optional)  | Supplementary clean energy                   |
| GSM Module (SIM800L)    | Sends SMS with usage/alerts to authority     |
| Rectifier + Capacitors  | Converts AC piezo output to DC for storage   |
---

## Cost Estimate 

| Component                 | Estimated Cost (₦)     |
|--------------------------|-------------------------|
| Arduino Uno R3 (clone)   | ₦6,000 – ₦8,500          |
| PIR Sensor               | ₦1,200 – ₦1,800          |
| Ultrasonic Sensor        | ₦1,000 – ₦2,000          |
| LED Strip (5m)           | ₦2,500 – ₦5,000          |
| Relay Module             | ₦1,000 – ₦1,500          |
| Rechargeable Battery     | ₦4,500 – ₦9,000          |
| Piezo Discs (5 pcs)      | ₦3,000 – ₦6,000          |
| Solar Panel (optional)   | ₦2,500 – ₦5,000          |
| GSM Module (SIM800L)     | ₦4,000 – ₦7,500          |
| Cement + Sand (base tile)| ₦3,000 – ₦6,000          |
| **Total Estimate**       | **₦30,000 – ₦55,000**    |

--- 

## System Diagram

```
Piezo + Solar --> Rectifier --> Battery --> Arduino --> Relay --> LED/Buzzer
                                |
                              Sensors (PIR/Ultrasonic)
                                |
                             GSM Module (SMS Alerts)
```

---

## Features
- Self-sustaining energy system
- Traffic-aware motion response
- Modular, scalable installation
- Real-time data communication
- Safe even in off-grid areas

--- 

##  Impact Measurement Plan
- Pre/post-installation accident reports
- Pedestrian usage counters (infrared beam)
- SMS logs: daily/weekly crossing counts
- Community surveys on confidence/safety

---

##  Use Case
- Government deployments in school zones
- NGOs and urban safety organizations
- Community-driven smart city initiatives

---

##  Looking for Partners
We're actively seeking:
- City governments for pilot deployments
- Urban planners and safety NGOs
- STEM investment partners and grant sponsors

---

## Created by
**Enijeshiku Elijah Eniola** – Engineering student at KWASU  
*“Nigeria’s locally-powered smart pedestrian system — designed to save lives, one crossing at a time.”*
