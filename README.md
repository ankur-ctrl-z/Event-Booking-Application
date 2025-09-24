````markdown
# 📅 Event Booking Application – Calendra

A comprehensive **event booking platform** where users can 📆 create, 🤝 share, and ✅ join appointments seamlessly. Built with a robust and scalable stack to ensure conflict-free scheduling and smooth user experience.

---

## 🚀 Tech Stack

| Layer              | Technology                          |
| ------------------ | ----------------------------------- |
| **Frontend**       | Next.js, Tailwind CSS               |
| **Backend**        | Next.js API Routes, Drizzle ORM     |
| **Database**       | PostgreSQL                          |
| **Authentication** | Clerk                               |
| **Deployment**     | Vercel                              |

---

## 🌟 Features

* 🔐 **Secure Authentication with Clerk (Login / Signup)**
* 📅 **Create, Manage, and Share Appointments**
* 🤝 **Invite Friends via Event Links**
* 🕒 **Real-time Availability Check** (no scheduling conflicts)
* 📈 **Track Upcoming and Past Events**
* 📱 **Responsive UI for Mobile and Desktop**

---

## 🛠️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/ankur-ctrl-z/Event-Booking-Application.git
cd Event-Booking-Application
````

### 2. Install Dependencies

```bash
npm install
```

### 3. Configure Environment Variables in **.env.local**

```dotenv
DATABASE_URL=<your-postgres-connection-string>
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=<your-clerk-publishable-key>
CLERK_SECRET_KEY=<your-clerk-secret-key>
```

### 4. Run Development Server

```bash
npm run dev
```

The app will be running at `http://localhost:3000/`

---

## ✅ API Overview

### Event Routes (`/api/events`)

| Method | Endpoint         | Description                   |
| ------ | ---------------- | ----------------------------- |
| POST   | `/create`        | Create a new event            |
| GET    | `/my-events`     | Fetch logged-in user’s events |
| GET    | `/join/:eventId` | Join an event if available    |
| GET    | `/all`           | Fetch all shared events       |

> All protected routes require **Clerk Authentication**.

---

## 🗂️ Project Structure

```
/Event-Booking-Application
├── /app        # Next.js app router pages & routes
├── /components # Reusable UI components
├── /lib        # Utilities & helper functions
├── /db         # Drizzle schema & migrations
└── /public     # Static assets
```

---

## 🌍 Deployment

* **Frontend + Backend:** Deploy on **Vercel**
* **Database:** Host PostgreSQL on **Neon**

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!
Feel free to check [issues](https://github.com/ankur-ctrl-z/Event-Booking-Application/issues) or submit a **PR**.

---


## 👨‍💻 Author

**Ankur Sharma**

* 🔗 [LinkedIn](https://www.linkedin.com/in/ankur-sharma-3a6037226/)
* 🔗 [X (Twitter)](https://x.com/__ankur01__)
```

