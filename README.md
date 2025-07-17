# 🖼️ Imagify – AI-Powered Image Generator (MERN SaaS)

Imagify is a full-stack AI SaaS platform that lets users generate stunning images from text prompts using the **Clipdrop text-to-image API**. It features a **credit system**, **user authentication**, and **Stripe integration** for payments — built with the modern **MERN stack**.

---

## 📽️ Live Link

[Watch Live](https://imagify-teal-kappa.vercel.app/)

---

## 🚀 Key Features

- 🔐 JWT-based user authentication & protected routes
- 🧠 Text-to-image generation using Clipdrop API
- 💳 Stripe payment integration with webhook-based credit top-up
- 🔄 Credit system: 1 credit = 1 image generation
- 🕒 Prompt & image history tracking per user
- 📱 Responsive UI with Tailwind CSS
- 🌍 Hosted on Render (backend) & Vercel (frontend)

---

## 🛠️ Tech Stack

| Layer        | Technology                  |
|--------------|------------------------------|
| Frontend     | React.js, Tailwind CSS, Toastify |
| Backend      | Node.js, Express.js          |
| Database     | MongoDB Atlas                |
| Auth         | JWT, bcrypt                  |
| Payments     | Razorpay API                   |
| AI API       | Clipdrop API                 |
| Deployment   | Vercel (Frontend), Render (Backend) |

---

## 📂 Project Structure
imagify/
├── client/ # React frontend
│ └── components/
├── server/ # Node/Express backend
│ └── routes/, controllers/, middlewares/
├── .env # Environment variables
├── README.md
