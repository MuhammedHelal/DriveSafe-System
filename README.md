# 🚦 DriveSafe: Integrated V2X and AI System for Complete Driver & Road Safety

A highly advanced graduation project that integrates **AI-powered driver monitoring** with **Vehicle-to-Vehicle (V2V) communication** and an **Automated Emergency Response System with Autonomous Control** to protect the driver, notify emergency services, and manage surrounding traffic.

---

## 🌟 System Pillars: Safety, Autonomy, and Cooperation

The DriveSafe system covers every phase of a critical incident, from detection to autonomous resolution, ensuring maximum safety for the driver and the surrounding vehicles.

| Feature Category | Description | Technical Implementation Highlight |
| :--- | :--- | :--- |
| **🚨 Autonomous Takeover & Parking** | **CRITICAL SAFETY PROTOCOL:** If the driver is detected as unconscious or incapacitated, the system initiates **autonomous control**, maneuvering the vehicle to a **safe stop** and **parking it** out of traffic flow. | Required implementation of low-level **vehicle control commands** via the Carla API bridge. |
| **🗺️ Dynamic Traffic Re-routing** | Uses the V2V network to broadcast the location and status of the disabled vehicle. The system integrates with a mapping service to **re-calculate and suggest optimal routes** for other nearby drivers to avoid the hazard zone. | Integrated with a **Routing Service API** to dynamically inject a high-priority hazard avoidance zone. |
| **🧠 Multi-Model AI Monitoring** | Uses multiple **TFLite models** for real-time detection of fatigue, distraction (e.g., phone use), and head pose from the camera feed. | Achieved high FPS processing through optimized, concurrent ML model inference. |
| **🚑 Automated Emergency Response** | Triggers an immediate alert to **emergency services (Ambulance)** upon critical detection, transmitting the vehicle's **GPS coordinates**, physiological data, and driver ID. | Implemented the secure API call logic with precise geographic data transmission. |
| **V2V Proximity Alerts** | Peer-to-peer communication between DriveSafe-enabled vehicles to instantly share localized danger alerts (e.g., rapid braking, autonomous parking events). | Utilized `[...] MQTT / Wi-Fi Direct / other P2P protocol ...` for low-latency data exchange. |
| **⌚ Smart Watch Data Fusion** | Integrates physiological data (Heart Rate, HRV) with visual AI analysis to generate the final, weighted **Driver Safety Score**. | Developed a robust communication service (e.g., Bluetooth LE) for reliable wearable data acquisition. |
| **🕹️ Carla Simulation Integration** | All autonomous and communication features were validated within the **Carla Simulator** to prove safety and functionality under complex, dynamic, and critical driving scenarios. | Successfully established a stable, low-latency control and data bridge. |

---

## 💻 Technologies & System Architecture

This project required expertise across Mobile, AI, Robotics/Autonomy, and Network Communication domains.

### I. Mobile & AI Deployment
* **Frontend Framework:** **Flutter** (Dart)
* **AI Deployment:** **TFLite** (TensorFlow Lite)
* **Core Libraries:** `camera`, `geolocator`, `flutter_bluetooth_serial`.

### II. Control & Network Communication
* **Vehicle Control Interface:** Python API for direct communication with the Carla vehicle control system (steering, throttle, brake) when in autonomous mode.
* **Routing Service:** Integration with Google maps for dynamic route suggestions.
* **Real-time Streaming:** Firebase Realtime Database and Firebase FCM for data sharing with family.

### III. Simulation & Testing
* **Simulator:** **Carla Simulator**
* **Middleware:** **Python** scripts acting as the interface between the simulation, the autonomous control logic, and the Flutter application.

---

## 👨‍💻 My Role: Full-Stack Mobile Developer & AI Specialist

My role encompassed the **entire development lifecycle**, including the creation of the user-facing application, the core safety logic, and the integration of the Machine Learning models. I single-handedly managed the transformation of research concepts into a real-time, functioning safety system.

### Key Technical Contributions:

1.  **Full Flutter Application Development:**
    * Designed and implemented the entire **user interface (UI/UX)**, focusing on a driver-friendly, high-contrast, non-distracting experience.
    * Built the **core application logic**, including state management, local data storage, and asynchronous data processing across multiple threads.
2.  **AI Model Deployment and Optimization:**
    * Responsible for the deployment pipeline, including quantization and optimization of the **multiple AI models** for efficient, low-latency execution using **TFLite** within the Flutter environment.
    * Developed the concurrent processing logic in Dart to handle the real-time camera feed and run multiple AI models simultaneously.
3.  **Critical System Logic Integration:**
    * Implemented the proprietary **Sensor Fusion Algorithm** that combines AI predictions, Smart Watch data, and V2V alerts into the single, weighted **Driver Safety Score**.
    * Coded the **Emergency and Autonomous Control Logic**, including the sequencing of the **Autonomous Takeover**, GPS location capture, and immediate **Ambulance/V2V broadcasts**.
4.  **External System Integration:**
    * Managed the communication bridges for the **Carla Simulator**, **V2V Peer-to-Peer Network**, and **Smart Watch data acquisition**, ensuring reliable data exchange across all components.

---

## 🤝 Contact

**Muhammed Helal**
* **GitHub:** [MuhammedHelal](https://github.com/MuhammedHelal)
* **LinkedIn:** https://www.linkedin.com/in/mohamed-ashraf-4079a8392/
* **Phone:** +201033809569


Project Link: [[https://github.com/MuhammedHelal/drive\_safe](https://github.com/MuhammedHelal/drive_safe](https://github.com/MuhammedHelal/drive_safe-Graduation-Project))
