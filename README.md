# SmileWorksApp – Backend

SmileWorksApp is a full-stack dental practice management platform developed by a team of six entry-level developers under the mentorship of two experienced software engineers. This project was built as part of a structured cohort program to simulate a real-world collaborative engineering environment.

The platform is designed to serve dental clinics with tools for managing patients, appointments, treatments, inventory, billing, insurance, and staff operations. The backend powers secure role-based access, real-time patient data flow, and integration between multiple modules essential for daily clinic operations.

---

## 🚀 Getting Started

> **Note:** This project was designed to run in a Dockerized environment. If you prefer to run it without Docker, follow the steps below. Some setup steps may vary based on team-specific configuration.

### Prerequisites
- Node.js (v16+)
- MongoDB (local or cloud instance like MongoDB Atlas)
- Postman (optional, for testing APIs)

### Local Setup (Without Docker)

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Shittu24/smile_works_app_backend.git
   cd smile_works_app_backend
   ```

2. **Install Dependencies**
   ```bash
   npm install
   ```

3. **Create Environment Variables**
   Create a `.env` file in the root directory and add the following (or your team’s configuration):

   ```
   PORT=5000
   MONGO_URI=mongodb://localhost:27017/smileworks
   JWT_SECRET=your_jwt_secret
   ```

4. **Start the Server**
   ```bash
   npm run dev
   ```

5. **API Runs On**
   Visit `http://localhost:5000/api` or test endpoints using Postman.

### Running with Docker (Optional)

If Docker is installed and configured, you can use:

```bash
docker-compose up --build
```

---

## 🧩 MVP Modules Implemented

We scoped and built the following core modules as part of the MVP (Minimum Viable Product):

1. ✅ Treatment Plan Tracking  
2. ✅ Insurance Verification System  
3. ✅ Patient Recall System  
4. ✅ X-ray and Image Management  
5. ✅ Procedural Cost Estimation  
6. ✅ Supply Inventory Management  
7. ⚠️ Patient Education Content System *(Planned, not implemented in MVP)*

---

## 🧠 System Architecture & Tech Stack

- **Frontend:** React.js + Next.js  
- **Backend:** Node.js + Express.js  
- **Database:** MongoDB  
- **Deployment/Containers:** Docker  
- **Dev Tools:** GitHub, Postman, VS Code  

---

## 🧪 Application Flow

This platform is **not publicly accessible**. Staff credentials are provisioned by administrators. No self-registration is allowed — users log in with assigned credentials only.

---

## 🏥 Key Functional Pages (Backend-Enabled)

### 📊 Dashboard
- Welcome message with user name and today’s date
- Appointment summary: total, cancelled, missed
- Table of today’s appointments (time, patient, reason)
- Weekly appointment trends (bar chart)
- Quick links: cost estimation, create patient, start treatment

### 👤 Patients
- Search patients by name, ID, or DOB
- View contact details and basic info
- Create and update patient records

### 🦷 Treatments
- View treatment and billing history
- Start and update treatment status
- Estimate costs based on procedures (braces, fillings, etc.)

### 📦 Inventory & Orders
- Track supply levels, usage frequency, and categories
- Add new products, set reorder thresholds
- Place restocking orders

### 🧾 Insurance & Billing
- Record and validate insurance information
- Link insurance coverage to treatment cost breakdown
- Generate billing records for completed procedures

### 📅 Scheduling
- Staff can create and view appointments
- View by day or week
- Color-coded appointment status: upcoming, done, cancelled, ongoing

### 👥 Users & Admin
- Admins manage all clinic staff
- Staff include dentists, hygienists, nurses, and reception
- Role-based access control to features

---

## 💡 My Contributions

As part of the backend team, I:
- Implemented RESTful API endpoints for treatment and inventory modules
- Developed cost estimation logic based on procedure types
- Built CRUD operations for users, patients, and schedules
- Collaborated on MongoDB schema design and backend data models
- Participated in sprint planning, daily stand-ups, and mentor-led code reviews

---

> This project was a collaborative learning experience focused on building production-level systems under mentorship. It demonstrates end-to-end understanding of backend development in a secure, modular, healthcare-oriented environment.
