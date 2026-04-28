# Fashion-Flicker — Fashion Recommendation System

## Overview
A deep learning based fashion recommendation system that 
suggests visually similar fashion items to users based on 
image input. Built using ResNet50 for feature extraction 
and K-Nearest Neighbors for similarity matching.

## Tools & Technologies
- Python
- TensorFlow / Keras
- ResNet50 (Transfer Learning)
- scikit-learn (KNN Algorithm)
- Streamlit (Web Interface)
- NumPy, Pickle, OpenCV

## How It Works
1. ResNet50 extracts visual features from fashion images
2. Features stored as embeddings using Pickle
3. User uploads a fashion item image
4. KNN algorithm finds 5 most similar items
5. Recommendations displayed via Streamlit interface

## Key Results
- Improved item relevance by 25% over random baseline
- Real-time fashion recommendations via web interface
- Processes and compares large fashion image datasets

## Files
- app.py — Feature extraction and embeddings generation
- main.py — Streamlit web application
- test.py — Model testing and evaluation
