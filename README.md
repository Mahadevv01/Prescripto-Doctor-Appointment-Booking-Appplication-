# 🩺 Prescripto - Doctor Appointment Web App

**Prescripto** is a full-stack web application designed to make healthcare more accessible by simplifying the process of booking doctor appointments. It features three levels of authentication—**Patient**, **Doctor**, and **Admin**—with customized dashboards and functionalities for each. Integrated with online payment gateways (Stripe and Razorpay), the app ensures secure and seamless transactions.

Built with the **MERN** stack (MongoDB, Express.js, React.js, Node.js), Prescripto delivers an efficient and user-friendly experience for both patients and healthcare providers.

---

## 🛠️ Tech Stack

- **Frontend:** React.js  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB  
- **Authentication:** JSON Web Token (JWT)  
- **Payment Gateways:** Stripe, Razorpay  

---

## 🔑 Key Features

### 1. Three-Level Authentication

#### 👤 Patient Login
- Sign up, log in, and book appointments with doctors.
- Manage appointments (view, cancel, reschedule).
- Pay online using Stripe, Razorpay, or cash.
- Maintain personal profile (edit name, email, address, gender, birthday, and upload profile picture).

![Patient Login](https://github.com/user-attachments/assets/e749e270-1f38-4a2c-acee-13f163a6cf0c)

#### 🩺 Doctor Login
- Manage appointments and view appointment details.
- Dashboard includes earnings, total appointments, and recent bookings.
- Update profile including description, fees, address, availability.

![Doctor Login](https://github.com/user-attachments/assets/0a5e8616-68a4-43da-b83e-c1dadc5bb8ee)

#### 🛠️ Admin Login
- Create, view, edit, or delete doctor profiles.
- Dashboard shows analytics for appointments, doctors, and patients.
- Manage all appointments (cancel or mark as completed).

![Admin Login](https://github.com/user-attachments/assets/7799f71f-3f98-4985-b43d-cedda0b45d4c)

---

## 🏠 Home Page

- User-friendly UI with search and filter options.
- View top doctors and explore sections: About Us, Delivery Info, Privacy Policy, Contact.
- Footer with navigation links.

![Home Page](https://github.com/user-attachments/assets/3b8f572b-3630-41ae-ab19-399c24e899c1)

---

## 🩺 All Doctors Page

- Browse all registered doctors.
- Filter doctors based on specialties.
- Click on a profile to book appointments.

---

## 📄 About Page

- Learn about Prescripto’s vision and mission.
- **Why Choose Us** section:
  - **Efficiency**: Streamlined appointment process.
  - **Convenience**: Online booking and payments.
  - **Personalization**: Tailored experience.

---

## 📞 Contact Page

- Office address and contact details.
- Job opportunity section.

---

## 📅 Doctor Appointment Page

- View detailed doctor profiles: qualification, experience, availability.
- Appointment form with date, time, and payment options (Cash, Stripe, Razorpay).
- Related doctors section.

![Doctor Appointment Page](https://github.com/user-attachments/assets/06416217-801c-44ce-b9ba-cf5c7f2c2c8c)

---

## 👤 User Profile

- Edit profile info and upload profile pictures.
- View past and upcoming appointments.
- Logout option available.

---

## 🗄️ Admin Panel

- Dashboard: Stats on doctors, appointments, patients.
- Add Doctor: Form for profile creation (image, specialty, email, experience, etc.).
- View and manage all appointments.

![Admin Panel](https://github.com/user-attachments/assets/d2974693-b45a-41a7-9cc4-4f923e3ce0f8)

---

## 🩺 Doctor Dashboard

- **Earnings Overview**
- **Appointments List** with patient info, appointment time, status, and payment mode.
- **Profile Management**

![Doctor Dashboard](https://github.com/user-attachments/assets/21a6655b-032d-4fe7-8f39-daf7a6756bdd)

---

## 💳 Payment Integration

- Multiple options: Stripe, Razorpay, and Cash.
- Safe, secure, and seamless.

---

## 🌐 Project Setup

### Clone the Repository:
```bash
git clone https://github.com/your-username/prescripto.git
cd prescripto
