Speech Recognition System


This project is a **Speech Recognition Web Application** that allows users to either:
- Record audio in real-time using their **microphone**.
- Upload an existing **MP3 or WAV audio file**.

It then processes the audio and performs speech-to-text transcription using **Google Speech Recognition API**.

---

## ✅ Features
- 🎤 Record live audio from your microphone via the browser.
- 📂 Upload MP3 or WAV audio files.
- 🔄 Automatically converts MP3 to WAV format if necessary.
- ⚡ Processes the audio using `speech_recognition`.
- ✅ Uses Google’s Speech Recognition API for transcription.
- 🚫 Gracefully handles errors (e.g., unrecognized audio, API issues).
- 🌐 Simple web interface powered by **Gradio**.
---


## 🚀 How It Works
1. User visits the web page hosted via **Gradio**.
2. They can either:
    - Record audio live using the microphone.
    - Upload an MP3/WAV audio file.
3. If the uploaded file is MP3, it is converted to WAV format.
4. The audio is processed using Python’s `speech_recognition` library.
5. Google API performs the transcription.
6. Transcribed text is displayed in the web interface.
<img width="1295" height="657" alt="Screenshot 2025-09-16 at 12 04 17 PM" src="https://github.com/user-attachments/assets/1ac46e27-a90e-4dbe-af20-9fbccc99b544" />
<img width="1292" height="644" alt="Screenshot 2025-09-16 at 12 05 11 PM" src="https://github.com/user-attachments/assets/66a542d2-844c-4279-895f-bc8bd569faf9" />
<img width="1289" height="640" alt="Screenshot 2025-09-16 at 12 06 56 PM" src="https://github.com/user-attachments/assets/8e8ba0c2-64d8-415a-b290-a0e77b9769bd" />

