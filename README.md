# 🤖 Karel Robot Game — Hand Gesture Control

A modern reimagining of the classic Karel robot game — now playable with **hand gestures** using your webcam! 🚀
Built with **HTML**, **CSS**, and **JavaScript**, powered by **MediaPipe Hands** for real-time gesture recognition.

---

## 🕹️ Features

* 👆 **Hand Gesture Commands** via webcam (powered by [MediaPipe Hands](https://github.com/google/mediapipe))
* ⌨️ **Keyboard Controls** for traditional gameplay
* 🎨 **Responsive, animated UI** with custom CSS
* 💎 Beeper pickup/drop system
* 🎮 Grid-based movement and real-time direction feedback

---

## ✋ Supported Hand Gestures

| Gesture             | Action         |
| ------------------- | -------------- |
| 👆 Point up         | `move()`       |
| ✋ Open hand (left)  | `turnLeft()`   |
| ✋ Open hand (right) | `turnRight()`  |
| 👍 Thumbs up        | `pickBeeper()` |
| ✊ Fist              | `putBeeper()`  |

> 🤖 Tip: Hold your hand in front of the webcam and perform one gesture at a time. Gesture input is debounced to prevent repeated execution.

---

## 🧠 Keyboard Shortcuts

| Key       | Action         |
| --------- | -------------- |
| `W` / `↑` | `move()`       |
| `A` / `←` | `turnLeft()`   |
| `D` / `→` | `turnRight()`  |
| `S` / `↓` | `pickBeeper()` |
| `Space`   | `putBeeper()`  |

---

## 📦 How to Use
can go to https://karel-cv.vercel.app or :

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/karel-gesture-game.git
   cd karel-gesture-game
   ```

2. **Open `index.html` in a Browser**

   > ✅ Preferably use Chrome or Edge — MediaPipe works best there.

3. **Click "Enable Gesture Control"**

   * Allow camera access when prompted
   * Show your hand in front of the camera
   * Start issuing gestures and have fun!

---

## 🧪 Technologies Used

* **HTML5/CSS3** — modern responsive UI
* **JavaScript** — game logic & gesture handling
* **MediaPipe Hands** — real-time hand tracking
* **CameraUtils & DrawingUtils** — WebRTC + overlay tools

---

## 📁 Folder Structure

```
/
├── index.html      # Main game file
├── README.md       # You're reading it!
```

---

## 🚧 Known Limitations

* Only detects **one hand** at a time
* Gesture recognition depends on **lighting & hand visibility**

---

## 📸 Permissions

This app **requires webcam access** for gesture detection. No camera data is stored or sent anywhere — everything runs locally in the browser.

---

## 🙌 Credits

* Hand tracking: [MediaPipe by Google](https://mediapipe.dev/)
* Inspired by Karel the Robot (Stanford CS Education)

---

## 🧩 License

MIT License — feel free to modify, share, and improve!

---