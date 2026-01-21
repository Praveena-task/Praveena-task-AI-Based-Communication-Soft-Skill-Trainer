# System Architecture

This document describes the architecture of the AI-Based Communication and Soft Skill Trainer.

## Architecture Flow

1. User provides video input through webcam.
2. Video frames are processed using OpenCV.
3. Facial landmarks and gestures are extracted using MediaPipe.
4. Audio is extracted from video and analyzed.
5. NLP models analyze speech and communication patterns.
6. Feedback is generated and shown to the user.

## Architecture Diagram

![Architecture Diagram](architecture_diagram.png)
