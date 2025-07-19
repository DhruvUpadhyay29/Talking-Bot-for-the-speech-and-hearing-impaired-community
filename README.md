# Talking-Bot-for-the-speech-and-hearing-impaired-community

# 🤖 Talkative Bot for Speech Impaired

A gesture-based communication tool designed to assist speech-impaired individuals by translating hand gestures into recognizable actions or spoken output using real-time machine learning in the browser.

---

## 🚀 Features

- 🖐️ Real-time gesture recognition using webcam input
- 🧠 KNN-based image classification with TensorFlow.js
- 🗣️ Text-to-Speech output for recognized gestures
- 💻 100% client-side — no backend required
- 🎨 Responsive and animated UI for accessibility

---


## 📁 Project Structure

```
Talkative-Bot/
├── index.html              # Main entry point
├── main.js                 # Gesture logic with TensorFlow.js
├── dist/
│   └── build.js            # Compiled output (from main.js)
├── CSS/
│   ├── style.css
│   └── animate.css
├── Design/
│   ├── Logos/
│   └── Configuration/
└── README.md
```

---

## 🛠️ Getting Started

### Option 1: Run Directly in Browser

> If `dist/build.js` already exists, simply open the app.

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/talkative-bot.git
   cd talkative-bot
   ```

2. Open `index.html` in your web browser.

3. Allow webcam access when prompted.

---

### Option 2: Build from Source (if `build.js` is missing)

1. Install [Node.js](https://nodejs.org/) and npm.

2. Install dependencies:
   ```bash
   npm install
   ```

3. Build the app:
   ```bash
   npm run build
   ```

4. Serve locally using:
   ```bash
   npx http-server .
   ```

5. Open the local server URL in your browser.

---

## 💡 How It Works

- Uses your webcam to capture live video.
- Allows training of custom gestures (e.g., “start”, “stop”).
- Uses **KNN (K-Nearest Neighbors)** for classifying hand gestures.
- Converts recognized gestures into **text and optionally speech** using browser APIs.

---

## 📦 Built With

- [TensorFlow.js](https://www.tensorflow.org/js)
- [deeplearn.js](https://github.com/PAIR-code/deeplearnjs) (legacy)
- HTML5 + CSS3 + Vanilla JavaScript
- Web Speech API (Text-to-Speech)

---

## 👨‍💻 Authors

- Dhruv Upadhyay  

---

## 📄 License

This project is licensed under the MIT License.

---

## 🙌 Acknowledgements

- Inspired by communication needs of the speech-impaired community.
- Thanks to TensorFlow.js for browser-based machine learning tools.
