# SmileWorksApp – Backend

SmileWorksApp is a full-stack dental practice management platform developed by a team of six entry-level developers under the mentorship of two experienced software engineers. This project was built as part of a structured cohort program to simulate a real-world collaborative engineering environment.

The platform is designed to serve dental clinics with tools for managing patients, appointments, treatments, inventory, billing, insurance, and staff operations. The backend powers secure role-based access, real-time patient data flow, and integration between multiple modules essential for daily clinic operations.

## 🧩 MVP Modules Implemented

We scoped and built the following core modules as part of the MVP (Minimum Viable Product):

1. ✅ Treatment Plan Tracking  
2. ✅ Insurance Verification System  
3. ✅ Patient Recall System  
4. ✅ X-ray and Image Management  
5. ✅ Procedural Cost Estimation  
6. ✅ Supply Inventory Management  
7. ⚠️ Patient Education Content System *(Planned, not implemented in MVP)*

## 🧠 System Architecture & Tech Stack

- **Frontend:** React.js + Next.js  
- **Backend:** Node.js + Express.js  
- **Database:** MongoDB  
- **Deployment/Containers:** Docker (for local containerization)  
- **Dev Tools:** GitHub, Postman, VS Code  

## 🧪 Application Flow

This platform is **not publicly accessible**. Staff credentials are provisioned by administrators. No self-registration is allowed — users log in with assigned credentials.

### 🏥 Key Functional Pages (Backend-Enabled):

#### 📊 Dashboard
- Welcome message with user name and today’s date
- Appointment summary: total, cancelled, missed
- Table of today’s appointments with time, patient, and reason
- Weekly appointment trend visualized as a bar chart
- Quick access to features: cost estimation, new patient registration, start treatment

#### 👤 Patients
- Search patients by name, ID, or DOB
- View basic details (name, phone, address, DOB)
- Create new patient records

#### 🦷 Treatments
- View patient treatment and billing history
- Start new treatments and log as part of patient record
- Cost estimation based on procedure (e.g., braces, fillings, cleaning)
- Edit patient details and manage treatment progress

#### 📦 Inventory & Orders
- Table of supplies: product name, stock, threshold, price, category
- Add new products and reorder low-stock items
- Monitor usage frequency and brand/category grouping

#### 🧾 Insurance & Billing
- Record insurance details, eligibility, and cost breakdown
- Generate billing information per treatment
- Validate coverage and reduce claim errors

#### 📅 Scheduling
- Staff can create and assign appointments
- Appointments categorized by status (upcoming, ongoing, done, cancelled)
- Two viewing modes: day view and week view
- Filter by doctor, time, and date

#### 👥 Users & Admin
- Admins manage clinic staff: hygienists, dentists, nurses, front desk, etc.
- Staff accounts include name, email, phone, and role-based access

## 💡 My Contributions
As part of the backend team, I:
- Implemented RESTful API endpoints for treatment and inventory modules
- Developed cost estimation logic based on procedure type
- Built CRUD logic for users, patients and schedules
- Collaborated on MongoDB data modeling and API testing with Postman
- Participated in sprint planning, stand-ups, and code reviews with mentors and peers

---

> This project was a collaborative learning experience focused on building production-level systems under mentorship. It demonstrates end-to-end understanding of backend development in a secure, modular, healthcare-oriented system.

