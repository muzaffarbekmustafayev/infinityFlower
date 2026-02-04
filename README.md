

# 🌸 Infinity Flower Animation

An abstract **flower animation** created using HTML5 Canvas and Vanilla JavaScript.  
The animation is driven by mathematical sine functions and Bézier curves, producing a smooth, symmetric, and infinite floral motion.

This project explores the beauty of mathematics through visual art.

---

## ✨ Overview

The animation renders a continuously evolving flower-like shape with multiple petals.  
It runs directly in the browser and reacts to user interaction.

- Smooth real-time animation
- Infinite loop with graceful motion
- Click to reset and redraw

---

## 🧠 Concept

The core idea of this project is based on:

- Trigonometric functions (`sin`, `cos`)
- Quadratic Bézier curves
- Rotational symmetry
- Alpha blending and light composition
- Frame-based animation using `requestAnimationFrame`

The result is a **dynamic, glowing, multi-petal flower** that feels organic and alive.

---

## 🛠 Technologies Used

- **HTML5**
- **CSS3**
- **Vanilla JavaScript**
- **Canvas 2D API**

No external frameworks or libraries are required.

---

## 📁 Project Structure

```

infinityFlower/
│
├── index.html      # Main HTML file
├── style.css       # Canvas and page styling
├── script.js       # Animation logic
└── README.md       # Project documentation

````

---

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/muzaffarbekmustafayev/infinityFlower.git
````

2. Open the project folder
3. Open `index.html` in any modern web browser

No server or build process is needed.

---

## 🖱 Interaction

* The animation **starts automatically** when the page loads
* **Click on the canvas** to clear and restart the animation
* The animation **stops automatically after 30 seconds**

---

## ⚙️ Customization

You can easily modify the visual behavior by adjusting these variables in `script.js`:

```js
var petals = 7;   // Number of petals
var Rx = 150;     // Horizontal radius
var Ry = 150;     // Vertical radius
var kx = 3;       // X-axis sine frequency
var ky = 4;       // Y-axis sine frequency
```

Changing these values will generate completely different flower patterns.

---

## 🎨 Visual Effects

* Semi-transparent strokes
* Neon-like glow using `lighter` blend mode
* Rotational symmetry
* Dark background for high contrast

---

## 📜 License

This project is open for **learning, experimentation, and creative exploration**.
You are free to use and modify it for personal or educational purposes.

---

## 👤 Author

**Muzaffarbek Mustafayev**
Software Engineer

If you like this project, consider giving it a ⭐ on GitHub.
