# 🚀 Fruits Hub: A Full-Scale E-Commerce Ecosystem Built with Flutter, Firebase, & Supabase

<p align="center">
  <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" alt="Flutter Badge"/>
  <img src="https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white" alt="Dart Badge"/>
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" alt="Firebase Badge"/>
  <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white" alt="Supabase Badge"/>
</p>

## ✨ Project Showcase: Defining Modern Mobile Commerce

**Fruits Hub** is a robust, production-ready full-stack E-commerce application engineered from the ground up using **Flutter**. It boasts **dual backend support** (**Firebase** and **Supabase**) and features a dedicated, **enterprise-grade network layer**. This project goes beyond basic implementation, serving as a comprehensive demonstration of professional development workflows, advanced state management, **multi-gateway payment integration (Stripe & PayPal)**, and sophisticated architectural flexibility.

This is a complete, scalable, and highly flexible solution showcasing the power of Dart and Flutter in building complex, high-performance mobile and web applications ready for real-world deployment.

---

## 🖼️ Visual Preview

> **Note:** Replace the placeholders below with actual screenshots and a demo link!

| Onboarding Screen | Home Screen | Product Details | Cart & Checkout |
| :---: | :---: | :---: | :---: |
| | | 

[Image of Product Details Screen]
 | 

[Image of Shopping Cart and Checkout]
 |

---

## 💎 Key Features: What Users Experience

Every feature in Fruits Hub is designed for a frictionless shopping journey, now supporting flexible and secure transactions:

* **🛡️ Secure Authentication Flow:** Complete user registration, login, and session management using robust Firebase Auth **or Supabase Auth**.
* **🍎 Dynamic Product Catalog:** Browse categorized products, view featured items, and manage inventory state dynamically from the database.
* **🔍 Advanced Search & Filtering:** High-performance filtering logic to allow users to quickly find products by name, category, or attributes.
* **🛒 Comprehensive Cart Management:** Real-time updates to quantities, removal of items, and automatic calculation of totals/subtotals.
* **💳 Multi-Gateway Payment System:** Implemented secure payment processing via **Stripe** and **PayPal SDKs**, providing users with trusted checkout options.
* **📦 Order History & Tracking:** Dedicated screens for users to review past purchases and check the current status of active orders.
* **⚙️ User Profile Management:** Allowing users to update personal details, change passwords, and manage addresses.

---

## ⚙️ The Engineering Achievement: What I Built

This section highlights the technical complexity and sophisticated architectural patterns implemented, underscoring the enterprise-grade quality of the solution:

### 1. **Robust Architecture & Clean Code**
* Implemented **Clean Architecture** principles to enforce strict separation of concerns, ensuring the code is modular, reusable, and easily testable.
* Employed the **Repository Pattern** to abstract data sources, facilitating the easy **integration of both Firebase and Supabase**.
* Developed a high-quality, reusable **Widget Library** for rapid and consistent UI development across all screens.

### 2. **Mastery of State Management**
* Utilized the **BLoC Pattern** (Business Logic Component) for immutable state and reliable UI rendering. This was critical for managing complex asynchronous operations like fetching product lists and updating the persistent shopping cart state in a predictable, stream-based manner.

### 3. **Enterprise-Grade Network Layer**
* Designed and implemented a dedicated network layer (e.g., using **Dio** or a similar package) complete with **Interceptors** for logging, token refresh, and centralized error handling. This ensures robust, secure, and scalable API communication.

### 4. **Dual Backend Flexibility (Firebase & Supabase)**
* **Modular Backend Services:** Structured data service modules to allow quick switching between **Firebase Firestore** (NoSQL) and **Supabase PostgREST** (PostgreSQL/SQL), demonstrating adaptability to different database technologies and client requirements.
* **Real-time Data Sync:** Configured listeners for both backends to provide a dynamic user experience where product or cart changes are reflected instantly.

### 5. **Secure Multi-Gateway Payment Implementation**
* Integrated **Stripe SDK** and **PayPal SDK** for end-to-end transaction handling, demonstrating expertise in managing complex financial integrations and adherence to security best practices.

### 6. **Cross-Platform Readiness**
* The application is built with a single codebase designed for native performance on **iOS, Android, and Web**, demonstrating high proficiency in Flutter's multi-platform capabilities.

---

## 🛠️ Tech Stack

| Component | Technology | Role in the Project |
| :--- | :--- | :--- |
| **Mobile/Web Framework** | `Flutter (Dart)` | Foundation for cross-platform UI/UX. |
| **Backend Services (Dual)** | `Google Firebase` & `Supabase` | Authentication, Database, and File Storage. |
| **Database** | `Cloud Firestore / PostgreSQL` | Flexible data management (NoSQL or SQL). |
| **State Management** | `BLoC / flutter_bloc` | State control and robust business logic injection. |
| **Networking** | `Dio + Interceptors` | High-performance, enterprise-grade networking layer. |
| **Payment** | `Stripe SDK` & `PayPal SDK` | Secure, multi-option financial transaction processing. |

---

## 🚀 Getting Started

To run this magnificent piece of engineering on your machine:

1. **Clone the Repository:**
    ```bash
    git clone [https://github.com/MuhammedHelal/fruits-hub_Full-ECommerce-App-in-Flutter.git](https://github.com/MuhammedHelal/fruits-hub_Full-ECommerce-App-in-Flutter.git)
    cd fruits-hub_Full-ECommerce-App-in-Flutter
    ```
2. **Fetch Dependencies:**
    ```bash
    flutter pub get
    ```
3. **Setup Backend:**
    * Configure either a **Firebase** project OR a **Supabase** project.
    * Place the platform-specific configuration files (`google-services.json` or Supabase keys) in the appropriate directories and environment variables.
4. **Run the App:**
    ```bash
    flutter run
    ```

## 🤝 Contact

**Muhammed Helal**
* **GitHub:** [MuhammedHelal](https://github.com/MuhammedHelal)
* **LinkedIn:** https://www.linkedin.com/in/mohamed-ashraf-4079a8392/
* **Phone:** +201033809569

Project Link: [fruits-hub_Full-ECommerce-App-in-Flutter](https://github.com/MuhammedHelal/fruits-hub_Full-ECommerce-App-in-Flutter)
