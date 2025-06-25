
> ⚠️ **Note:** Due to confidentiality and company policy, source code is not published in this repository. This README serves as a technical summary of my work.

# Internship Project Summary – CRTS System

📅 Internship Period: October 2024 – March 2025

📅 Project Hands-on Period: January 2025 – March 2025
🏢 Company: Silverlake Innovation Partners Sdn Bhd  
👨‍💻 Role: Full Stack Web Developer Intern  
🎓 Final Year Project / Internship Completion – Bachelor of Computer Science (Software Development), UTeM

---

## 🔧 Tech Stack
- **Frontend**: Angular 17 (standalone components)
- **Backend**: Spring Boot
- **Database**: MySQL
- **Authentication**: JWT stored via `sessionStorage`
- **Email Integration**: SMTP with Outlook

---

## 🧠 Project Overview
During my internship, I contributed to the development of an internal web-based **CRTS System** (Case Registration Tracking System). It’s designed to help manage users, parameters, change requests, assignments, tracking, and reporting features with proper role-based access control.

I worked on both frontend and backend tasks throughout the SDLC – from planning, designing, to actual development.

---

## 📌 Project Scope
During my internship, I was assigned to the **Registration Module**, which forms the foundation of the internal web-based CRTS (Change Request Tracking System).

Although the scope focused on one module, the work involved significant architectural and logic-based decisions — such as component reusability, access control, and dynamic form behavior — which laid the groundwork for the rest of the system.

---

## 🧩 Registration Module – Key Contributions

### 🔹 Parameter Handling
- CRUD implementation for dynamic system parameters like:
  - Partner list
  - Module configurations
  - LOA / PO / Assessment / Fee statuses
- Designed forms using Angular Reactive Forms with validation

### 🔹 User Management
- Developed user registration flow, including:
  - User details form
  - Module assignment modal with editable selections
  - `is_active` vs `selected` logic separation
- Reused form logic for update functionality

### 🔹 Access Control Logic
- Applied dynamic role & team-based permissions:
  - Support Team Member editable profiles
  - Admin-only toggles for user activation
- Authenticated with JWT stored in sessionStorage

### 🔹 UI/UX Enhancements
- Modular component structure
- Clean separation of services and form logic
- Feedback alerts and status indicators

---

## 💡 What I Learned
- Full-stack development using Angular & Spring Boot
- Clean component structuring with Angular standalone components
- Session-based JWT handling & role-based access logic
- How to manage reusable UI & maintain DRY (Don't Repeat Yourself) principles
- Working with real project requirements, deadlines, and collaborative review

---

## 📌 Notes
This summary reflects my hands-on contribution to a real-world production system.

---

