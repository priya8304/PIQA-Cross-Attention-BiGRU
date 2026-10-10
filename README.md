# Physical Commonsense Reasoning Using Cross-Attentive BiGRU

## Project Overview

This project focuses on **Physical Commonsense Reasoning** using the Physical Interaction Question Answering (PIQA) dataset. The objective is to develop a neural network capable of selecting the most physically plausible solution from two candidate answers for a given real-world situation.

Developed as part of the **CITS4012 Natural Language Processing** unit at the University of Western Australia, this project explores how recurrent neural networks and attention mechanisms can be combined to understand relationships between everyday goals and possible actions.

## Model Architecture

The proposed model was implemented from scratch using **Python and PyTorch** and consists of:

- Trainable word embeddings
- Shared Bidirectional Gated Recurrent Unit (BiGRU) encoder
- Goal–solution cross-attention mechanism
- Interaction-based feature fusion
- Masked mean pooling
- Feed-forward candidate compatibility scorer

The model independently evaluates two candidate solutions and predicts the more physically plausible answer based on their compatibility with the given goal.

## My Contributions

**Role: Model Architecture Lead**

As part of a three-member team, my primary responsibilities included:

- Designing and implementing the custom BiGRU neural network architecture.
- Developing the goal–solution cross-attention mechanism.
- Implementing interaction fusion, masked pooling, and candidate scoring.
- Testing neural network components and verifying tensor dimensions.
- Preparing the model architecture diagram and documenting the methodology, mathematical equations, and design decisions.

Other team members contributed to dataset preparation, model training, baseline comparisons, evaluation, and ablation studies.

## Technologies and Skills

**Python | PyTorch | Deep Learning | Natural Language Processing | Bidirectional GRU | Attention Mechanisms | Neural Networks | Google Colab**

## Dataset

Physical Interaction Question Answering (PIQA)

https://huggingface.co/datasets/ybisk/piqa

## Project Type

Academic Group Project | University of Western Australia | 2026
