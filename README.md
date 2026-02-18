Sentiment Classification using Custom Transformer (From Scratch)
Overview

This project implements a 5-class sentiment classification model using a transformer encoder built from scratch in PyTorch.

The objective was to understand and implement attention-based architectures without relying on pretrained models.

Dataset

Total Train samples: ~4,000
Test Samples: 1500
Classes: 5 sentiment categories
Random baseline accuracy: 20%

Model

Custom Transformer encoder
Token embeddings + positional encoding
Multi-head self-attention
Feed-forward layers
Final linear classification head
Loss: CrossEntropyLoss
Optimizer: Adam

Results

Train Accuracy: 45.47%
Test Accuracy: 36.26%
The model performs above the random baseline (20%) but is limited by dataset size and quality.

Next Steps
Use Pytorch's inbuilt encoder.
Compare scratch vs inbuilt performance
Add deployment via FastAPI
