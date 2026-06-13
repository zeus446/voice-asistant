# voice-asistant

# 🎙️ Hello-App

A simple Python voice assistant that listens to your commands and performs useful tasks like playing music, searching Wikipedia, telling jokes, and providing the current time.

This project was created as a beginner-friendly introduction to voice recognition, text-to-speech systems, and Python automation.

---

## ✨ Features

- 🎵 Play songs directly on YouTube
- 🕒 Tell the current time
- 📖 Search Wikipedia and read summaries aloud
- 😂 Tell random jokes
- 💬 Respond to basic conversational commands
- 🎤 Voice-controlled interaction using your microphone

---

## 🛠️ Built With

- Python 3
- SpeechRecognition
- pyttsx3
- PyWhatKit
- Wikipedia
- PyJokes
- PyAudio

---


## 🚀 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/zeus446/Hello-app.git
cd Hello-app
```

### 2. Install Dependencies

```bash
pip install SpeechRecognition pyttsx3 pywhatkit wikipedia pyjokes pyaudio
```

If PyAudio fails to install on Windows:

```bash
pip install pipwin
pipwin install pyaudio
```

---

## ▶️ Running the Assistant

```bash
python main.py
```

The assistant will begin listening for commands through your microphone.

---

## 🎤 Available Voice Commands

### Play Music

Say:

```text
Alexa play Shape of You
```

Result:

- Opens YouTube
- Plays the requested song

---

### Get the Current Time

Say:

```text
Alexa what is the time
```

Result:

- Reads the current time aloud

---

### Search Wikipedia

Say:

```text
Alexa who is Elon Musk
```

Result:

- Fetches a short Wikipedia summary
- Reads it aloud

---

### Tell a Joke

Say:

```text
Alexa tell me a joke
```

Result:

- Reads a random joke

---

### Casual Conversation

Say:

```text
Alexa how are you
```

Result:

```text
I am spiffing
```

---


## ⚠️ Requirements

- Python 3.8+
- Working microphone
- Internet connection

Internet access is required for:

- Speech recognition
- Wikipedia searches
- YouTube playback

---

## 🔮 Future Improvements

- Open desktop applications
- Weather updates
- AI-powered conversations
- Voice-controlled email sending
- Smart home integration
- Custom wake word
- Offline speech recognition
- Better error handling

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a new branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Added new feature"
```

4. Push to your branch

```bash
git push origin feature-name
```

5. Open a Pull Request

---

## 👨‍💻 Author

**Siddharth S**

GitHub: https://github.com/zeus446

---

## ⭐ Support

If you found this project useful, please consider giving it a star on GitHub.

A star helps others discover the project and motivates future development.

⭐ Star the repository: https://github.com/zeus446/Hello-app
