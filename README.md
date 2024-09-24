PROJECT DESCRIPTION:
This project is a real-time language translation application used with Google Gemini AI, utilizing speech recognition and speech synthesis to translate spoken English into Chinese text. The project takes advantage of Google Gemini's generative AI model to translate spoken input and uses the Google Text-to-Speech (gTTS) library to play the audio translation back to the user. The application runs on Python, and uses pygame for handling audio playback and speech_recognition for capturing voice input.

FEATURES:
* Real-time English-to-Chinese translation.
* Speech-to-Text functionality using Google Gemini AI.
* Text-to-Speech (TTS) functionality using gTTS for audio output in Mandarin Chinese.
* Audio playback handled through pygame.
* Logs the conversation into a text file for review.

TECHNOLOGIES THAT WERE USED:
* Google Gemini AI for real-time language translation.
* gTTS (Google Text-to-Speech) for generating audio output in Chinese.
* Pygame for playing audio files.
* SpeechRecognition for recognizing voice input.
* Python programming language.

CHALLENGES AND FUTURE FEATURES
* Implementing accurate real-time voice recognition with varying environmental noise.
* Managing audio playback efficiently with pygame.
* Handling exceptions gracefully for smoother user experience.

*******

Required:
* google-generativeai
* pygame
* gTTS
* SpeechRecognition
* Setting up the Google Gemini API
* Get your Google Gemini AI API key.
* Configure your API key by adding it to the environment variables or directly in the code.
* Python

*genai.configure(api_key="your-own-google-ai-api-key")

HOW TO USE THE PROJECT:
* Make sure your microphone is connected and working.
* After running the project, the system will listen for speech.
* Speak clearly in English, and the application will respond in Chinese with a voice translation.
* The translated audio will be played through your speakers.
* All conversations will be logged in a file named chatlog-<date>.txt for review.


![image](https://github.com/italia713/GoogleGenerativeAILanguageTranslator/assets/68444573/e57fa261-c723-4503-a5a6-56137f3d7a92)
