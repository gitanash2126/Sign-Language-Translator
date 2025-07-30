# Sign-Language-Translator
# 🧠 Sign Language Translator | by gitanash2126

Welcome to the **Sign Language Translator**, a web-based application that allows users to train and translate hand gestures using sign language. This tool is designed to help users train custom gestures and interpret them in real-time using webcam input.

![Sign Translator](Images/asl_logo.ico)

---

## 🚀 Features

- 🎥 Real-time webcam input for capturing gestures.
- 🧑‍🏫 Custom gesture training for **Start** and **Stop** actions.
- ✋ Add and train additional gestures with custom labels.
- 💬 Live gesture translation.
- 📞 Built-in **video call support** using TokBox for communication.
- 📱 Responsive and animated UI using `animate.css`.

---

## 📁 Project Structure

root/
├── index.html # Main HTML file (this project)
├── CSS/
│ ├── style.css # Custom styles
│ └── animate.css # Animation styles from animate.css
├── Images/
│ ├── asl_logo.ico # Favicon/logo
│ └── plus_sign.svg # Plus icon for adding gestures
├── dist/
│ └── build.js # Compiled JavaScript for gesture logic


---

## 🛠️ How It Works

1. **Welcome Screen**: User is greeted and asked to proceed.
2. **Gesture Training**:
   - Train around **30 samples** for each of the **Start** and **Stop** gestures.
   - Visual counters and checkmarks confirm training progress.
3. **Translation**:
   - Once trained, click `Translate` to detect and display real-time gestures.
4. **Add Gestures**:
   - Input a custom gesture title and train it.
   - Use the `Done Retraining` button to finalize training.
5. **Video Call**:
   - Embedded TokBox video call iframe allows live communication with sign language.

---

## 🧑‍💻 Technologies Used

- **HTML5 / CSS3 / JavaScript**
- **Google Fonts**
- **animate.css**
- **TokBox (OpenTok)**
- **Custom gesture training logic (JavaScript)**

---

## ✅ Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/gitanash2126/sign-translator.git
   cd sign-translator
