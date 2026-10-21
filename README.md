# 🎂 Animated Birthday Cake & Celebration

<div align="center">

  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=14,23,45&height=200&section=header&text=Animated%20Birthday%20Cake&fontSize=42&fontAlignY=38&desc=An%20interactive%20SVG%20animated%20birthday%20cake%20experience%20with%20magical%20effects&descAlignY=58&descAlign=50" alt="Header Banner" width="100%" />

  <p align="center">
    <strong>A stunning, interactive birthday greeting web application with SVG morphing animations, realistic flickering candles, poppable balloons, interactive confetti, and a magical particle cursor trail.</strong>
  </p>

  <p align="center">
    <a href="https://github.com/saklincodes/Animated-Birthday-Cake/stargazers"><img src="https://img.shields.io/github/stars/saklincodes/Animated-Birthday-Cake?style=for-the-badge&color=gold" alt="Stars"></a>
    <a href="https://github.com/saklincodes/Animated-Birthday-Cake/network/members"><img src="https://img.shields.io/github/forks/saklincodes/Animated-Birthday-Cake?style=for-the-badge&color=blue" alt="Forks"></a>
    <a href="https://github.com/saklincodes/Animated-Birthday-Cake/blob/main/LICENSE"><img src="https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge" alt="License"></a>
    <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
    <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
    <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  </p>

</div>

---

## 🌟 Overview

**Animated Birthday Cake** is a front-end celebration web page designed to deliver a delightful, warm, and interactive birthday surprise. It brings together fluid SVG path morphing, CSS keyframe animations, Canvas-based physics particles, and interactive confetti explosions triggered by user actions.

---

## ✨ Features

- 🎂 **Sequential SVG Cake Morphing**: Intricate SVG paths smoothly drop down and assemble each cake tier, frosting layer, and cream filling into place.
- 🕯️ **Interactive Candle & Flame**:
  - Drops into position right after the cake finishes assembling.
  - Features a multi-layered flickering flame glow animation.
  - **Click to Blow Out**: Clicking the candle extinguishes the flame and triggers an opulent 3-second golden/silver celebration confetti shower.
- 🎈 **Interactive Floating Balloons**:
  - Smooth floating animations with custom strings and realistic 3D inner shadows.
  - **Pop Mechanics**: Clicking any floating balloon pops it with localized color-matched confetti bursts.
- ✨ **Magic Particle Cursor Trail**:
  - Custom HTML5 Canvas engine generates dynamic sparkling stardust particles that follow mouse movement across the screen.
- 🎨 **Elegant Dark Mode Aesthetic**:
  - Deep atmospheric background (`#252432`) tailored for high contrast with warm golden, pastel, and cream tones.
  - Responsive design with smooth animations across modern desktop and mobile browsers.

---

## 🎮 Interactive Controls

| Interaction | Action | Effect |
| :--- | :--- | :--- |
| 🖱️ **Move Mouse** | Anywhere on screen | Leaves a glowing stardust particle trail |
| 🕯️ **Click Candle** | Center top of the cake | Blows out candle flame + triggers twin-cannon confetti explosion |
| 🎈 **Click Balloon** | Any floating balloon | Pops balloon with customized color confetti particles |

---

## 📸 Demo Preview

```
               🔥   (Flickering Flame)
               ||   (Candle with striped detail)
            .------.
          (  Cream   )
        .--------------.
       |  Top Sponge    |
       |~~~~~~~~~~~~~~~~| (Chocolate Cream)
       |  Base Sponge   |
      ==================== (Serving Platter)
       
       🎈   🎈   🎈   🎈   🎈 (Interactive Floating Balloons)
```

---

## 📁 Project Structure

```bash
Animated-Birthday-Cake/
│
├── index.html       # Semantic HTML5 markup, SVG morphing shapes & canvas
├── style.css        # Typography, keyframes, candle, flame, balloons styling
├── script.js        # jQuery click handlers, canvas particles, confetti triggers
├── LICENSE          # MIT Open Source License
└── README.md        # Project documentation
```

---

## 🚀 Getting Started

No complicated build tools or dependencies required. It runs natively in any modern web browser!

### 1. Clone the repository
```bash
git clone https://github.com/saklincodes/Animated-Birthday-Cake.git
cd Animated-Birthday-Cake
```

### 2. Run the application
Simply open `index.html` in your favorite browser:
- **Directly**: Double-click `index.html`.
- **VS Code Live Server**: Right-click `index.html` and click **"Open with Live Server"**.
- **Python local server** (optional):
  ```bash
  python -m http.server 8000
  ```
  Then visit `http://localhost:8000`.

---

## 🛠️ Built With

* **HTML5** & **SVG SMIL Animations** - Vector shapes and timeline-based path morphing.
* **CSS3** - Keyframe animations, 3D pseudo-elements, custom clip-paths, and flexbox/positioning.
* **JavaScript (ES6+)** - Canvas 2D particle simulation and physics loops.
* **[jQuery](https://jquery.com/)** - Lightweight event handling and DOM manipulation.
* **[Canvas Confetti](https://www.kirilv.com/canvas-confetti/)** - High-performance celebratory particle effects.
* **Google Fonts** - *Lato* typography.

---

## 🎨 Customization

### Changing the Name or Message
Open [index.html](file:///d:/Reels/Animated%20Birthday%20Cake/index.html) and locate lines 188–191:
```html
<div class="text">
  <h1>happy birthday!</h1>
  <p>Hayati</p> <!-- Replace with your recipient's name -->
</div>
```

### Changing Balloon Colors
Open [style.css](file:///d:/Reels/Animated%20Birthday%20Cake/style.css) and customize the balloon color hex codes:
```css
.balloon1 { background-color: #D4AF37; /* Gold */ }
.balloon2 { background-color: #C0C0C0; /* Silver */ }
.balloon3 { background-color: #FFB6C1; /* Pink */ }
.balloon4 { background-color: #87CEEB; /* Sky Blue */ }
.balloon5 { background-color: #F5F5DC; /* Cream */ }
```

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!
Feel free to check the [issues page](https://github.com/saklincodes/Animated-Birthday-Cake/issues).

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

Distributed under the **MIT License**. See [`LICENSE`](./LICENSE) for more information.

---

## 👤 Author

**Saklin**
- GitHub: [@saklincodes](https://github.com/saklincodes)
- Instagram: [@saklin_01](https://instagram.com/saklin_01)

---

<div align="center">
  Made with ❤️ by <a href="https://github.com/saklincodes">Saklin</a>
</div>
