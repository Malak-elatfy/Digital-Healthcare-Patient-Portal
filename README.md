# 🏥 Digital Healthcare Patient Portal (HUE Simulation)

A premium, security-focused web application designed to simulate a modern, end-to-end **Healthcare Patient Portal**. Built with a futuristic glassmorphic UI, the system bridges the gap between clean frontend dashboards and complex client-side data structures, featuring embedded cryptography and a full clinic simulation layout.

---

## 💡 The Challenge & Solution
Managing sensitive medical records on the web requires strict analytical design and client-side privacy safeguards. 

This portal provides an advanced solution by storing data directly on the user's browser via encrypted structures. Before any medical record (Diagnosis, History, Medications) or personal detail is saved, it is compiled and obfuscated using an integrated dual-cryptographic routine, mirroring production-grade data privacy at the edge.

---

## 🛠️ Tech Stack & Architecture
* **Frontend UI:** HTML5, CSS3 (Advanced Custom Properties, Glassmorphism, Responsive Grid Setup)
* **Client-Side Logic:** Vanilla JavaScript (ES6+, Functional State Management, Native Storage Bridges)
* **Cryptographic Layer:** Custom Embedded `XOR Engine` (Key: `0x5A`) + `Caesar Cipher Shift` (Offset: `7`)
* **Authentication Security:** Secure Password Hashing via `DJB2 Algorithm` with anti-brute force lockout states.

---

## 🌟 Key Features

### 🛡️ 1. Cryptographic Security Engine
* **On-the-Fly Obfuscation:** Safely encrypts patient records prior to storing them in the persistent browser state, rendering local storage immune to simple data snooping.
* **Brute-Force Lockout Defense:** Features a strict 3-attempt login lockout policy for both Doctor and Patient accounts.
* **DJB2 Authentication:** Passwords are never stored in plain text; instead, they are converted into reliable cryptographic hashes during authorization.

### 👥 2. Dual-Portal View Layer
* **🩺 Doctor / Medical Board Dashboard:** Allows practitioners to register new patients, look up medical histories, diagnose conditions, write prescriptions, and review real-time statistics of booked appointments.
* **👤 Patient Self-Service Hub:** Provides patients with immediate access to their personal health file, current prescriptions, upcoming appointment queues, and password management tools.

### 📅 3. Dynamic Medical Scheduling
* Includes an interactive appointment grid system where slots can be reserved or canceled instantly, updating dashboard analytical metrics dynamically.
