# ONEPASS (Version 1 – LocalStorage)

A simple and lightweight password manager built using **React** and **Tailwind CSS**, storing all data locally using **browser localStorage**.

---

## 🚀 Features

* Add / Edit / Delete password entries
* Show / Hide password
* Copy username or password
* Fully offline — stored in **localStorage**
* Clean and responsive UI with Tailwind CSS

---

## 📁 Project Structure

```
PROJECT_ONEPASS/
│
├─ src/
│   ├─ assets/          # icons & images
│   ├─ components/      # Navbar, Manager, Footer
│   ├─ App.jsx
│   ├─ main.jsx
│   ├─ index.css
│
├─ public/
├─ README.md
└─ vite.config.js
```

---

## ⚙️ How It Works

1. When you add a password, it's saved inside `localStorage` as a JSON array.
2. Manager.jsx loads saved data on page load.
3. Edit/Delete updates the localStorage entry.
4. No backend required — 100% client-side.

**LocalStorage Key Used:**

```
onepass_entries
```

---

## ▶️ Run Locally

```
npm install
npm run dev
```

Open the app in your browser at the shown localhost URL.

---

## 🔐 Security Note

LocalStorage is not encrypted. Anyone with device access can view stored credentials.
Use Version 2 (MongoDB) for better security.

---

## 👨‍💻 Author

**Ripusudan Mishra**

---

Simple. Local. Fast. ONEPASS V1.
