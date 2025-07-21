# Igbo Text-toSpeech Web App
This project is a *Text-to-Speech (TTS)* web app for the *Igbo language, built using **Gradio* and powered by the *ElevenLabs API. Users can type Igbo text, select a voice (like **Eze*), and hear the spoken output — with options to download the generated audio.

---

## Project Focus

- Language Support*: Igbo (ISO 639-1: ig)
- Voice ID Used*: Eze – Voice ID: QLniWkGYsJa91mXrxl3ç
- *API Used*: [ElevenLabs Text-to-Speech](https://www.elevenlabs.io)
-*  Features**:
  - Text input for Igbo language
  - Dropdown to select different voices
  - Audio playback & download
  - Emojis and headers for enhanced UI
  - Basic pronunciation tuning using commas and pauses

---

##How It Works

1. *User types* a sentence in Igbo
2. Selects a *voice from dropdown*
3. Clicks *“Generate Speech”*
4. The app sends the request to ElevenLabs
5. Receives & plays back the audio using Gradio
6. Option to *download* the audio as .mp3

---

## Demo Video

Watch the full app demo here:  
[https://www.loom.com/share/b1f3b9e42fbd432b96eda14e9add2903?sid=d6f3eea6-2795-429a-bbf6-c52fc199c0ed]
(demo-video.mp3)

---

## Pronunciation Optimization

- Igbo tones are *context-sensitive, so we used **manual punctuation (commas, periods)* to simulate natural pauses and emphasis
- Tested different ElevenLabs voices like *Antoni, **Rachel, and **Eze*
- *Eze voice* was found to pronounce Igbo words more accurately

---

##Technologies Used

| Tool         | Purpose                         |
|--------------|----------------------------------|
| Gradio       | Frontend app UI                 |
| ElevenLabs   | Text-to-speech generation       |
| Google Colab | Development environment         |
| Python       | Core logic                      |

---

## Files Included

- app.py – Main Gradio app
- README.md – This file
- demo-video.mp4 – Screen recording of usage
- reflection.txt – What worked, challenges, and lessons learned

---

## Installation (for local run)

```bash
git clone https://github.com/yourusername/igbo-tts-app.git
cd igbo-tts-app
pip install -r requirements.txt
streamlit run app.py 


Author
Jennifer Onyeukwe
