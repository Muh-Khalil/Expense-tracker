# 💰 Expense Tracker

A full-stack Expense Tracker web application that helps users manage their personal finances by tracking income and expenses. Includes filtering, PDF/Excel reports, and secure authentication.

---

## 📌 Features

- 🔐 User Authentication (Signup/Login)
- 🧾 Add, Edit, Delete Expenses and Incomes
- 📅 Filter by Month
- 📤 Export Expense Report as PDF or Excel
- 📊 Visual Income vs. Expense Summary
- 🧠 Password Reset via Email
- 🧱 Responsive UI with Tailwind CSS
- ☁️ Cloudinary Profile Picture Upload
- 🌐 Built with MERN Stack (MongoDB, Express, React, Node.js)
- ✅ JWT-based Authentication
- 🔒 Secured API endpoints

---

## 🛠️ Tech Stack

**Frontend:**
- React
- Tailwind CSS
- React Router
- Framer Motion
- React Hot Toast
- FileSaver.js / SheetJS / jsPDF (for PDF/Excel export)

**Backend:**
- Node.js
- Express.js
- MongoDB (Mongoose)
- JWT, Bcrypt.js
- Nodemailer
- Cloudinary

---

## 🚀 Getting Started

### 🔧 Prerequisites
- Node.js & npm
- MongoDB (Atlas or local)

### 🖥️ Clone the Repository
```bash
git clone https://github.com/Muh-Khalil/expense-tracker.git
cd expense-tracker
````

### 📦 Install Dependencies

**Frontend:**

```bash
cd fronted
npm install
```

**Backend:**

```bash
cd backend
npm install
```

### 🗂️ Environment Variables

Create a `.env` file in `/backend`:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLOUD_NAME=your_cloud_name
CLOUD_API_KEY=your_api_key
CLOUD_API_SECRET=your_api_secret
EMAIL_USER=your_email@example.com
EMAIL_PASS=your_email_password_or_app_key
CLIENT_URL=your client url
ABSTRACT_API_KEY=abstract_api_key_for_checking_email
```

---

### ▶️ Running the App

**Backend:**

```bash
cd backend
npm run dev
```

**Frontend:**

```bash
cd fronted
npm start
```

Then visit: `http://localhost:3000`

---

## 📁 Folder Structure

```
expense-tracker/
├── client/                 # Frontend (React)
│   └── src/
│       ├── components/
│       ├── layouts/
│       ├── pages/
│       └── ...
├── backend/                # Backend (Express)
│   ├── controllers/
│   ├── routes/
│   ├── models/
│   ├── middlewares/
│   └── ...
└── README.md
```

---

## 🧠 Future Enhancements

* Add category-wise reports
* Enable dark mode

---

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first.

---


## 📫 Contact

Made with ❤️ by **Muhammad Khalil**
Connect on [LinkedIn](https://www.linkedin.com/in/khalil-dev) or [GitHub](https://github.com/khalil-dev)



