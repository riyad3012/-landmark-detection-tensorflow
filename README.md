# Landmark Detection using TensorFlow

An image classification project that identifies famous landmarks using deep learning and transfer learning with MobileNetV2.

## Project Overview

This project implements a landmark recognition system capable of classifying images into eight different landmark categories using TensorFlow and Keras.

The model uses MobileNetV2 as a pretrained feature extractor and applies transfer learning and fine-tuning to improve classification performance.

## Landmark Categories

The model classifies images into the following eight categories:

1. Taj Mahal
2. Eiffel Tower
3. Statue of Liberty
4. Big Ben
5. Sydney Opera House
6. Colosseum
7. Burj Khalifa
8. Gateway of India

## Technologies Used

- Python
- TensorFlow
- Keras
- MobileNetV2
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Dataset

- 400 landmark images downloaded from Wikimedia Commons.
- 320 training images.
- 80 validation images.
- 8 landmark categories.

## Model Architecture

- Pretrained MobileNetV2 architecture.
- Transfer learning.
- Model fine-tuning.
- Image classification using TensorFlow/Keras.

## Results

| Metric | Accuracy |
|---|---:|
| Initial validation accuracy | 80% |
| Fine-tuned validation accuracy | 78.75% |

The notebook also includes a confusion matrix and classification report for model evaluation.

## Features

- Landmark image classification.
- Prediction with confidence scores.
- Transfer learning using MobileNetV2.
- Model training and fine-tuning.
- Performance evaluation and visualization.

## How to Run

1. Clone this repository.

```bash
git clone YOUR_REPOSITORY_URL
```

2. Open the notebook using Jupyter Notebook or Google Colab.

3. Run the notebook cells sequentially.

4. Allow the notebook to download the dataset and train the model.

5. Test the model using landmark images.

## Project Structure

```text
landmark-detection-tensorflow/
│
├── landmark-detection-tensorflow.ipynb
└── README.md
```

## Future Improvements

- Expand the landmark dataset.
- Improve model accuracy.
- Build a web application for real-time landmark recognition.
- Deploy the trained model for public use.

## Author

Riya D Souza

BE – Artificial Intelligence and Machine Learning
