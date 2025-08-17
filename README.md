Vision Transformer (ViT) Replication

This repository contains my replication of the Vision Transformer (ViT) model, based on the paper “An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale” by Dosovitskiy et al. The project aims to explore how transformer architectures, originally designed for NLP, can be applied to image classification tasks with competitive performance.

Overview

The Vision Transformer (ViT) splits an input image into fixed-size patches (e.g., 16x16 pixels), flattens them, and projects them into a sequence of embeddings, analogous to word embeddings in NLP. These embeddings are then processed through a standard transformer encoder to learn contextual relationships between patches. Finally, a classification head predicts the image class.

Key features of this replication:

Patch Embedding: Converts images into a sequence of patch embeddings.

Transformer Encoder: Multi-head self-attention layers capture spatial dependencies across patches.

Classification Head: Uses the [CLS] token representation for final image classification.

Training & Evaluation: Implemented training loop and evaluation on standard datasets to validate performance.

This project is intended for educational purposes and demonstrates how transformer-based architectures can be adapted to vision tasks.
