
# Customize Word Embeddings for LLMs
This project demonstrates how to customize word embeddings for Large Language Models (LLMs) using the Natural Questions (NQ) dataset from Google. We compare the performance of default embeddings with customized ones by evaluating their accuracy and behavior through cosine similarity distributions.

# Overview
Use LoRA for Efficient Model Fine-Tuning:

Train T5 and BART-large-cnn models on the SAMSum dataset.
Save and load the trained models using Hugging Face.
Dataset:
'''
NQ Dataset: Contains 307,373 training, 7,830 development, and 7,842 test examples with questions and Wikipedia passages.
Fields: Queries, long answers, and short answers.
Performance Comparison
Default vs Customized Embeddings:
Plot cosine similarity distributions before and after customization.

Accuracy is measured by a threshold-based rule for similarity prediction.

Visualize overlap between similar and dissimilar pairs.

'''