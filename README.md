# Siamese Network for Face Recognition

Face verification system using a Siamese Neural Network trained on the Olivetti Faces dataset.

## Results

| Metric | Score |
|---|---|
| Train accuracy | 93.0% |
| Test accuracy | 88.75% |
| Epochs | 150 |
| Optimizer | RMSprop |

## Why Siamese?

A standard CNN classifier requires full retraining when adding a new person.
A Siamese network learns a similarity function instead — it compares two images
directly, so new identities can be added without retraining.

## Dataset

Olivetti Faces — 400 grayscale images, 40 subjects, 10 images each.
Images resized to 64x64 pixels.
Pairs generated: positive (same subject) and negative (different subjects).

## Context

Academic project — Master's in Intelligent Information Systems (UMMTO, 2024).

## Setup

pip install -r requirements.txt

Open siamese_face_recognition.ipynb in Jupyter or Google Colab.

## License

MIT