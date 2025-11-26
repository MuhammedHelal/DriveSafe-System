# 🚀 DriveSafe: Autonomous & Cooperative AI System for Next-Gen Road Safety

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
* **V2V Protocol:** `[...] Specify the peer-to-peer/mesh networking protocol used for V2V communication ...`
* **Routing Service:** Integration with `[...] Google Maps API / OpenStreetMap / other ...` for dynamic route suggestions.
* **Real-time Streaming:** `[...] Firebase Realtime Database / MQTT Broker ...` for data sharing with family.

### III. Simulation & Testing
* **Simulator:** **Carla Simulator**
* **Middleware:** **Python** scripts acting as the interface between the simulation, the autonomous control logic, and the Flutter application.

---

## 👨‍💻 My Role: Principal Engineer - Autonomy and Network

My primary achievement was designing and implementing the autonomous control loop and the cooperative V2X network logic, transforming the project from a monitoring app into a fully reactive safety system.

### Key Technical Contributions:

1.  **Autonomous Control Logic:** **Designed and implemented the autonomous decision tree** to safely maneuver and park the vehicle upon driver incapacitation.
2.  **Dynamic Traffic Management Layer:** Developed the backend service that consumes V2V hazard broadcasts and interacts with the routing API to **calculate and disseminate alternative routes**.
3.  **Critical Safety Protocol Implementation:** Coded the end-to-end sequence for a critical event, ensuring synchronous triggering of the Emergency Autonomy, Ambulance Notification, and V2V Hazard Broadcast.
4.  **Cross-System Data Harmonization:** Managed data flow from multiple sources (AI models, Smart Watch, V2V Network) into a centralized state management system for accurate safety scoring.

---

## 📸 Screenshots & Demonstrations

***(Screenshots will be added here later)***

| Autonomous Parking Sequence | Dynamic Traffic Re-route Alert | Critical Safety Protocol Triggered |
| :---: | :---: | :---: |
| _[Placeholder: Screen showing "Autonomous Takeover In Progress: Parking"]_ | _[Placeholder: Map view showing a recommended detour around a disabled vehicle]_ | _[Placeholder: Critical status screen with "Ambulance Alert Sent" and "Autonomous Control Active"]_ |

---

## 🤝 Contact

**Muhammed Helal**
* **GitHub:** [MuhammedHelal](https://github.com/MuhammedHelal)
* **LinkedIn:** `[...] Your LinkedIn Profile Link ...`

Project Link: [https://github.com/MuhammedHelal/drive\_safe](https://github.com/MuhammedHelal/drive_safe)
