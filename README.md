# SynchroCare: A Smart Patient & Resource Management System

## 📌 Overview

Wenlock Hospital faces challenges in synchronizing patient movement, OT schedules, drug availability, and emergency alerts across departments like Cardiology, OT, and Pharmacy — despite having 73 digital display screens. 
  
**SynchroCare** is a full-stack-free, design simulation built using HTML, CSS, and JavaScript that addresses these issues through a modular smart display system.

This system simulates **real-time communication** between departments and provides **separate interfaces** for staff, patients, doctors, the pharmacy, and the OT wing — all with live data syncing and emergency readiness.

---

## 🔧 Features & Functionality

### 🧑‍💼 Staff Dashboard (`staff.html`)
- Displays live **clock and date**
- Shows **upcoming surgery details** in OT
- Receives **drug stock alerts** from pharmacy
- Broadcasts **Code Blue/Red emergency alerts** across all screens

### 👨‍⚕️ Doctor Screen (`doctor.html`)
- Simulated for **Cardiology department**
- Live clock and date
- Displays:
  - Current token number
  - Patient token info
  - Drug stock alerts (synced from pharmacy)
- "Next Token" button triggers green alert on the **patient screen**
- "Clear" button removes the alert after the patient is called

### 🧑‍⚕️ Patient Screen (`patient.html`)
- Shows **department**, **token number**, and **room number**
- Live clock and date
- Auto **toggles between English and Kannada**
- Green alert appears when a doctor calls a token (until cleared)

### 💊 Pharmacy Inventory (`pharmacy.html`)
- Displays **medicines and their availability**
- Updates drug stock status which reflects live on **staff and doctor screens**
- Live clock and date

### 🏥 OT Display Screen (`OT.html`)
- Shows **real-time OT schedule** with:
  - Time
  - Patient/case
  - Department
  - Room number
- Live clock and date
- Receives emergency alerts from the staff dashboard

---

## 🔁 Real-Time Simulation

All screens communicate using the browser's `localStorage` and JavaScript event listeners to simulate live updates without a server.

- Emergency alerts and drug stock updates sync instantly.
- Token movement updates reflect immediately across departments.

---

## 🌐 Technology Used

- **HTML5**
- **CSS3**
- **JavaScript**
- No external frameworks or backend — built for pure design simulation.

---

## ⚠️ Emergency System

- Supports **Code Blue** and **Code Red** alerts
- Emergency messages flash on all screens with color-coded banners
- Sent from the **Staff Dashboard**

---

## 🌍 Bilingual Support

- Patient screen automatically switches between **English** and **Kannada** every few seconds for better public understanding.

---

## 📸 Screens Provided

- Staff Dashboard Screenshot
- Patient Screen (English & Kannada)
- Doctor Screen (Cardiology)
- Pharmacy Inventory
- OT Schedule Display

---

## 📽 Demo Video  

🎥 [Click here to watch the demo video](https://drive.google.com/file/d/1oTi7egelMgedlBIyr7KUAM6mgne2OJsy/view?usp=sharing)
Will walk through all screens, interactions, and emergency syncing simulation.

---

## 💡 Project Goals

This prototype aims to:
- Reduce delays in patient navigation and staff coordination
- Use existing display infrastructure more effectively
- Improve communication and emergency responsiveness
- Prepare the system for future integration with platforms like [e-Hospital]

---

## 🧠 Developer

**Panchami Kashyap**  
Solo developer for UDAL Fellowship Design Simulation  
Passionate about solving real-world healthcare challenges through smart tech solutions.

---     
