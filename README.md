# ToxicCommentClassifier
This project implements a toxic comment classifier using TensorFlow and Gradio. The model is trained on a dataset of comments, aiming to classify comments into various toxicity categories. The Toxic Comment Classifier utilizes a Bidirectional LSTM-based neural network architecture.

## Key Features

- **Text Preprocessing:** Tokenization and vectorization of comments for model input.
- **Model Architecture:** Bidirectional LSTM layers with fully connected layers for feature extraction.
- **Training and Evaluation:** Training the model on a dataset, evaluating precision, recall, and accuracy.
- **Gradio Interface:** Integration with Gradio for a user-friendly interface to classify toxicity in real-time.


## Repository Structure
- toxic_comment_classifier.py: Main script containing the model training, evaluation, and Gradio interface.
- requirements.txt: List of required Python packages.
- ToxicCommentClassifier.h5: Pre-trained model file.
- train.csv: Dataset file (not included in this repository).


## Download Dataset:
https://www.kaggle.com/competitions/jigsaw-toxic-comment-classification-challenge
