# 🦷 DentalDesk — Doctor Portal

A responsive, private, client-side clinical portal designed for dental practitioners to manage daily appointments, patient diagnoses, prescriptions, and follow-ups.

---

## ⚡ Key Features

- **Interactive Fracture Gate**: Dynamic tooth-shatter entrance screen powered by synthesized Web Audio API sound effects (no external audio files required).
- **Personalized Access**: Dynamic clinic header displaying `Welcome Dr. [NAME]`.
- **Strict Indian Mobile Validation**: Validates 10-digit mobile numbers prefixed with standard mobile carrier digits (`6–9`) with automatic `+91` regional handling.
- **Smart Appointment Reminders**:
  - Live sound chimes when a patient's appointment time arrives.
  - Interactive on-screen toast alerts with one-click actions (*Open File*, *Mark Done*).
  - Background browser notifications for upcoming visits.
- **100% Local Privacy**: All clinical records remain stored inside browser `localStorage`. No patient data is sent to external cloud databases.
- **Backup & Restore**: Instant `.json` export and import for clinic record preservation.

---

## 🚀 Live Demo

You can access the live web console at:
https://zaveridhyan15.github.io/Dental-Desk/

---

## 📂 Project Structure

```text
├── index.html       # Single-file standalone app (UI, styles, logic, & sound synthesis)
└── README.md        # Documentation and project overview
