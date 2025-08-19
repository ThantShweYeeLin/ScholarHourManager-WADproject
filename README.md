# Scholar Hour Manager – Scholarship Hour Management System

## 👥 Team Members
- Pwint Hmon Nathar [GitHub](https://github.com/PwintHmonNathar18)
- Thant Shwe Yee Lin [GitHub](https://github.com/ThantShweYeeLin)

---

## 📖 Project Description
Scholar Hour Manager is a **Next.js web app** that helps universities manage scholarship/work-study hours.  
It provides a portal for admins, supervisors, and students to schedule, track, and approve scholarship shifts in a transparent and efficient way.

### ✨ Problems It Solves
- Manual timesheets and spreadsheets are error-prone and time-consuming.  
- Lack of visibility leads to over/under-allocation of student hours.  
- Students struggle to view assigned shifts in one place.  
- Admins find compliance reporting slow and inconsistent.  

### 🎯 Target Users
- **Admin (Scholarship Office)** – manages programs, policies, and audits.  
- **Supervisor (Department Staff)** – assigns shifts and approves hours.  
- **Scholarship Students** – view schedule, check in/out, and request leave/swap.  

---

## 🔧 Features
- Role-based login (Admin / Supervisor / Student).  
- CRUD operations for at least **3 entities**:
  - **Student** – profile, assigned program, GPA, max hours/week  
  - **Shift** – schedule with date, location, supervisor  
  - **Attendance** – check-in/out, linked to student & shift  
- Timesheet auto-generation from attendance records.  
- Requests: leave, swap, or make-up shifts.  
- Notifications (upcoming shifts, approvals).  
- Export reports (CSV/Excel) for finance and auditing.  

---

## 🗄️ Data Models
1. **Student** – id, name, program, GPA, maxHoursPerWeek  
2. **Shift** – id, date, start, end, supervisor, location  
3. **Attendance** – id, studentId, shiftId, checkIn, checkOut  

(Additional: Supervisor, Timesheet, Request, AuditLog)

---

## 📷 Screenshots
(Will be added later after UI is implemented)

---
