# ✈️ Airline Booking Website Testing – Passengers & Add-ons

## 📌 Project Overview
This project documents the **manual testing** of an airline booking website (Scoot Airlines), focusing on two critical modules:
1. **Passengers** – entering and validating traveler details.  
2. **Add-ons** – selecting additional services (baggage, seats, meals, Wi-Fi, insurance, etc.).  

The work was conducted as part of the **Software Testing course** at the University of Danang – University of Technology and Education.  

---

## 👤 Author
- **Student:** Lưu Ngọc Yến Như – 22115053122128  
- **Instructor:** Nguyễn Thị Đức  
- **Date:** April 2025  

---

## 🛠️ Requirements Tested

### 1. Passengers
- Mandatory fields: Salutation, First Name, Last Name, Date of Birth, Nationality, Place of Residence.  
- Validation rules:  
  - No empty or duplicate passenger details.  
  - No special characters in names, max length 32 chars.  
  - Correct formats for **KrisFlyer Number** and **Passport Number**.  
  - Age verification based on type:  
    - Adult: 1926–2013  
    - Child: 2013–2023  
    - Infant: 2023–2025  
- System features:  
  - Auto-fill when logged in (Travelling Passenger).  
  - Checkbox option for “no First Name”.  
  - Prevent duplicate passengers.  
  - Session timeout after 15 minutes of inactivity.  

### 2. Add-ons
Nine services tested:  
- Baggage  
- Seat Selection  
- Meal Selection  
- Snooze Kit  
- Onboard Wi-Fi  
- BoardMeFirst  
- Change Your Flight  
- Pokémon Merchandise  
- Scootsurance  

Requirements:  
- Options and pricing vary by ticket type (ScootPlus vs Economy).  
- Services must display clear details and costs.  
- Each passenger can select services individually.  
- Updates must be reflected in the booking summary.  
- System prevents errors, invalid edits, and expired sessions.  

---

## ✅ Test Cases
- Designed **positive & negative scenarios** for each requirement.  
- Covered field validation, input constraints, duplicate handling, and session expiry.  
- Each test case documented with:  
  - Pre-conditions  
  - Input data  
  - Steps  
  - Expected results  
  - Actual results (Pass/Fail)  

---

## 📂 Repository Contents
- `Requirements/` – Detailed requirements for Passengers & Add-ons.  
- `TestCases/` – Designed test cases in tabular format.  
- `Reports/` – Execution results with Pass/Fail status.  

---

## 🚀 Tools & Techniques
- **Testing type:** Manual (Black-box).  
- **Techniques:** Equivalence Partitioning, Boundary Value Analysis.  
- **Documentation:** Microsoft Word, Excel.  

---

## 📊 Deliverables
- Requirement specifications.  
- Test case design.  
- Test execution reports.  
- Final documentation.  

---

## 🎓 Academic Context
This work is part of the **Software Testing course project** to practice requirement analysis, test design, and execution on a real-world airline booking platform.
