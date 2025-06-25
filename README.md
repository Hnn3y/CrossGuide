# CrossGuide

**Smart, Self-Powered Road Safety System Designed for Urban & Rural Nigeria**

---

## About the Project

CrossGuide is a smart pedestrian crossing system designed to reduce pedestrian accidents in Nigeria, especially in school zones and high-traffic areas. It combines renewable energy harvesting, AI-driven logic, and real-time alerts to create an adaptive safety infrastructure that works even in off-grid environments.

Key features include:
- Piezoelectric energy harvesting from footsteps or vehicle pressure
- Motion and ultrasonic sensors for detecting pedestrian intent and vehicle approach
- LED visual alerts to warn drivers
- Self-charging battery system for 24/7 operation
- Optional solar power for hybrid energy reliability
- GSM module for SMS alerts to traffic control centers
- Smart data logging for route planning and analysis
- AI-based vehicle speed detection and auto-deploy safety bump
- Crowd-based pedestrian control using people counters and wait timers

---

## Problem Solved

Nigeria records high numbers of road-related fatalities, often due to lack of visible, responsive crossing systems. Current zebra crossings are passive and frequently ignored. CrossGuide solves this by providing a proactive, self-powered, low-cost, and modular system that ensures pedestrian safety without relying on the national grid.

---

## SDG Alignment

- SDG 3: Good Health and Well-being  
- SDG 9: Industry, Innovation, and Infrastructure  
- SDG 11: Sustainable Cities and Communities  
- SDG 13: Climate Action  

---

## Technology Stack and Architecture

| Component                 | Description                                   |
|--------------------------|-----------------------------------------------|
| Arduino Uno / ESP32      | Microcontroller and logic control             |
| Piezoelectric Discs      | Harvest energy from pressure                  |
| PIR + Ultrasonic Sensor  | Detect motion and vehicle proximity           |
| LED Strip (12V)          | Visual alerts to drivers                      |
| Relay Module             | Controls high-power components                |
| Rechargeable 12V Battery | Stores energy for continuous operation        |
| Solar Panel (optional)   | Adds renewable power source                   |
| GSM Module (SIM800L)     | Sends SMS alerts and status data              |
| Laser Checkpoints        | Measure vehicle speed                         |
| AI Logic (Microcontroller-based) | Controls safety bump + crowd logic   |

---

## Estimated Cost (Nigeria-based Pricing)

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

Piezo + Solar --> Rectifier --> Battery --> Arduino --> Relay --> LED/Buzzer
|
Sensors (PIR/Ultrasonic)
|
GSM Module (SMS Alerts and Data Logging)
|
AI Logic --> Safety Bump / Crowd Control Timer

---

## Key Features

- Works without grid electricity
- Automatically responds to pedestrian activity
- Detects vehicle speed with laser sensors
- Deploys safety bump when cars overspeed
- Tracks and logs crossing activity for urban planning
- Triggers crossings based on pedestrian crowd size or wait duration

---

## Impact Measurement

- Compare accident reports before and after deployment
- Count pedestrian crossings using beam counters
- Log SMS alerts and system activity
- Conduct user surveys on safety and usability

---

## Use Cases

- High-risk school zones
- Government road safety pilot programs
- NGO-led urban safety initiatives
- Community smart infrastructure projects

---

## Call for Partners

We are seeking:
- Traffic agencies and ministries for pilot testing
- Investors and foundations supporting road safety
- Community organizations and education stakeholders
- Engineering labs for advanced prototype support

---

## Created by

**Enijeshiku Elijah Eniola (Henney)**  
Engineering Student, KWASU  

“Nigeria’s locally-powered smart pedestrian system — designed to save lives, one crossing at a time.”

---

## Repository Contents

- Wiring Diagram (PNG)
- Source Code (Arduino)
- System Architecture
- Pitch Deck (PDF)
- Demo Video (linked externally)

---

##  Links
-  [Wiring Diagram (PNG)](./schematics/crossguide_wiring.png)
-  [Source Code](./src/main.ino)
-  [Video Demo (Coming Soon)](https://example.com)
-  [Pitch Deck PDF](./docs/CrossGuide_Pitch.pdf)

---
