# 🕐 Flip Clock

A stylish, animated **Flip Clock** built with pure **HTML, CSS, and JavaScript** — no libraries, no frameworks. Displays real-time hours, minutes, and seconds with smooth flip card animations, just like the classic airport departure boards.

![Flip Clock Preview](preview.png)

---

## ✨ Features

- 🕒 **Real-time clock** — updates every second automatically
- 🎴 **Smooth flip animations** — classic card-flip effect for each digit
- 🌙 **Dark aesthetic UI** — minimal and elegant design
- 📱 **Responsive layout** — works on desktop and mobile
- ⚡ **Zero dependencies** — pure HTML, CSS & JavaScript only

---

## 🚀 Live Demo

🔗 [View Live](https://lokesh007-de.github.io/flip-clock) <!-- Update this link if deployed elsewhere -->

---

## 🛠️ Tech Stack

| Technology | Usage |
|------------|-------|
| HTML5 | Structure & layout |
| CSS3 | Flip animations, styling |
| JavaScript (Vanilla) | Real-time clock logic |

---

## 📁 Project Structure

```
flip-clock/
├── index.html       # Main HTML file
├── style.css        # All styles & animations
└── script.js        # Clock logic & flip trigger
```

---

## 🏃 How to Run Locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/lokesh007-de/flip-clock.git
   ```

2. **Navigate to the project folder**
   ```bash
   cd flip-clock
   ```

3. **Open in browser**
   ```bash
   # Simply open index.html in any browser
   open index.html
   ```

   Or use **Live Server** extension in VS Code for best experience.

---

## 🧠 How It Works

- JavaScript fetches the current time every second using `new Date()`
- Each digit is split into **top half** and **bottom half** cards
- On each second tick, the **flip animation** plays using CSS `@keyframes` with `rotateX` transform
- The "before" state shows the old digit, the "after" state reveals the new digit after the flip

---

## 📸 Screenshot

> *(Add a screenshot of your project here)*

---

## 👨‍💻 Author

**Lokesh Kumar**  
🎓 B.Tech IT — Institute of Technology & Management, Aligarh  
🐙 GitHub: [@lokesh007-de](https://github.com/lokesh007-de)  
📧 Email: lokeshkumark026@gmail.com

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

⭐ If you found this useful, please give it a **star** on GitHub!
