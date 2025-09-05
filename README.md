# English to Indian Language Video Translator

This Python project automatically translates the audio from an English video into any Indian regional language and merges the translated audio back into the video. It’s useful for content creators, educators, and anyone who wants to make videos accessible in multiple Indian languages.

---

## Features

- Extracts audio from video files using **FFmpeg**.
- Converts audio to WAV for transcription.
- Transcribes English audio using **SpeechRecognition**.
- Translates English text to any Indian regional language using **Google Translator (deep-translator)**.
- Converts translated text to speech using **gTTS**.
- Replaces the original video audio with the translated speech.
- Supports multiple Indian languages (Hindi, Tamil, Bengali, Telugu, Marathi, Gujarati, Kannada, Malayalam, Punjabi, etc.).
- Easy to change target language by updating `TARGET_LANG`.

*Future updates planned:*  
- Detect voice gender (male/female) for more natural-sounding speech.
- Improve TTS output to sound more natural and expressive.

---


