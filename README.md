
# Custom TensorFlow Models and Training Loops

## Overview
This repository showcases various implementations of neural network architectures and custom training loops using TensorFlow and Keras. The code demonstrates techniques like multi-input models, sequential and functional API approaches, and custom gradient computation.

## Features
- Implementation of friend score prediction based on parameter similarity to ideal values.
- Comparison between Sequential and Functional API in TensorFlow.
- Multi-input neural network models using Keras Functional API.
- Custom training loops for fine-grained control over model optimization.

## Code Highlights
1. **Friend Score Prediction**  
   A model predicts scores based on how closely input parameters match an ideal set, using dense layers and scaled input features.

2. **Sequential and Functional API**  
   - Sequential API: Layer-by-layer model definition.
   - Functional API: Flexible model design for multi-input architectures.

3. **Custom Training Loops**  
   - Batch-wise gradient computation.
   - Training control for epochs and loss monitoring.

## Prerequisites
- Python 3.x
- TensorFlow 2.x
- NumPy
- Matplotlib
- Seaborn

Install required packages using:
```bash
pip install tensorflow numpy matplotlib seaborn
