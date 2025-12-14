# ⚛️ The Atomic Blog

The Atomic Blog is a simple React application built to demonstrate core React concepts in a practical way.  
It uses fake data, basic UI interactions, and state management to simulate a small blog system.

---

## 🚀 Features

- Generate fake posts using `@faker-js/faker`
- Add new posts manually
- Search through posts (title + body)
- Clear all posts
- Toggle a fake dark mode 🌙 / ☀️
- Large post archive (performance demo)
- Derived state for filtered results

---

## 🧠 Concepts Covered

This project showcases several important React concepts:

- `useState` for state management
- `useEffect` for side effects (dark mode toggle)
- Derived state (filtered posts based on search)
- Controlled components (inputs & textarea)
- Lifting state up and passing props
- Performance optimization using lazy state initialization

---

## 🛠️ Tech Stack

- React
- @faker-js/faker
- JavaScript (ES6+)

---

## 📦 Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/shefo72/The-Atomic-Blog.git
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm start
   ```

## 🧪 How It Works

- On first render, the app generates **30 random posts**.
- You can:
  - Add a new post using the form
  - Search posts using the search input
  - Clear all posts with one click
- The archive contains **10,000 posts** generated once for performance demonstration.
- Clicking **“Add as new post”** copies an archive post to the main list.
- Dark mode is simulated by toggling a CSS class on the `<html>` element.

---

## ⚠️ Notes

- The archive is intentionally large and may slow down rendering.
- Post keys use array index for simplicity (not recommended for production).

---

## 📄 License

This project is for learning and practice purposes only.
