
# Speech to Text for Transcription Services

## 📑 Description

This project demonstrates how to build a **Speech-to-Text (STT) transcription system** using Python. It processes audio files, converts speech into written text, and outputs the transcriptions. The primary goal is to automate transcription for applications such as interviews, lectures, customer service calls, or accessibility services.

## 🚀 Key Features

- Reads audio files (WAV format)
- Converts speech to text using the `speech_recognition` library
- Handles exceptions for unknown or unintelligible audio
- Outputs the transcription results clearly

## 🛠️ Technologies Used

- Python 3
- Jupyter Notebook
- `speech_recognition` (Google Web Speech API)
- `pydub` for audio processing
- `IPython.display` for audio playback

## 📦 Installation

```bash
pip install SpeechRecognition
pip install pydub
```

Also, make sure **FFmpeg** is installed for `pydub` to handle audio files:

```bash
# For Linux
sudo apt install ffmpeg

# For Windows/Mac
# Download from https://ffmpeg.org/download.html and set it in your system path
```

## 🧪 How to Run

1. Open the notebook in Jupyter.
2. Upload or point to a `.wav` file.
3. Run all cells to process and transcribe the audio.
4. Read the transcription in the output.

## 📌 Notes

- Accuracy depends on audio quality and background noise.
- The default recognizer is the free Google Web Speech API, which requires an internet connection.
