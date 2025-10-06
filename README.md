# RentEase – Property Listing & Rental Management System

**RentEase** is a digital property management and real estate platform designed for landlords, tenants, and agents.  
It allows users to list properties, handle rent payments, track maintenance requests, and automate reminders — all from one place.

---

### 🏡 Key Features
- Property listing with images, videos & documents  
- Rent payment & receipt generation  
- Maintenance request system  
- Tenant verification and digital lease signing  
- Agent dashboard with earnings tracking  
- Push/email notifications for rent reminders  
- Admin control panel for full management  

---

### 🧠 Tech Stack
| Layer | Technology |
|-------|-------------|
| **Frontend (Web + Mobile)** | Flutter |
| **Backend API** | Node.js + Express |
| **Database** | PostgreSQL (ReinHost Cloud / AWS RDS) |
| **Storage** | AWS S3 / ReinHost Storage |
| **Payments** | Paystack / Flutterwave |
| **Notifications** | Firebase / SMTP |
| **Hosting** | ReinHost VPS / cPanel |

---

### 🧩 System Architecture
Landlords / Tenants / Agents → Flutter App (Web + Mobile)
│
│──> Node.js Backend (ReinHost VPS)
│
│──> PostgreSQL Database
│
│──> AWS S3 / ReinHost Storage (Property Images)
│
│──> Payment Gateway (Paystack / Flutterwave)
│
└──> Firebase / SMTP (Notifications)


---

### 🔒 Security & Roles
- JWT authentication system  
- Roles: Admin, Agent, Landlord, Tenant  
- Role-based permission enforcement  
- Secure payment and encrypted tenant data  

---

### 🧾 Status
**Concept build for portfolio demonstration.**  
RentEase demonstrates expertise in PropTech systems integrating payments, listings, and role-based access.

---

### 👨🏽‍💻 Developer
**James Friday**  
📧 jamesfriday007@gmail.com  
🌐 GitHub: [https://github.com/CityRock007](https://github.com/CityRock007)
