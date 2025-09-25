Video Classification and Description with BLIP Fine-tuning

This project implements a video classification and captioning system using BLIP (Bootstrapped Language-Image Pre-training) with partial fine-tuning. The system is designed to classify short video clips into predefined action categories and generate concise textual descriptions of the video content.

Features

Video Classification: Classifies videos into four action categories:
ApplyLipstick, PlayingPiano, TrampolineJumping, ShavingBeard.

Video Captioning: Generates a short description of the video using the BLIP model.

Frame-based Processing: Extracts frames from uploaded videos for efficient processing.

Gradio Interface: Provides a user-friendly web interface to upload videos and get predictions.

Partial Fine-tuning: Fine-tunes only the last layer of BLIP’s vision model along with a custom classifier to reduce training time and GPU memory usage.

Technologies Used

PyTorch – Deep learning framework.

Transformers – Pre-trained BLIP model and processor.

OpenCV – Video frame extraction.

Gradio – Interactive web interface.

Usage

Upload a video through the Gradio interface.

The system predicts the video class.

A short textual description of the video is generated.

Potential Applications

Action recognition in videos.

Automatic video summarization.

Multimedia content analysis and tagging
