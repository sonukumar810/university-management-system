# University Management System

📘 About

The **University Database Management System** is a comprehensive platform designed to efficiently manage and organize university-related data. It handles complete records of **students** and **faculty**, ensuring smooth academic and administrative operations.

This system includes features such as:

- **Attendance tracking** for students and faculty  
- **Result and marks management**  
- **Secure login system** with role-based access  
- **Streamlined administrative workflows** for managing academic records  

Additionally, the project includes optimized database operations:

- Improved data retrieval using **indexing** and **MongoDB aggregation**
- Faster query performance and better scalability
---

## 🚀 Features
- Student management  
- Faculty management  
- Course and department management  
- Attendance tracking  
- Results / marks management  
- Admin panel  
- Authentication & role-based access  

---

## 📂 Project Structure
university-mgmt-sys/
│
├── backend/ # Node.js / Express backend API
└── frontend/ # React-based frontend
---

## 🛠️ Tech Stack

### **Frontend**
- React  
- JavaScript  
- CSS / Tailwind 

### **Backend**
- Node.js  
- Express.js  
- MongoDB 
- JWT Authentication  

---

## 📦 Installation & Setup

### 1️⃣ Clone the Repository

git clone https://github.com/sakshiSakshi77/university-mgmt-sys.git
cd university-mgmt-sys
Backend Setup
cd backend
npm install
npm start

Example .env
PORT=5000
MONGO_URL=your_mongodb_connection_string
JWT_SECRET=your_secret_key

Frontend Setup
cd frontend
npm install
npm start
This will start the frontend at:

http://localhost:3000📘 How It Works

Admin logs in and manages students/faculty.

CRUD operations for all major modules (students, faculty, departments, attendance).

Frontend communicates with backend through REST API endpoints.
