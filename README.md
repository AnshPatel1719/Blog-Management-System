# Inkhive – AI Powered Blog Platform

**Inkhive** is a modern full‑stack **AI‑powered blog management platform** where users can create high‑quality blog posts with AI assistance, admins review and approve content, and readers can interact through feedback. The platform focuses on clean UI, secure authentication, and scalable architecture.

---

🚀 Features

✍️ User Module

* User registration and secure login
* Profile management with image upload
* Create and edit blogs
* AI‑assisted blog generation using **Google Gemini**
* View published blogs
* Give feedback on blogs

🛡️ Admin Module

* Secure admin authentication
* Admin dashboard
* Approve or reject blog posts
* Manage users and blogs
* Content moderation

🌐 General Features

* Responsive design for all devices
* Clean and modern UI
* Secure authentication using JWT with HTTP‑only cookies
* Role‑based access (Admin / User)

---

🛠️ Tech Stack

Frontend

* React
* Vite
* Tailwind CSS
* ShadCN/UI

Backend

* Node.js
* Express.js
* MongoDB
* Mongoose

AI Integration

* Google Gemini API (AI blog generation)

 Authentication & Security

* JWT (JSON Web Token)
* Secure cookies

---

⚙️ Setup & Installation

1️⃣ Clone the Repository

```bash
git clone https://github.com/AnshPatel1719/Blog-Management-System.git
```

---

2️⃣ Backend Setup

```bash
cd server
npm install
```

Create a `.env` file:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
GEMINI_API_KEY=your_gemini_api_key
```

Run backend server:

```bash
npm start
```

---

3️⃣ Frontend Setup

```bash
cd client
npm install
npm run dev
```

---

 🔐 Authentication Flow

* JWT generated on login
* Token stored in **HTTP‑only secure cookies**
* Role‑based route protection for Admin and User

---

📌 Future Enhancements

* Comment replies & threading
* SEO optimization
* Blog analytics dashboard
* Social media sharing

---

👨‍💻 Author

**Ansh Patel**
M.Sc. IT – VNSGU

---

📄 License

This project is developed for **learning and portfolio purposes**. You are free to use and modify it.
