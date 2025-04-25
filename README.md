# Prescripto - Doctor Appointment Booking Web App

Prescripto is a full-stack web application designed to make healthcare more accessible by simplifying the process of booking doctor appointments. It offers **three levels of login**: Patient, Doctor, and Admin, each with distinct features tailored to their roles. The app integrates online payment gateways (Stripe and Razorpay) to facilitate seamless and secure payments.

Built using the **MERN stack** (MongoDB, Express.js, React.js, and Node.js), Prescripto provides an efficient, user-friendly experience for both patients and healthcare providers.

---

## 🛠️ Tech Stack

- **Frontend:** React.js  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB  
- **Authentication:** JSON Web Token (JWT)  
- **Payment Gateways:** Stripe, Razorpay  

---

## 🔑 Key Features

### 🧑‍⚕️ Patient Login:
- Sign up and log in.
- Book, view, cancel, or reschedule appointments.
- Secure online payments via Cash, Stripe, or Razorpay.
- Edit user profile (name, email, address, gender, birthday, profile picture).

### 👨‍⚕️ Doctor Login:
- Login to view and manage appointments.
- Dashboard: earnings, number of patients, appointment history.
- Edit profile (description, fees, address, availability).
- View appointment details (patient info, payment mode, status).

### 👩‍💼 Admin Login:
- Create and manage doctor profiles.
- Dashboard: total doctors, appointments, patients, recent bookings.
- Add new doctors with full profile details.
- Manage all appointments (cancel or mark as completed).

---

## 🏠 Home Page
- User-friendly layout.
- Search doctors by specialties.
- View top doctors and their profiles.
- Access sections: About Us, Delivery Info, Privacy Policy, Contact Us.
- Footer with navigation links.

---

## 🩺 All Doctors Page
- List of all available doctors.
- Filter by specialty.
- Redirect to Doctor Appointment Page on profile click.

---

## 📄 About Page
- Info about Prescripto’s vision and mission.
- **Why Choose Us** section:
  - **Efficiency**: Streamlined process.
  - **Convenience**: Online booking and payment.
  - **Personalization**: Tailored experience.

---

## 📞 Contact Page
- Office address and contact details.
- Job opportunity section.
- Footer with additional navigation.

---

## 📅 Doctor Appointment Page
- Doctor details: profile, qualification, experience, description.
- Appointment form: choose date, time, and payment method.
- Online payment options: Cash, Stripe, Razorpay.
- Related doctors section.
- Login required for booking.

---

## 👤 User Profile
- Accessible after login.
- View and edit profile.
- Upload profile picture.
- View upcoming and past appointments.
- Logout option.

---

## 🗄️ Admin Panel

### Dashboard:
- Statistics: number of doctors, appointments, patients, latest bookings.
- Cancel bookings if required.

### Add Doctor:
- Add full profile: image, specialty, email, password, degree, address, experience, fees, description.

### Doctor List:
- View/edit/delete doctor profiles.

### Appointments:
- View all appointments with patient and doctor info.
- Admin actions: cancel or mark as completed.

---

## 🩺 Doctor Dashboard
- **Earnings Overview:** View total earnings from completed appointments.
- **Appointments List:** Detailed list with patient info, date, time, payment mode, status.
- **Actions:** Complete/cancel appointment.
- **Profile Management:** Update description, fees, address, availability.

---

## 💳 Payment Integration
- Multiple payment methods supported:
  - Cash
  - Stripe
  - Razorpay
- Ensures a secure and smooth user experience.
