# Hospital Management System

## This is a Fullstack Hospital Management System project built using the MERN stack, with three distinct user roles: User, Doctor, and Admin.

1. **User Features**:
   Users can register or log in to explore the list of available doctors by their specializations. They can easily book appointments, make payments online through Razorpay, and view all upcoming and past appointments. Users can also update their personal information in the "My Profile" section.

2. **Doctor Features**:
   Doctors can log in to view and manage their appointments and update their profiles. Through their personalized dashboard, they can track total earnings, the number of appointments, and patient interactions. Doctors have the option to complete or cancel appointments directly from their dashboard, enabling efficient appointment management.

3. **Admin Features**:
   The admin can log in to oversee all aspects of the system. They have access to an Admin Dashboard that displays the total number of doctors, patients, and booked appointments. Additionally, the admin can view recent appointments and manage doctor profiles and their schedules, streamlining the system's functionality.

_This project demonstrates a comprehensive hospital management solution, supporting an intuitive user experience, robust role-specific features, and secure online payments, providing seamless interaction for patients, doctors, and administrators._

**Live Preview** : https://hms-frontend-kappa.vercel.app/
<br/>
<br/>
**Admin/Doctor Portal** : https://hms-admin-nine.vercel.app/

## Here are some references images

## User Sction

### User Registration & Login

<img src="frontend/src/readme_images/userSignup.png" alt="User Registration" style="padding:0 10px;"/>

<img src="frontend/src/readme_images/userLogin.png" alt="User Login" style="padding:0 10px;"/>

### Home Screen

<img src="frontend/src/readme_images/home1.png" alt="Home" style="padding:0 10px;"/>

<img src="frontend/src/readme_images/home-findbySpeciality.png" alt="Home" style="padding:0 10px;"/>

<img src="frontend/src/readme_images/footer.png" alt="Footer" style="padding:0 10px;"/>

### All Doctors Page

<img src="frontend/src/readme_images/allDoctors.png" alt="All Doctors" style="padding:0 10px;"/>

### About Us

<img src="frontend/src/readme_images/about.png" alt="About Us" style="padding:0 10px;"/>

### Contact Information

<img src="frontend/src/readme_images/contactUs.png" alt="Contact Information" style="padding:0 10px;"/>

## Admin Section

### Admin Login

<img src="frontend/src/readme_images/adminLogin.png" alt="Admin Login" style="padding:0 10px;"/>

### Admin Dashboard

<img src="frontend/src/readme_images/adminDashboard.png" alt="Admin Dashboard" style="padding:0 10px;"/>

### All Appointments

<img src="frontend/src/readme_images/adminAppointments.png" alt="All Appointments" style="padding:0 10px;"/>

### Add Doctor Form

<img src="frontend/src/readme_images/adminAddDoctor.png" alt="Add Doctor" style="padding:0 10px;"/>

### All Doctor

<img src="frontend/src/readme_images/adminAllDoctor.png" alt="All Doctors" style="padding:0 10px;"/>

## Doctor Section

### Doctor Login

<img src="frontend/src/readme_images/doctorLogin.png" alt="Doctor Login" style="padding:0 10px;"/>

### Doctor Dashboard

<img src="frontend/src/readme_images/doctorDashboard.png" alt="Doctor Dashboard" style="padding:0 10px;"/>

### Doctor Appointments

<img src="frontend/src/readme_images/doctorAppointmnets.png" alt="Doctor Appointments" style="padding:0 10px;"/>

### Doctor Profile

<img src="frontend/src/readme_images/doctorProfile.png" alt="Doctor Profile" style="padding:0 10px;"/>

### Thank You for Visiting 🎊 🎉 🙏
# Doctor Management System

A modern web application for managing doctors, patients, and appointments. Built with React (Vite), Node.js, Express, and MongoDB.

## Live Demo

[Live Link (sahil)](https://hms-frontend.vercel.app)

## Features
- Admin and Doctor dashboards
- Patient management
- Appointment scheduling
- Authentication and authorization
- Responsive UI with Tailwind CSS
- Cloudinary integration for image uploads

## Tech Stack
- **Frontend:** React, Vite, Tailwind CSS
- **Backend:** Node.js, Express, MongoDB
- **Image Uploads:** Cloudinary
- **Deployment:** Vercel

## Getting Started

### Prerequisites
- Node.js
- npm
- MongoDB Atlas account

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/sahil-saroj/hms.git
   ```
2. Install dependencies for frontend, admin, and backend:
   ```sh
   cd doctor-management/frontend
   npm install
   cd ../admin
   npm install
   cd ../backend
   npm install
   ```
3. Set up environment variables for backend (see `backend/config/mongodb.js`).
4. Start the backend server:
   ```sh
   npm start
   ```
5. Start the frontend and admin apps:
   ```sh
   cd ../frontend
   npm run dev
   cd ../admin
   npm run dev
   ```

## Folder Structure
```
doctor-management/
  admin/
  backend/
  frontend/
```

## Author
**Sahil Saroj**

---

For any queries, contact [Sahil Saroj](mailto:sahil.saroj@example.com).
