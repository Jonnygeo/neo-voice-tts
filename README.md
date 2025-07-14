<p align="center"> <a href="https://neo-shade.com"> <img src="https://neo-shade.com/wp-content/uploads/2025/07/NeoLegacyBanner.jpg" height="180"> </a> <h1 align="center"> Neo Voice TTS </h1> </p> <p align="center"> <a href="https://x.com/neoshade2025"> <img src="https://img.shields.io/badge/X-Twitter-black?style=for-the-badge&logo=twitter&logoColor=white"> </a> <a href="https://youtube.com/@neoshade"> <img src="https://img.shields.io/badge/YouTube-Subscribe-red?style=for-the-badge&logo=youtube&logoColor=white"> </a> <a href="https://social.neo-shade.com"> <img src="https://img.shields.io/badge/NeoShade%20Social-Join-blueviolet?style=for-the-badge&logo=discourse&logoColor=white"> </a> </p>
🔊 What is Neo Voice TTS?
Neo Voice TTS is a plug-and-play voice rendering module that transforms any written message into human-like audio using ElevenLabs. It’s built for the NeoLegacy system to turn truth, emotion, and memory into sound.

This module acts as the final voice output engine — whether you're delivering bedtime messages to your child, final words, spiritual confessions, or future-dated audio reminders.

✨ Features
🎙️ ElevenLabs TTS Integration (all voice models)

🔁 Text-to-Voice rendering for legacy messages

📦 Outputs playable audio streams or downloadable .mp3s

🔐 API key secured & modular

🧠 Ready for integration with AI agents, vaults, and timelines

⚙️ Technology
Node.js

@elevenlabs/elevenlabs-js SDK

MP3/audio stream handler

Works locally or server-side

Can plug into NeoLegacy voice delivery system

📦 Setup
bash
Copy
Edit
git clone https://github.com/Jonnygeo/neo-voice-tts.git
cd neo-voice-tts
npm install
Create a .env file with your ElevenLabs API key:

ini
Copy
Edit
ELEVENLABS_API_KEY=your_api_key_here
🧩 Connected Modules
Module	Role
neo-voice-core	Requests voice render from text
neo-msg-deliver	Delivers rendered audio messages
NeoLegacy	Plays voice clips from dashboard

📜 License
Private — For internal NeoLegacy / NeoShade AI use only.

👤 Author
Built by Jonathan
“Every word you speak should last longer than your voice. Now it can.”
