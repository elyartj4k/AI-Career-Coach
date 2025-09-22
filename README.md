# **Full Stack AI Career Coach** 🤖🚀

> A powerful AI-driven career coaching platform built with **Next.js**, **Neon DB**, **Tailwind CSS**, **Prisma**, **Inngest**, and **Shadcn UI**.
> This app helps users with career guidance, resume tips, and personalized advice, all powered by modern full-stack technologies.

---

## **📌 Features**

* 🔐 **Authentication** powered by **Clerk**
* 🎨 **Beautiful UI** built with **Tailwind CSS** and **Shadcn UI**
* ⚡ **Serverless Workflows** with **Inngest**
* 🗄️ **PostgreSQL Database** hosted on **Neon** and managed via **Prisma**
* 🤖 **AI Career Coaching** using **Gemini API**
* 🧩 Modular and scalable **Next.js 14 App Router architecture**

---

## **📂 Project Structure**

```
AI-Career-Coach/
│
├── app/                  # Next.js application routes & pages
│
├── prisma/               # Prisma schema and migrations
│
├── components/           # Reusable UI components
│
├── styles/               # Tailwind CSS styles
│
└── public/               # Static assets
```

---

## **⚙️ Environment Setup**

Before running the project, create a `.env` file in the root of your project and add the following variables:

```env
# Database
DATABASE_URL=

# Clerk Authentication
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

# Clerk Routes
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding

# Gemini AI API Key
GEMINI_API_KEY=
```

---

## **🚀 Getting Started**

### **1. Clone the Repository**

```bash
git clone https://github.com/<your-username>/AI-Career-Coach.git
cd AI-Career-Coach
```

---

### **2. Install Dependencies**

Make sure you have **Node.js (v18 or higher)** installed.

```bash
npm install
```

---

### **3. Set Up the Database**

Generate the Prisma client and run database migrations:

```bash
npx prisma generate
npx prisma migrate dev
```

---

### **4. Run the Development Server**

```bash
npm run dev
```

Your app will be live at:
[http://localhost:3000](http://localhost:3000)

---

## **🛠️ Tech Stack**

| **Category**       | **Technology**                      |
| ------------------ | ----------------------------------- |
| **Frontend**       | Next.js 14, Tailwind CSS, Shadcn UI |
| **Backend**        | Next.js API Routes                  |
| **Database**       | Neon (PostgreSQL) + Prisma          |
| **Authentication** | Clerk                               |
| **AI Integration** | Gemini API                          |
| **Workflows**      | Inngest                             |

---

## **🤝 Contribution**

Contributions are welcome!
If you'd like to contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature-name`)
3. Commit your changes (`git commit -m "Added feature X"`)
4. Push to the branch (`git push origin feature-name`)
5. Open a Pull Request

---

## **📜 License**

This project is licensed under the **MIT License**.
You are free to use, modify, and distribute it.

---

## **🌟 Future Improvements**

* Add **career path recommendation engine**
* Real-time chat with **AI career assistant**
* Analytics dashboard for users and admins
* Mobile-first optimizations

---

This README provides:

* Clean instructions for **setup** and **deployment**
* Proper **.env variable guide**
* Clear **tech stack table**
* Contribution guidelines for collaborators
