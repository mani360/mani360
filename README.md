# Hi, I'm Manitosh Bepari 👋

### Lead Software Engineer | Android, Kotlin & Java | Software Architecture | Biometrics, PKI & Device Integration

I’m a **Lead Software Engineer with 8+ years of experience in native Android development**, currently working across software architecture, technical leadership, project delivery, biometric device integration, and application security.

I enjoy solving engineering problems that sit at the intersection of:

**Android Applications × External Devices × Biometrics × Security**

My work combines hands-on development with architecture decisions, developer guidance, technical problem solving, integration planning, and software delivery.

---

## 👨‍💻 What I Work On

- 📱 Native Android application development
- 🏗️ Android application and system architecture
- 👥 Technical leadership and developer guidance
- 🔌 USB and external hardware integration
- 👆 Fingerprint biometric applications
- 👁️ Iris and face biometric workflows
- 🔐 PKI, certificates, and digital signatures
- 🔑 RSA and elliptic-curve cryptography
- 🛡️ Secure key management and Android Keystore
- 🔒 Hardware-backed key operations / HSM concepts
- 🚀 Application release and production support
- 🧩 SDK and device integration troubleshooting

---

## 🛠️ Core Technology Stack

### Android

![Android](https://img.shields.io/badge/Android-3DDC84?logo=android&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?logo=kotlin&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?logo=openjdk&logoColor=white)
![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-4285F4?logo=jetpackcompose&logoColor=white)

- Android SDK
- Kotlin
- Java
- Jetpack Compose
- XML Layouts
- Data Binding
- MVVM
- Coroutines
- Flow / StateFlow
- Dependency Injection
- KAPT / KSP
- Firebase

---

### Architecture & Engineering

- MVVM
- Repository Pattern
- Use Cases
- Modular Architecture
- Interface-driven design
- State management
- Concurrency control
- Failure recovery
- SDK abstraction
- Device lifecycle management
- Code review
- Technical risk analysis

---

### Device & Biometric Integration

- USB device integration
- Android USB Host APIs
- Vendor SDK integration
- JNI / native library integration
- Fingerprint capture
- Fingerprint enrollment
- Verification
- Identification
- ISO biometric template workflows
- Iris integration
- Face biometric integration

---

### Security & PKI

![Security](https://img.shields.io/badge/Security-PKI%20%7C%20Crypto-blue)

- PKI
- X.509 certificates
- Digital signatures
- RSA
- ECC
- ECDSA
- SHA-256
- Android Keystore
- Secure key lifecycle management
- Hardware-backed key concepts
- YubiHSM
- Certificate-chain processing

---

## 🏗️ Engineering Focus

I’m especially interested in designing software where Android applications communicate with external hardware.

These systems require more than normal application development because hardware can:

- disconnect unexpectedly
- fail during operations
- require runtime permissions
- return incomplete or poor-quality data
- depend on vendor SDKs
- interact with native libraries
- require secure key and certificate handling

My preferred approach is to keep these concerns behind clear application boundaries:

```text
UI
 │
 ▼
ViewModel
 │
 ▼
Use Cases
 │
 ▼
Repository
 │
 ├──────────────┐
 ▼              ▼
Device Layer   Security Layer
 │              │
 ▼              ▼
USB / SDK     Keystore / PKI
```

This keeps applications easier to maintain, test, and extend.

---

## 🚀 Featured Project

### 🔐 SecureDeviceBridge

**Android reference architecture for device integration, biometric workflows, failure recovery, and secure key operations.**

🔗 https://github.com/mani360/secure-device-bridge

The project is designed to demonstrate:

- Kotlin-first Android architecture
- Jetpack Compose
- MVVM
- Coroutines and StateFlow
- device abstraction
- explicit hardware state management
- simulated biometric capture
- failure simulation
- Android Keystore
- digital signatures
- certificate processing
- automated testing

> This is an independently developed portfolio project and does not contain proprietary employer, customer, or commercial SDK code.

---

## 🧠 Engineering Leadership

My current work also includes:

- translating requirements into engineering tasks
- designing application architecture
- guiding developers
- reviewing technical approaches
- identifying technical risks
- resolving application/SDK/device integration issues
- coordinating development activities
- supporting project delivery
- maintaining engineering quality through review and testing

One principle I value:

> **A technical lead should reduce uncertainty for the team while creating enough architectural clarity for developers to make good decisions independently.**

---

## 📚 Engineering Topics I Write About

I’m building technical content around:

### Android & Device Integration

Architecture patterns for applications communicating with biometric and USB hardware.

### Engineering Leadership

Requirement decomposition, technical risk, developer guidance, integration, and delivery.

### PKI for Application Developers

Certificates, digital signatures, RSA, ECC, HSMs, Android Keystore, and secure key management.

### Testable Hardware Architecture

Designing device-connected applications that remain testable without physical hardware.

---

## 🔭 Currently Exploring

- Modern Android architecture
- Jetpack Compose
- Kotlin Coroutines and Flow
- Hardware abstraction patterns
- Device integration reliability
- Android security
- PKI architecture
- Hardware-backed cryptography
- Application architecture for biometric systems
- Software project leadership

---

## 📊 GitHub

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=mani360&show_icons=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=mani360&layout=compact)

---

## 🤝 Connect With Me

**LinkedIn**  
https://www.linkedin.com/in/manitosh-bepari-ba77a8a3/

**GitHub**  
https://github.com/mani360

---

### Building reliable software across Android, hardware, biometrics, and security.
