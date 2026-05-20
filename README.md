# Wav2Vec2 Speech Recognition Experiments

An exploration of Wav2Vec2 for automatic speech recognition, audio feature extraction, and speech-to-text processing using Hugging Face Transformers.

---

## Overview

This project explores transformer-based automatic speech recognition (ASR) pipelines using pretrained Wav2Vec2 architectures from Facebook AI and Hugging Face Transformers.

The notebook includes experiments involving:

- Speech-to-text transcription
- Audio feature extraction
- Transformer-based ASR pipelines
- Fine-tuning workflows
- Word Error Rate (WER) evaluation
- Hugging Face Trainer APIs

The implementation demonstrates how pretrained transformer models can process and transcribe raw audio waveforms into text.

---

## Models Explored

- `facebook/wav2vec2-base-960h`
- `facebook/wav2vec2-large-xlsr-53`
- Torchaudio WAV2VEC2 ASR pipelines
- AST (Audio Spectrogram Transformer)

---

## Features

- Automatic Speech Recognition (ASR)
- Audio preprocessing using Librosa
- Transformer-based speech modeling
- Feature extraction from raw audio
- Hugging Face Transformers integration
- Fine-tuning experiments on speech datasets
- WER (Word Error Rate) evaluation

---

## Tech Stack

- Python
- PyTorch
- Hugging Face Transformers
- Torchaudio
- Librosa
- Datasets
- Evaluate
- NumPy

---

## Dataset

Experiments were conducted using:

- Custom WAV audio samples
- PolyAI MINDS-14 dataset
- Pretrained Facebook AI speech models

---

## Project Pipeline

Audio Input  
→ Feature Extraction  
→ Wav2Vec2 Transformer Processing  
→ Speech Transcription  
→ Evaluation using WER

---

## Key Concepts Used

- Self-Supervised Learning
- Transformer-based ASR
- Connectionist Temporal Classification (CTC)
- Audio Embeddings
- Speech Representation Learning
- Word Error Rate (WER)

---

## Installation

Clone the repository:

```bash
git clone https://github.com/GantiYasaswini/wav2vec2-speech-recognition-experiments.git
cd wav2vec2-speech-recognition-experiments
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the notebook:

```bash
jupyter notebook
```

---

## Repository Structure

```text
wav2vec2-speech-recognition-experiments/
│
├── README.md
├── requirements.txt
├── .gitignore
├── LICENSE
├── wav2vec2_experiments.ipynb
│
└── sample_audio/
    └── audio.wav
```

---

## Future Improvements

- Fine-tuning on larger speech datasets
- Real-time ASR inference
- Multilingual speech recognition
- Speaker adaptation
- Deployment using Hugging Face pipelines

---

## Acknowledgements

- Hugging Face Transformers
- Facebook AI Research
- Torchaudio
- PolyAI MINDS-14 Dataset

---

## Author

Developed by Yasaswini Ganti as part of an exploration into transformer-based speech recognition and audio representation learning using Wav2Vec2 architectures.
