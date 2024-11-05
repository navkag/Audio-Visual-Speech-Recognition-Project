# Audio-Visual Speech Recognition with Conformer-Based Fusion

This repository contains the implementation and report for an audio-visual speech recognition model utilizing Conformers for feature extraction and gated fusion for multimodal data. The model processes audio and video features separately, fuses them using a gated mechanism, and uses a Transformer-based architecture to make predictions.

## Overview:
This project explores the use of Conformer-based models for end-to-end audio-visual speech recognition. The modular design allows testing individual modalities (audio-only, video-only) and combined (audio-visual) to evaluate the effect of each modality on overall model performance.

## Features:
Conformer-based encoding for both audio and video inputs
Gated fusion module to dynamically weigh audio and video features
Transformer-based decoding to generate transcripts
Support for individual modality testing
Pre-trained models and Jupyter notebook for easy experimentation

## Clone the repository
git clone https://github.com/navkag/Audio-Visual-Speech-Recognition-Project.git
cd Audio-Visual-Speech-Recognition-Project

## Install dependencies
pip install torch torchvision torchaudio
pip install opencv-python scipy scikit-image av six mediapipe ffmpeg-python

## Usage
To test the model with a sample video and experiment with audio-only, video-only, or audio-visual inference:
Run the Jupyter Notebook: Open the inference_notebook.ipynb in Google Colab or Kaggle Notebooks and follow the steps to run inference and see results across modalities.

## References
End-to-end Audio-visual Speech Recognition with Conformers, Pingchuan Me et al (2021)
