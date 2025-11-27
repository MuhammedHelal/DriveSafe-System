# 🚀 Fruits Hub: A Full-Scale E-Commerce Ecosystem Built with Flutter, Firebase, & Supabase

<p align="center">
  <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" alt="Flutter Badge"/>
  <img src="https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white" alt="Dart Badge"/>
  <img src="https://img.shields.io/badge/Arabic-RTL_Only-1E88E5?style=for-the-badge&logoColor=white" alt="Arabic RTL Badge"/>
</p>

## ✨ Project Showcase: Defining Modern Mobile Commerce

**📢 Note: This application currently supports the Arabic language (Right-to-Left/RTL) only, as it is specialized for a local brand. English language support is architecturally planned and will be added in a future update.**

**Fruits Hub** is a robust, production-ready full-stack E-commerce application engineered from the ground up using **Flutter**. This project is a specialized solution tailored for the Middle East, implementing full **Right-to-Left (RTL)** layouts across the entire application. It boasts **dual backend support** (**Firebase** and **Supabase**) and includes a dedicated, **enterprise-grade network layer** and **multi-gateway payment integration (Stripe & PayPal)**.

This is a complete, scalable, and highly flexible solution showcasing expert-level handling of RTL design, complex architectural patterns, and secure financial integrations.

---

## 🖼️ Visual Preview

> **Note:** Replace the placeholders below with actual screenshots and a demo link! The screenshots should clearly show the Arabic text and RTL layout.

| Onboarding Screen (Arabic) | Home Screen (Arabic) | Product Details (RTL) 

[Image of Product Details Screen]
 | Cart & Checkout (RTL) 

[Image of Shopping Cart and Checkout]
 |
| :---: | :---: | :---: | :---: |
| | | | |

---

## 💎 Key Features: What Users Experience

Every feature in Fruits Hub is designed for a frictionless shopping journey, fully optimized for the Arabic user:

* **🇸🇦 Exclusive Arabic Support (RTL Default):** The entire UI is built and optimized for the **Right-to-Left (RTL) reading direction**. The underlying architecture is designed for quick future localization (i18n) expansion to English.
* **🛡️ Secure Authentication Flow:** Complete user registration, login, and session management using robust Firebase Auth **or Supabase Auth**.
* **🍎 Dynamic Product Catalog:** Browse categorized products, view featured items, and manage inventory state dynamically from the database.
* **🔍 Advanced Search & Filtering:** High-performance filtering logic to allow users to quickly find products by name, category, or attributes.
* **🛒 Comprehensive Cart Management:** Real-time updates to quantities, removal of items, and automatic calculation of totals/subtotals.
* **💳 Multi-Gateway Payment System:** Implemented secure payment processing via **Stripe** and **PayPal SDKs**, providing users with trusted checkout options.
* **📦 Order History & Tracking:** Dedicated screens for users to review past purchases and check the current status of active orders.
* **⚙️ User Profile Management:** Allowing users to update personal details, change passwords, and manage addresses.

---

## ⚙️ The Engineering Achievement: What I Built

This section highlights the technical complexity and sophisticated architectural patterns implemented:

### 1. **RTL-First Architecture & Clean Code**
* The entire UI framework was developed with **RTL as the native default direction**, ensuring perfect mirroring of elements (icons, app bar, drawers, etc.) across all screens using Flutter's `Directionality` system.
* Implemented **Clean Architecture** principles to enforce strict separation of concerns, ensuring the code is modular, reusable, and easily testable.
* Employed the **Repository Pattern** to abstract data sources, facilitating the easy **integration of both Firebase and Supabase**.

### 2. **Mastery of State Management**
* Utilized the **BLoC Pattern** (Business Logic Component) for immutable state and reliable UI rendering. This was critical for managing complex asynchronous operations and persistent data like the shopping cart.

### 3. **Enterprise-Grade Network Layer**
* Designed and implemented a dedicated network layer (using **Dio**) complete with **Interceptors** for logging, token refresh, and centralized error handling, ensuring robust and scalable API communication.

### 4. **Dual Backend Flexibility (Firebase & Supabase)**
* **Modular Backend Services:** Structured data service modules to allow quick switching between **Firebase Firestore** and **Supabase PostgREST**, showcasing adaptability to different backend technologies.

### 5. **Secure Multi-Gateway Payment Implementation**
* Integrated **Stripe SDK** and **PayPal SDK** for end-to-end transaction handling, demonstrating expertise in managing complex financial integrations and adherence to security best practices.

### 6. **Cross-Platform Readiness**
* The application is built with a single codebase designed for native performance on **iOS, Android, and Web**, demonstrating high proficiency in Flutter's multi-platform capabilities.

---

## 🛠️ Tech Stack

| Component | Technology | Role in the Project |
| :--- | :--- | :--- |
| **Mobile/Web Framework** | `Flutter (Dart)` | Foundation for cross-platform UI/UX. |
| **Language Support** | `flutter_localizations (Arabic RTL)` | Exclusive Arabic Language and RTL system. |
| **Backend Services (Dual)** | `Google Firebase` & `Supabase` | Authentication, Database, and File Storage. |
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
