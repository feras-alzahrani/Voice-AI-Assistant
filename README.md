# Voice AI Assistant

## Overview
This project implements a simple Voice AI Assistant that processes spoken input through three main stages:

1. Convert speech to text using OpenAI Whisper.
2. Generate an intelligent response using Cohere LLM.
3. Convert the generated response back to speech using Google Text-to-Speech (gTTS).

The project demonstrates the complete Speech-to-Text → LLM → Text-to-Speech pipeline.

---

## Features

- Speech-to-Text using Whisper
- AI-generated responses using Cohere
- Text-to-Speech using gTTS
- Arabic language support
- Simple and easy-to-understand implementation

---

## Technologies Used

- Python
- OpenAI Whisper
- Cohere API
- gTTS
- Google Colab

---

## Project Workflow

```
Speech Input
      ↓
OpenAI Whisper
      ↓
Extracted Text
      ↓
Cohere LLM
      ↓
AI Response
      ↓
gTTS
      ↓
Audio Output
```

---

## How to Run

1. Install the required libraries.
2. Configure your Cohere API key.
3. Upload an audio file.
4. Run the notebook cells sequentially.
5. Listen to the generated audio response.

---

## Author

**Feras Alzahrani**
