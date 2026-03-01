# Mental-Health-Companion-AI
Hybrid Transformer-Based Emotion Detection and Crisis-Aware Mental Health Chatbot

# Overview
This project presents a hybrid AI system designed to detect emotional states from text and provide empathetic, crisis-aware conversational support for students.
The system integrates transformer-based emotion classification, classical machine learning baseline comparison, crisis detection logic, and generative AI response modeling.
The primary focus of this project is on machine learning model development, evaluation, and hybrid system integration.

# System Architecture
The system consists of the following components:
1. Emotion Classification Model
   Fine-tuned RoBERTa transformer
   Multi-class classification (5 emotion categories)
2. Baseline Model
   TF-IDF vectorization
   Logistic Regression classifier
3. Crisis Detection Module
   Explicit high-risk keyword detection
   Emergency response override
4. Generative Response Module
   TinyLlama 1.1B Chat Model
   Emotion-conditioned prompting
5. Recommendation Engine
   Deterministic coping strategies based on predicted emotion

# Results
Model	                           Accuracy	                            F1 Score
TF-IDF + Logistic Regression	    ~66%	                                ~0.64
Fine-Tuned RoBERTa	              ~72%	                                ~0.72
The transformer-based model demonstrated improved contextual understanding and superior performance compared to the classical baseline.

# Technologies Used
Python
PyTorch
HuggingFace Transformers
HuggingFace Datasets
Scikit-learn
BitsAndBytes
Gradio
Google Colab

# How to Run
1. Install dependencies:
   pip install -r requirements.txt
2. Open mental_health_companion.ipynb and run all cells sequentially.

# Disclaimer
This project is intended for educational and research purposes only and is not a substitute for professional mental health services.
