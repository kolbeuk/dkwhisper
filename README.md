# dkwhisper
Multilingual Whisper-Llama2 Integration for Speech Recognition and Translation
Introduction
This Python script is an innovative tool that combines the powerful capabilities of OpenAI's Whisper large-v3 model with Meta's Llama2 model. It is specifically designed to transcribe spoken content from video files and then translate it, making it an invaluable resource for users in multilingual environments.

Features

Efficient Speech Recognition: Leverages Whisper large-v3 for accurate transcription of audio from video files.

Seamless Language Translation: Integrates with Meta's Llama2 model for reliable translation of the transcribed text.

Requirements
The Whisper model must be installed as per the official guidelines from OpenAI. https://github.com/openai/whisper

ollama.ai https://ollama.ai

The Llama2 model should be set up and accessible through a local API.

Requests library for Python.

Usage

Run the script via the command line, providing the paths to the video files as arguments. For example:

python3 dkwhisper.py /path/to/video1.mp4

Output

The script will output the transcribed text, followed by its translation. Transcription and translation are both printed to the console.

Acknowledgements
OpenAI: This project utilizes the OpenAI API for advanced AI-based image and text processing. Code snippets and guidance from OpenAI's documentation and resources have been instrumental in the development of this project.
Meta: Acknowledgment is given to Meta for the development of the Llama2 model, which has significantly contributed to the AI capabilities of this project.
ollama.ai: Gratitude is extended to llama.ai for enabling the local hosting of the Llama2 model, enhancing the accessibility and performance of the project.

Note
This script is intended as a demonstration and may require modifications for production use.
