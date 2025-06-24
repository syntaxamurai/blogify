# 📝 Blogify – Fullstack Blog Platform with AI-Powered Content Creation

**Blogify** is a fullstack blogging platform built with **Laravel** and **Tailwind CSS** that lets users **write, manage, and share blog posts** easily. It includes **user authentication**, **markdown support**, **commenting**, and a built-in integration with **Gemini AI** to help users generate blog content using prompts.

---

## 📸 Preview

![Blogify Screenshot](./screenshot.png)

---

## 🚀 Features

- ✅ User registration & login (Auth)
- 📝 Create, edit, delete blog posts (Markdown supported)
- 💬 Commenting system for each blog
- 📚 View all published blogs (public feed)
- 👨‍💻 Admin moderation dashboard
- ⚡️ **Gemini AI-powered blog generation**
- 🎨 Beautiful UI with Tailwind CSS
- 🔐 Secure access and route protection

---

## 🧠 AI Integration (Gemini)

Blogify uses **Gemini AI** to help users generate blog post drafts.

### ✨ How it works:
1. User enters a topic or prompt.
2. Gemini AI generates a structured blog draft.
3. User can edit, publish, or save it for later.

> Example: "Write a blog about how Laravel compares to Node.js for beginners" → Gemini outputs a formatted draft.

---

## 🛠️ Tech Stack

| Layer       | Tools & Frameworks                              |
|------------|--------------------------------------------------|
| Frontend    | Laravel Blade, Tailwind CSS                     |
| Backend     | Laravel (PHP)                                   |
| Database    | MySQL or PostgreSQL                             |
| AI Service  | Gemini AI (Google's Generative AI API)          |
| Auth        | Laravel Breeze / Laravel Jetstream              |
| Deployment  | Laravel Forge, Vercel (optional for AI UI)      |

---

## 📦 Installation

### 🔧 Prerequisites:
- PHP 8.x
- Composer
- MySQL or PostgreSQL
- Node.js & npm (for Tailwind)
- Gemini AI API Key (get one at [https://ai.google.dev](https://ai.google.dev))

### 🧪 Setup:

```bash
# 1. Clone the repo
git clone https://github.com/yourusername/blogify.git
cd blogify

# 2. Install PHP dependencies
composer install

# 3. Install Tailwind CSS and build assets
npm install && npm run dev

# 4. Configure .env
cp .env.example .env
php artisan key:generate

# 5. Setup database
php artisan migrate

# 6. Serve the app
php artisan serve

---

📌 License
MIT License. Feel free to fork and use for learning or your own blog platform.

💡 Inspiration
This project is meant to help developers build fullstack apps using Laravel and explore AI-assisted content creation using Gemini AI. It’s designed to be portfolio-ready and scalable.



