# Arc_Chatbot
ARC is a simple offline Python chatbot using pyttsx3 for text-to-speech. It responds to basic greetings and emotional prompts with friendly, predefined replies. Lightweight, easy to modify, and works without internet. Perfect for beginners exploring chatbots and offline TTS.


# 🤖 ARC – Offline AI Chatbot (Python + pyttsx3 TTS)

ARC is a lightweight offline AI chatbot built using Python and pyttsx3.
It can talk to you using **offline text-to-speech**, understand basic greetings, emotions, and answer simple questions — all without internet.

It’s designed for learning, fun, and beginner-friendly AI interaction.

---

## 🚀 Features

### 🔊 Offline Text-to-Speech

* Uses **pyttsx3**
* Works without internet
* Supports female & male voices

### 💬 Smart Predefined Responses

ARC can respond to:

* Greetings (hello, hi, good morning)
* Emotions (I am sad / happy)
* Funny prompts (tell me a joke)
* Motivational lines
* Basic AI questions
* Exit & goodbye commands

### ⚡ Fast & Lightweight

* No external APIs
* No cloud dependency
* Runs on low-end laptops

### 🎛 Customizable

* Add your own responses
* Change voice
* Modify speaking speed
* Extend chatbot behaviour

---

## 🎮 Controls (Chat Commands)

| User Input     | Bot Response      |
| -------------- | ----------------- |
| hello / hi     | Greeting back     |
| how are you    | Bot status        |
| motivate me    | Motivational line |
| tell me a joke | A funny joke      |
| bye            | Exit message      |
| what is AI     | Basic definition  |

…and many more.

---

## 🛠 Tech Stack

* **Python 3.x**
* **pyttsx3** (Offline TTS)

---

## 📦 Installation

1️⃣ **Install Dependencies**

```bash
pip install pyttsx3
```

2️⃣ **Run the Chatbot**

```bash
python arc_chatbot.py
```

---
3️⃣ **Clone the Repo
```bash
git clone https://github.com/codertheashish/Arc_Chatbot.git
```

## ▶ How It Works

* User types input in console
* Chatbot checks keywords
* Returns predefined response
* pyttsx3 speaks the output
* Loop continues until you type `exit`

---

## 📁 File Structure

```
ARC-Chatbot/
│── arc_chatbot.py
│── README.md
```

---

## 🤖 ARC’s Working Logic

* Converts text to speech with pyttsx3
* Detects common phrases
* Matches them with stored responses
* Generates audio + text output
* Fully local processing—no internet

---

## 🌟 Future Upgrades

* Add emotion detection
* GUI-based ARC chatbot
* Add more conversation topics
* Add voice input (SpeechRecognition)
* Store chat history

---

## 📜 License

This project is open-source under MIT License.

---

## 👨‍💻 Author

**Ashish Kumar Prajapati**

