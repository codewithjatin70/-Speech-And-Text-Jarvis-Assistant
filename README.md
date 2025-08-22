# 🎙️ Speech-to-Text **Jarvis Assistant**

> A **smart voice and text assistant** built with Python — open apps, take commands, and respond like Jarvis!

---

## ✨ **Features**

* 🎤 **Voice & Text Modes** – Use either microphone or keyboard to interact.
* ⚡ **Fast App Launching** – Open common apps like Chrome, Notepad, VS Code, or Calculator with one command.
* 🤖 **Predefined Smart Commands** – Handles basic conversational inputs (e.g., `hello`, `how are you`, `shutdown`).
* 🛡 **Error Handling** – Smoothly handles unrecognized inputs or missing apps.
* 🛠 **Easily Customizable** – Add or edit commands in the predefined command dictionary.

---

## 📂 **Project Structure**

```
speech-to-text-jarvis/
│
├── Speech to text.py     # Main script for assistant
├── requirements.txt      # Python dependencies
└── README.md             # Project documentation
```

---

## 🚀 **Installation**

### **1. Clone the Repository**

```bash
git clone https://github.com/codewithjatin70/-Speech-And-Text-Jarvis-Assistant
cd Speech-And-Text-Jarvis-Assistant
```

### **2. Install Dependencies**

```bash
pip install -r requirements.txt
```

### **3. (Optional) Setup `.env` for APIs**

Create a `.env` file in the project folder if using APIs like Groq , News , Weather , Hugging as Api :

```

GROQ_API_KEY=
NEWS_API_KEY=
WEATHER_API_KEY=
HUGGINGFACE_API_KEY=
```

---

## 🖥 **Usage**

Run the assistant:

```bash
python "Jarvis Program"
```

Select input mode:

* Type `t` → **Keyboard Input**
* Type `v` → **Voice Command**

### **Example Interaction**

```
📌 Choose mode: (t = type, v = voice) : v
🎤 Listening...
✅ You said: open chrome
🗣️ Jarvis: Opening Chrome now, sir.
```

---

## 🧾 **Supported Commands**

| **Category**      | **Example Commands**                | **Action**                   |
| ----------------- | ----------------------------------- | ---------------------------- |
| **Greetings**     | `hello`, `hi jarvis`, `how are you` | Friendly response            |
| **System Apps**   | `open notepad`, `open calculator`   | Opens respective system apps |
| **Web Apps**      | `open youtube`, `open google`       | Opens websites in browser    |
| **Exit Commands** | `stop`, `shutdown jarvis`           | Closes the assistant         |

---

## ⚙ **Dependencies**

Install manually if needed:

```bash
pip install SpeechRecognition pyttsx3 pyaudio python-dotenv
```

---

## 🔮 **Future Enhancements**

* 🌐 Integration with **AI APIs** for intelligent Q\&A.
* ⏰ Built-in **reminders and task management**.
* 🗣 Wake-word detection (e.g., **“Hey Jarvis”**).
* 🎵 Play music and fetch live data.

---

## 🤝 **Contributing**

Contributions are welcome!

1. Fork the repo
2. Create a new branch (`feature-branch`)
3. Commit your changes
4. Open a Pull Request

---

## 📜 **License**

This project is licensed under the [MIT License](LICENSE).

---
### 🏷 **Badges**

![Python](https://img.shields.io/badge/Python-3.8+-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)
