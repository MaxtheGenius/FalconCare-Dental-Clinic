# FalconCare Dental Clinic

FalconCare is a comprehensive web-based dental clinic simulator designed to support the practical training of Healthcare Assistant students. The platform replicates the real workflow of a modern dental clinic, guiding users through patient intake, clinical exploration, odontogram management, appointment scheduling, and radiographic analysis.

---

## 🚀 Project Overview

FalconCare simulates the full operational flow of a dental clinic, from the first patient visit to resource planning and clinical documentation.  
It is built for educational environments, enabling students to practice real clinical procedures in a safe, structured, and interactive digital ecosystem.

The application is divided into three core phases:

1. **Initial Registration** – Personal data, billing information, and reason for consultation.  
2. **Clinical Exploration (Odontogram)** – Interactive graphical tool to record dental pathologies.  
3. **Clinical History** – Medical background, allergies, medication, and lifestyle habits.

---

## 🎯 Key Features

### **1. Patient Intake**
- Complete registration form (personal data, billing, consultation reason).
- Accessible from the agenda when creating or selecting a patient.

### **2. Interactive Odontogram**
- Full dental chart with 32 adult teeth and 5 surfaces per tooth.
- Color-coded protocol:
  - **Red:** Existing pathology (e.g., caries)
  - **Blue:** Completed treatments
- Symbols for extractions, prosthetics, and implants.
- Automatic saving of findings into the patient’s clinical history.

### **3. Clinical History**
- Vertical timeline of visits, treatments, allergies, medication, and radiographs.
- Direct access to uploaded documents and previous odontograms.
- Automatic creation of visit records from the agenda.

### **4. Smart Appointment Scheduling**
- Daily and weekly views with drag‑and‑drop functionality.
- Two fixed boxes (treatment rooms) with assigned doctors.
- Automatic duration assignment based on pathology type.
- Quick actions to navigate directly to patient history.

### **5. Radiograph Repository**
- Upload, preview, and manage radiographic images.
- High‑fidelity viewer with zoom and annotation tools.

### **6. Inventory Management (Optional Objective)**
- Material tracking per treatment.
- Alerts for low stock.
- Supplier management and automated material lists.

---

## 🧩 System Design

### **Wireframes & Navigation**
FalconCare includes a complete set of wireframes covering:
- Dashboard  
- Patient profile  
- Odontogram  
- Clinical history  
- Agenda  
- Radiology viewer  

Navigation is supported by:
- Global sidebar  
- Breadcrumbs  
- Quick actions  
- Internal workflow transitions (e.g., Patient → Odontogram → History → Radiographs)

### **Database Structure**
The database includes entities for:
- Patients  
- Visits  
- Treatments  
- Materials  
- Odontogram records  
- Radiographs  

### **Use Case Diagram**
Illustrates how clinical modules interact with the system and AI components to optimize educational workflows.

### **Gantt Diagram**
Project planning includes parallel task execution across the three team members, managed through GitHub Issues.

---

## 🎨 Branding & UI/UX

### **Typography**
- **Architects Daughter** – Chosen for its handwritten feel, balancing clinical precision with an educational environment.

### **Color Palette**
- **Intense Cyan (#00d2da):** Modern, energetic, and hygienic.  
- **Black (#000000):** Professional contrast and clarity.  
- **White (#FFFFFF):** Clean and essential for clinical readability.

### **Logo**
A stylized falcon inspired by dental shapes, symbolizing precision, speed, and modern clinical technology.

---

## 💼 Market Analysis

FalconCare positions itself as an innovative educational tool, differentiating from commercial dental software such as:
- **Gesden** – Strong administrative features but complex.  
- **Clinic Cloud** – Cloud‑based with a clean interface.  
- **Dentidesk** – Simple and intuitive odontogram focus.

FalconCare stands out by integrating **AI‑enhanced decision support**, predictive pathology analysis, and automated material suggestions.

---

## 💰 Monetization Strategy

### **SaaS Educational Model**
Annual licensing for vocational training centers, scaled by student volume.

### **SaaS Clinical (Freemium)**
Free basic version for clinics, with premium AI features available via subscription.

### **AI Credit System**
Pay‑per‑use credits for predictive analysis and automated material recommendations.

### **Marketplace Integration**
Commission‑based system for ordering materials through partnered suppliers.

---

## 👥 Development Team

**Speed Falcons — Development Team**

- **Adrián**  
- **Patricia**  
- **Maxime**  

Project deadline: **May 22, 2026**
