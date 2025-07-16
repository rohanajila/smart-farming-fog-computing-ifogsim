# Smart Farming with Fog Computing – iFogSim Simulation

## 📘 Overview
This project proposes and simulates a fog-enabled IoT architecture for smart farming. By leveraging **Fog Computing** and the **iFogSim** simulator, we demonstrate how placing computational resources closer to the edge improves **latency**, **energy efficiency**, and **resource utilization** in real-time crop monitoring.

## 🌾 Project Objectives
- Enable **smart agriculture** using real-time sensor data.
- Use **fog nodes** to process data locally and reduce cloud dependency.
- Simulate a **200-acre farm** split into 4 zones with IoT sensors and fog nodes.
- Validate improvements in latency, energy consumption, and bandwidth via **iFogSim** simulations.

## 🧱 System Architecture
- **Sensor Layer:** Soil moisture, temperature, humidity, pH, and light sensors across zones.
- **Fog Layer:** Edge nodes per zone for real-time analysis and alerts.
- **Cloud Layer:** Long-term data storage, machine learning-based analysis, and system orchestration.

## 🧪 Simulated Components
- Virtual sensors generating environmental data.
- Fog nodes for localized processing (Zone-wise deployment).
- iFogSim used for modeling network latency, energy consumption, and data flow.

## 📊 Key Results (Simulation)
| Metric                        | Value             |
|------------------------------|-------------------|
| Total Execution Time         | 726 ms            |
| Avg. Sensor Data Delay       | ~102 ms           |
| CPU Execution Delay (alerts) | < 3 ms            |
| Cloud Energy Consumption     | 2.72 million J    |
| Fog Node Energy (per zone)   | ~199,000 J        |
| Cloud Cost Estimate          | $78,851.18 USD    |
| Total Network Usage          | 19,931.5 units    |

## ⚙️ Technologies Used
- **Java**, **iFogSim**, **CloudSim**
- **MQTT**, **Zigbee**, **LoRaWAN**
- **Apache Kafka**, **Apache Spark**
- **AWS IoT**, **Docker**, **Microservices Architecture**

## 🛠️ Applications Enabled
- Smart irrigation based on moisture sensors.
- Crop health alerts using pH and light sensors.
- Forecasting crop yield using historical cloud data.
- Environment monitoring across farm zones.

## 📂 Repository Structure
- `src/`: Java simulation file using iFogSim.
- `report/`: Project PDF with system design and evaluation.

## 🧑‍💻 Author
**Rohan Narayan Ajila**  
MSc Cloud Computing  
National College of Ireland  
x22249729@student.ncirl.ie

## 📃 License
None

