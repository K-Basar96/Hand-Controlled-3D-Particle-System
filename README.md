# Interactive Hand-Controlled 3D Particle System

### [🔴 **Click Here to View Live Demo**](https://basar.page.gd/?i=1)

A real-time web experiment that combines **Computer Vision** (MediaPipe) and **WebGL** (Three.js). This project uses your webcam to track hand gestures and manipulate a 3D particle cloud in the browser—no installation or heavy backend required.

## ✨ Features

* **Real-time Hand Tracking:** Tracks 21 3D hand landmarks directly in the browser.
* **Gesture Recognition:**
    * **Expand/Explode:** Open your hand to scatter particles.
    * **Contract/Implode:** Close your fist to pull particles tight.
    * **Shape Morphing:** Pinch your thumb and index finger to morph the system into different shapes (Sphere, Heart, Saturn, Flower).
    * **Dynamic Coloring:** Move your hand left or right to cycle through color hues.
* **Performance:** Renders 8,000+ interactive particles at 60fps using GPU acceleration.

## 🎮 Controls

| Gesture | Action |
| :--- | :--- |
| **Open Hand** 🖐 | **Expand:** Particles explode outward based on how wide your hand is open. |
| **Closed Fist** ✊ | **Contract:** Particles shrink tightly into the current shape. |
| **Pinch (Index + Thumb)** 👌 | **Switch Shape:** Triggers a morph transition (Sphere → Heart → Saturn → Flower). |
| **Hand Position (Left/Right)** ↔️ | **Color Shift:** Moving your hand across the screen changes the color hue. |

## 🛠 Tech Stack

* **[Three.js](https://threejs.org/):** For high-performance 3D rendering and particle management.
* **[MediaPipe Hands](https://google.github.io/mediapipe/solutions/hands.html):** For machine-learning-based hand tracking running entirely on the client side.
* **HTML5/CSS3:** For structure and overlay UI.

## ⚠️ Troubleshooting

**The screen is black / "Loading..." forever:**
* Ensure you have granted camera permissions to the browser.
* If you previously blocked the camera, click the "Lock" or "Camera" icon in your address bar to reset permissions and refresh the page.

## 📄 License

This project is open source and available for educational purposes.

---

*Created with ❤️ using Three.js and MediaPipe.*
