# 🌟 Quoteify – Inspire Every Click

> A motivational web app that inspires users with quotes and allows them to create, save, and view their favorite ones — all in a beautiful glassmorphic UI.

---

## 🧠 Overview

**Quoteify** is a fully interactive web application built using **HTML**, **Tailwind CSS**, and **JavaScript**.  
It generates inspirational quotes, allows users to save their favorites, and even lets them create their own custom quotes.

With a simple **login and signup system**, each user gets a personalized experience where their data (quotes and saved items) is securely stored in the browser using **LocalStorage**.

---

## ✨ Features

✅ **User Authentication** – Sign up, log in, and manage sessions securely in the browser.  
✅ **Personalized Greeting** – Displays “👋 Welcome, [username]” once logged in.  
✅ **Random Quote Generator** – Inspires users with random motivational quotes.  
✅ **Save Favorites** – Save and manage your favorite quotes locally.  
✅ **Create Custom Quotes** – Add your own quotes to the app.  
✅ **Delete Saved Quotes** – Manage your collection easily.  
✅ **Logout Functionality** – End your session anytime safely.  
✅ **Responsive Glassmorphism UI** – Elegant design using Tailwind CSS.  

---

## 🧩 Project Structure

```
Quoteify/
│
├── signup.html      # Registration page
├── login.html       # User login page
└── quoteify.html    # Main application page (protected)
```

---

## ⚙️ Tech Stack

| Technology | Purpose |
|-------------|----------|
| **HTML5** | Structure of the web app |
| **Tailwind CSS** | Modern responsive styling |
| **JavaScript (Vanilla)** | App logic and interactivity |
| **Google Fonts (Inter)** | Clean typography |
| **LocalStorage** | Data persistence for users and quotes |

---

## 💾 Data Storage (LocalStorage Keys)

| Key | Description |
|------|-------------|
| `quoteify_users` | Stores all registered user accounts |
| `quoteify_logged_in` | Keeps track of the active logged-in user |
| `quoteify_user_quotes` | Stores all custom quotes created by user |
| `quoteify_saved_quotes` | Stores saved quotes list |

---

## 🔐 Authentication Flow

1. User signs up → credentials stored in LocalStorage.  
2. User logs in → session created using `quoteify_logged_in`.  
3. Quoteify main app checks authentication before loading.  
4. Logout clears the session and redirects to the login page.

---

## 🧠 How It Works

1. Click **Inspire Me** to get a random motivational quote.  
2. Use **Save** to add it to your favorites.  
3. Click **View Saved Quotes** to see all your saved quotes.  
4. Use **Create Custom Quote** to write your own.  
5. Logout when done — your data stays safe locally.  

---

## 🎨 Design Highlights

- **Glassmorphism** effects for cards and modals.  
- **Gradient background** with subtle blur and shadows.  
- **Hover transitions** for all buttons.  
- **Smooth opacity animations** for quotes.  
- **Fully responsive layout** using Tailwind CSS.

---

## 🚀 Future Enhancements

- 🔐 Connect to **Firebase Authentication** for online accounts.  
- ☁️ Move data storage to **Firestore or MongoDB**.  
- 📱 Convert to **Progressive Web App (PWA)** for offline access.  
- 🧠 Add **AI-powered quote suggestions**.  
- 🎨 Add **Dark / Light mode toggle**.  
- 💬 Add **Social sharing** for quotes.

---

## 🧰 How to Run Locally

1. Clone or download the repository.  
2. Open `signup.html` or `login.html` in your browser.  
3. Create an account and log in.  
4. Enjoy the app offline — everything works locally!
5. Link (https://kishore-2008.github.io/Quoteify/login.html)

---

## 👥 Team Members

| Name | GitHub |
|------|---------|
| **Kishore K V** | [@KiShOrE-2008](https://github.com/KiShOrE-2008) |
| **Sowmiya R** | [@SoWmIyA-R-2007](https://github.com/SoWmIyA-R-2007) |
| **Sharvesh B** | [@sharvesh001](https://github.com/sharvesh001) |
| **Nivedha S** | [@Nivedha1206](https://github.com/Nivedha1206) |

---

## 🏫 Institution

**Chennai Institute of Technology**  
🎓 B.Tech – Information Technology  

---

## 🏁 Conclusion

**Quoteify** is a compact yet powerful example of how to combine **design, logic, and interactivity** to build a complete motivational web app using only frontend technologies.

> “The best way to predict the future is to create it.” – *Peter Drucker*
