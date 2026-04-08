# 🧺 Laundry Wallah

A responsive and modern **Laundry Service Website UI** built using **HTML & CSS**, featuring smooth animations and a clean layout.

---

## 🚀 Features

* 📱 Fully Responsive Design (Desktop, Tablet, Mobile)
* 🎨 Clean and Modern UI
* 🧭 Navigation Bar with Logo & Links
* 🖼️ Hero Section with Image & Content
* ✨ CSS Animation (Orbit + Squeeze Effect)
* 🖱️ Interactive Button Design
* ⚡ Smooth Transitions & Hover Effects

---

## 🛠️ Technologies Used

* **HTML5**
* **CSS3 (Flexbox, Media Queries)**
* **CSS Animations (Keyframes & Transforms)**

---

## 🎯 Animation Highlights

### 🔄 Orbit Animation

The washing machine image moves in a square path using `@keyframes`.

* Uses `translate()` for movement
* Includes a **pause effect** between 75%–85%
* Adds **scale transform** for a squeeze effect

```css
@keyframes orbit {
    0%, 100% {
        transform: translate(0, 0);
    }
    25% {
        transform: translate(70px, 0);
    }
    50% {
        transform: translate(70px, 70px);
    }
    75% {
        transform: translate(0, 70px);
    }
    80%, 85% {
        transform: translate(0, 70px) scale(0.9, 1.2);
    }
}
```

---

## 📂 Project Structure

```
Laundry-Wallah/
│
├── index.html
├── style.css
├── images/
│   ├── WALLAH.png
│   ├── washing-machine.png
│
└── favicon.png
```

---

## 💻 How to Run the Project

1. Download or clone the repository:

   ```
   git clone https://github.com/your-username/laundry-wallah.git
   ```

2. Open the project folder

3. Run `index.html` in your browser

---

## 📱 Responsive Design

* ✅ Desktop: Full layout with navigation
* ✅ Tablet: Adjusted spacing and font sizes
* ✅ Mobile: Stacked layout for better readability

---

## 🎨 UI Preview

* Left section → Text & CTA button
* Right section → Animated washing machine
* Top → Navigation bar with logo & username

---

## 🔥 Future Improvements

* Add JavaScript functionality (booking system)
* Integrate backend (Node.js / Firebase)
* Add login/signup system
* Improve animations (circular orbit, loader effects)
* Add real service pages

---

## 🙌 Author

**Antef**

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!
