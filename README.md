# Voice Command Recognition - Kaggle Challenge

This repository contains the solution for the Kaggle challenge "TVD-2024 - Voice Command Recognition." In this project, different neural network architectures are implemented and compared for classifying voice commands from audio recordings.

## Repository Content
- **Main Notebook**: Implementation of models and result analysis.
- **Data Preprocessing**: Transformations applied to input data.
- **Model Definitions**: Baseline and advanced models used for classification.
- **Results & Analysis**: Model performance evaluation and conclusions.

## Implemented Models
Several architectures have been evaluated for the voice command classification task:
- **Baseline Model**: Simple convolutional neural network.
- **Recurrent Neural Networks (RNN, GRU, LSTM)**: Unidirectional and bidirectional models.
- **Deep Convolutional Networks (CNNs)**: Advanced models with regularization.
- **Transformers**: Assessment of the feasibility of this architecture for the task.
- **Combination of RNN and CNN**: Hybrid models to leverage the strengths of both architectures.

## Data Preprocessing
Data preprocessing included:
- Normalization and transformation of audio signals.
- Generation of linear spectrograms, MEL spectrograms, and MFCCs.
- Evaluation of different configurations to enhance data representation.

## Results
Deep convolutional networks achieved the best performance in the task, with a validation accuracy close to **96%**. Limitations were detected in the use of Transformers due to their higher computational demand and the need for more detailed optimization.

## Conclusion
Voice command recognition benefits from well-designed convolutional models and proper data preprocessing. Future improvements can focus on data augmentation and the optimization of hybrid architectures.

## Requirements
- Python 3.x
- TensorFlow / Keras
- Audio processing libraries (Librosa, NumPy, etc.)

## Usage
1. Clone the repository:
   ```bash
   git clone <repository URL>
   ```
2. Install dependencies:

3. Run the notebook in a Jupyter or Colab environment.

## Challenge Link
[Kaggle TVD-2024 - Voice Command Recognition](https://www.kaggle.com/competitions/tvd-2024-reconocimiento-de-comandos-de-voz/overview)

---
Authors: Zhihao Chen, Zhiqian Zhou  
Date: December 31, 2024

