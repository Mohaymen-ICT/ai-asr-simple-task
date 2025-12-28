# AI Engineer Interview - Practical Task: Automatic Speech Recognition (ASR)

## Overview
This repository contains a sample audio file for a practical interview question for the AI Engineer position. The goal is to assess your ability to implement an end-to-end ASR (Automatic Speech Recognition) system using modern AI techniques.

You are required to create a complete Google Colab notebook that processes the provided audio file and outputs the transcribed text. The notebook should demonstrate your skills in data handling, model selection/implementation, and inference.

## Task Description
1. **Input**: Use the sample audio file provided in this repository: `sample_audio.mp3` (or replace with the actual filename if different). This is a short voice recording in Persian for testing ASR capabilities.

2. **Requirements**:
   - Implement an ASR algorithm from scratch or using pre-trained models (e.g., via libraries like Hugging Face Transformers, SpeechRecognition, or Whisper by OpenAI). You may fine-tune if necessary, but keep it efficient for Colab.
   - The notebook must include:
     - Loading and preprocessing the audio file (e.g., handling sampling rate, noise reduction if needed).
     - The core ASR model/inference pipeline.
     - Output: The transcribed text from the audio.
     - Evaluation: Optionally, include metrics like Word Error Rate (WER) if you have a ground truth transcript (not provided; you can assume or generate one for demo).
   - Use Python and standard libraries/tools available in Colab (e.g., install dependencies like `transformers`, `torch`, `librosa`, etc., via `!pip install`).
   - Ensure the notebook is self-contained, runnable in Colab, and well-documented with comments explaining each step.
   - Handle edge cases: Audio format compatibility, potential errors, and runtime efficiency (should run in under 5-10 minutes on Colab's free tier).

3. **Deliverables**:
   - A single Google Colab notebook (.ipynb file AND its shareable LINK).
   - The final output cell should print the transcribed text clearly, e.g.:
     ```
     Transcribed Text: "This is a sample voice for ASR testing."
     ```
   - Submit the notebook via [email/link/pull request] as instructed in the interview process.

## Guidelines
- **Time Limit**: Complete this by the required deadline that your AI mentor/interviewer told to simulate real-world problem-solving.
- **Originality**: Avoid copying entire code blocks from tutorials; demonstrate understanding by customizing the implementation.
- **Best Practices**: Use version control (e.g., commit your notebook to a fork of this repo if possible), modular code, and error handling.
- **Resources**: You can reference open-source models like Whisper, Wav2Vec, or CTC-based approaches. No proprietary APIs without free access.
- **Questions?** If anything is unclear, ask during the interview.

## Getting Started
1. Fork or clone this repository.
2. Open Google Colab: Go to [colab.research.google.com](https://colab.research.google.com) and upload/create your notebook.
3. Download the `sample_audio.mp3` from this repo and upload it to your Colab session (or access via GitHub URL).
4. Implement and test your ASR pipeline.

Good luck! We're excited to see your solution.
