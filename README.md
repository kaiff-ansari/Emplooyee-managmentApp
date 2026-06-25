# 🚀 Employee Management System

A full-stack Employee Management System that simplifies HR operations by providing secure employee management, leave management, role-based access control, and automated email notifications.

## 🌐 Live Demo

**Live Project:** https://emplooyee-managment-app-lj1f.vercel.app/login

---

## ✨ Features

* Secure JWT Authentication
* Role-Based Access Control (Admin & Employee)
* Employee Management (Add, Update, Delete)
* Leave Request & Approval System
* Automated Email Notifications
* Event-Driven Background Processing
* Responsive User Interface
* Production Deployment

---

## 🛠 Tech Stack

**Frontend**

* React.js
* Tailwind CSS
* Axios

**Backend**

* Node.js
* Express.js
* JWT Authentication

**Database**

* MongoDB

**Services**

* Inngest
* Brevo SMTP

---

## 🔑 Demo Credentials

Use the following admin account to explore the application.

**Email**

```text id="5sn5mp"
ftd10622144@dseu.ac.in
```

**Password**

```text id="9kqv2u"
admin123
```

### How to Test

1. Login using the admin credentials.
2. Add a new employee.
3. Update or delete employee details.
4. Create and manage leave requests.
5. Approve or reject employee leave requests.
6. Verify automated email notifications.

---

## 📂 Project Structure

```text id="jjn96x"
Employee-Management-System
├── client/
├── server/
└── README.md
```

---

## ⚙️ Environment Variables

Create a `.env` file inside the **server** directory.

```env id="vkn7ek"
JWT_SECRET=

ADMIN_EMAIL=

MONGODB_URI=

INNGEST_EVENT_KEY=
INNGEST_SIGNING_KEY=

SMTP_USER=
SMTP_PASS=
SENDER_EMAIL=
```

---

## 🚀 Installation

```bash id="3uzjhk"
git clone https://github.com/your-username/employee-management-system.git

cd employee-management-system

# Install frontend dependencies
cd client
npm install

# Install backend dependencies
cd ../server
npm install
```

---

## ▶️ Run the Application

### Start Backend

```bash id="i7n6sj"
npm run server
```

### Start Frontend

```bash id="2uwgvh"
npm run dev
```

---

## 🚀 Future Improvements

* Attendance Management
* Payroll Management
* Department Management
* Employee Profile Uploads
* Analytics Dashboard
* Multi-Level User Roles

---

## 👨‍💻 Author

**Mohd Kaif**

If you found this project helpful, consider giving it a ⭐ on GitHub.
