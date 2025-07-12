# Sign Language Interpreter (Web-Based)

GES Is a program uses a webcam and ML to recognize hand gestures, converting them into letters and sentences in real-time. empowering people with speech disabilities to communicate silently and independently.


## 🌐 Live Demo
Once deployed via GitHub Pages, your site will be accessible at:

```
https://<your-username>.github.io/<repo-name>/
```

## 🚀 Features

- 🌟 Real-time gesture detection
- ✍️ Letter-by-letter sentence building
- 🌓 Light and dark theme toggle
- 🧹 Clear and copy sentence buttons
- ⏳ Delayed output display after clearing (3 seconds)
- 📱 Fully responsive for mobile & desktop
- 🔒 HTTPS ready for secure webcam access

## 📁 Files

- `index.html` — Landing page with introduction and link to gesture interface
- `sign_all_platforms.html` — Main gesture recognition interface
- `README.md` — Project description and setup help

## 🛠️ How to Use

1. Open the site in a browser (must be served over HTTPS or localhost).
2. Allow camera access when prompted.
3. Click **Start** to begin gesture detection.
4. Use **Clear** to reset and **Copy** to copy the sentence.
5. Toggle 🌙 to enable stylish dark mode.

## 🚧 Known Issues

- May require HTTPS or local server to work due to webcam permissions.
- Best used with a model trained from [Teachable Machine](https://teachablemachine.withgoogle.com/).

## 🧑‍💻 Built With

- HTML5 + CSS3
- Vanilla JavaScript
- TensorFlow.js
- Teachable Machine Image Model

## 📦 Deployment Instructions (GitHub Pages)

1. Create a GitHub repo and upload these files.
2. Enable GitHub Pages via `Settings > Pages`.
3. Rename `demo.html` to `index.html` for automatic home page loading.

---

© 2025 Sign Language Interpreter | Made with ❤️
