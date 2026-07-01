# Multimodal Emotion Detection

A Flask web app that recognizes human emotion across **three modalities** — speech (audio),
video (facial expressions), and text — and presents the results in an interactive UI.

## Modalities

- **Speech emotion recognition** — audio features classified with a trained model.
- **Video / facial emotion recognition** — face detection (dlib / OpenCV) + expression
  classification.
- **Text emotion recognition** — NLP pipeline (NLTK) over uploaded documents (PDF parsing
  via Tika) with preprocessing and classification.

## Stack

Python · Flask · TensorFlow / Keras · OpenCV · dlib · NLTK · gensim · scikit-learn ·
Altair (visualization).

## Run

```bash
pip install -r requirements.txt
python main.py
```

Open the local URL and choose a modality (audio / video / text) to analyze.

## Status

Portfolio project demonstrating an end-to-end multimodal ML pipeline behind a web UI.
