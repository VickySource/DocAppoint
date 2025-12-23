# 🩺 DocAppoint

**DocAppoint** is a full-stack **Smart Doctor Appointment Platform** built using the **MERN stack**.  
It enables patients to book doctor appointments, doctors to manage schedules, and an admin to monitor and control the entire system through a secure dashboard.

This project is designed with real-world healthcare workflows, clean architecture, and scalable cloud deployment in mind.

---

## 🌐 Live Applications

### 👤 Patient Frontend
- https://doc-appoint-pearl.vercel.app/
- https://doc-appoint-1j4y.vercel.app/

> Multiple deployments are used for testing and production validation.

---

## 👨‍💼 Admin
The **admin role is managed by the project owner**.

📩 **Admin Contact**
- **Name:** Vicky  
- **GitHub:** https://github.com/VickySource  
- **LinkedIn:** https://www.linkedin.com/in/vikas-ar/

(Admin credentials are intentionally not shared publicly.)

---

## 👥 Team Members

This project was developed collaboratively by:

- **Vicky**  
  LinkedIn: https://www.linkedin.com/in/vikas-ar/

- **Sampreeth C H**  
  LinkedIn: https://www.linkedin.com/in/sampreethch/

- **Saroj Kumar Sah**  
  LinkedIn: https://www.linkedin.com/in/saroj-kumar-sah-9056a1299/

- **Sanjan R**  
  LinkedIn: https://www.linkedin.com/in/sanjan-r/

---

## 🚀 Features

### 👤 Patient
- User authentication (Signup / Login)
- Browse doctors by specialization
- Book and manage appointments
- Online payments using Razorpay
- View appointment history

### 👨‍⚕️ Doctor
- Doctor authentication
- View scheduled appointments
- Update appointment status
- Manage availability

### 🛠️ Admin
- Secure admin authentication
- Add and manage doctors
- View users and appointments
- Platform-wide monitoring

---

## 🧱 Tech Stack

### Frontend & Admin
- React (Vite)
- React Router
- Context API
- Axios
- Tailwind CSS

### Backend
- Node.js
- Express.js
- MongoDB Atlas
- Mongoose
- JWT Authentication

### Third-Party Services
- Cloudinary – Image storage
- Razorpay – Online payments
- Gemini AI – AI features
- Vercel – Frontend & Admin deployment
- Render – Backend deployment

---

## 🗂️ Project Structure

DocAppoint/
│
├── frontend/ # Patient application
├── admin/ # Admin dashboard
├── backend/ # Express server & APIs
└── README.md

---

## ⚙️ Environment Variables

### Backend (`backend/.env`)
```env
MONGODB_URI=
JWT_SECRET=

CLOUDINARY_NAME=
CLOUDINARY_API_KEY=
CLOUDINARY_SECRET_KEY=

ADMIN_EMAIL=
ADMIN_PASSWORD=

GEMINI_API_KEY=

RAZORPAY_KEY_ID=
RAZORPAY_KEY_SECRET=

PORT=4000
NODE_ENV=production
VITE_BACKEND_URL=
VITE_RAZORPAY_KEY_ID=

Frontend (frontend/.env)
VITE_BACKEND_URL=
VITE_RAZORPAY_KEY_ID=

Admin (admin/.env)
VITE_BACKEND_URL=


📄 License
This project is for educational and demonstration purposes.  

Built with ❤️ by Team Vikas A R, Sampreeth C H, Saroj Kumar Sah & Sanjan R
