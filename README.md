🎙️ Jarvis - AI Voice Assistant
A Python voice assistant named Jarvis that listens for commands after the wake word. It opens websites like Google, YouTube, Instagram, plays songs from a custom library, and answers general questions using Google’s Gemini AI. Uses speech recognition and text-to-speech for seamless interaction.

🎙️ Jarvis -
Jarvis is a Python-based voice assistant that responds to your voice commands using speech recognition. It can open websites, play songs from a defined list, and answer your questions using Google's Gemini AI.

🧠 How It Works
Voice Activation
Jarvis listens for the wake word: "Jarvis"

Voice Command
After activation, it listens to your command:

Example: "Open YouTube" → Opens the website

Example: "Play perfect" → Plays the song link defined in musicLibrery.py

Example: "What is AI?" → Answered by Google Gemini AI

Response
Jarvis speaks the response back using text-to-speech.

📚 Libraries Used
speech_recognition – For recognizing voice commands

pyttsx3 – To convert text to speech

webbrowser – To open websites

google.generativeai – To access Gemini AI (text-based responses)

requests – For potential future API uses

musicLibrery.py – Custom file storing song names and YouTube links

Install all using:

bash
Copy
Edit
pip install speechrecognition pyttsx3 google-generativeai requests
🔑 How to Get Gemini API Key
Visit: https://makersuite.google.com/app

Sign in with your Google account

Go to API Keys section

Create an API key

Replace "Your gemini api" in the code with your key:

python
Copy
Edit
api_key = "YOUR_GEMINI_API_KEY"
🎵 How to Add Songs
Edit musicLibrery.py like this:

python
Copy
Edit
music = {
    "perfect": "https://www.youtube.com/watch?v=2Vv-BfVoq4g",
    "calm": "https://youtu.be/example"
}
Then say:

mathematica
Copy
Edit
Play perfect
✅ Supported Voice Commands
"Open Google"

"Open YouTube"

"Open Instagram"

"Open Facebook"

"Open GitHub"

"Open WhatsApp"

"Open Telegram"

"Play [song name]"

Any general question → answered by Gemini AI

👤 Developer
KevalKing
Instagram: @keval_king_212

