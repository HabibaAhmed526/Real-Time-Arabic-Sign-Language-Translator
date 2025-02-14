# Real-Time Arabic Sign Language Translator

This repository contains a multi-module Python project that builds an Arabic Sign Language (ASL) recognition system using hand landmarks. The project includes:

• A dataset creation script using MediaPipe to extract hand landmarks from images
• A machine learning training script that trains a RandomForest classifier on the landmarks
• A real-time detection module that uses a webcam to recognize ASL gestures
• A GUI application built with CustomTkinter that displays the video feed, the predicted text, and includes a Text-To-Speech (TTS) function for audio playback
