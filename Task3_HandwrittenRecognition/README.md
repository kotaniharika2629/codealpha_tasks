
# Handwritten Character Recognition Using CNN

## CodeAlpha Machine Learning Internship — Task 3

### Project Overview

This project recognizes handwritten digits (0–9) using a Convolutional Neural Network (CNN).

The model is trained on the MNIST dataset to identify handwritten digits from grayscale images.

### Dataset

- **Name:** MNIST Handwritten Digits Dataset
- **Training Images:** 60,000
- **Testing Images:** 10,000
- **Image Size:** 28 × 28 pixels
- **Classes:** 10 (digits 0–9)
- **Source:** TensorFlow Keras Datasets

### Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

### CNN Architecture

The model uses the following layers:

1. Input Layer — 28 × 28 × 1
2. Conv2D — 32 filters, 3 × 3 kernel, ReLU
3. MaxPooling2D — 2 × 2
4. Conv2D — 64 filters, 3 × 3 kernel, ReLU
5. MaxPooling2D — 2 × 2
6. Flatten Layer
7. Dense Layer — 128 neurons, ReLU
8. Output Layer — 10 neurons, Softmax

**Total Trainable Parameters:** 225,034

### Data Preprocessing

1. Loaded the MNIST dataset.
2. Normalized pixel values from 0–255 to 0–1.
3. Reshaped images to (28, 28, 1).
4. Prepared training and testing datasets.

### Model Training

- **Optimizer:** Adam
- **Loss Function:** Sparse Categorical Crossentropy
- **Epochs:** 5
- **Batch Size:** 64
- **Validation Split:** 10%

### Model Performance

| Metric | Result |
|---|---|
| Test Accuracy | 99.22% |
| Test Loss | 0.0245 |
| Total Test Images | 10,000 |
| Correct Predictions | 9,922 |
| Incorrect Predictions | 78 |

### Results

The CNN achieved **99.22% test accuracy** on the MNIST handwritten digits dataset.

Out of 10,000 test images:

- 9,922 images were correctly classified.
- 78 images were incorrectly classified.

The results demonstrate the CNN's effectiveness in recognizing handwritten digits.

### Project Features

- Handwritten digit recognition
- CNN-based image classification
- Image preprocessing and normalization
- Training and validation accuracy visualization
- Training and validation loss visualization
- Confusion matrix generation
- Incorrect prediction analysis
- Model saving using Keras

### Visualizations

The project includes:

1. Sample handwritten digit images
2. Training vs. validation accuracy graph
3. Training vs. validation loss graph
4. Handwritten digit predictions
5. Confusion matrix
6. Incorrectly classified digit images

### How to Run

1. Download or open `Handwritten_Character_Recognition.ipynb` in Google Colab.
2. Install the required Python libraries.
3. Run all notebook cells sequentially.
4. Train the CNN model.
5. Evaluate the model on the test dataset.
6. View the predictions and evaluation graphs.

### Model Saving

The trained CNN model is saved using:

```python
model.save("handwritten_digit_cnn.keras")
```

The saved model can be loaded using TensorFlow Keras.

### Limitations

This project recognizes handwritten digits (0–9) only.

It does not currently recognize alphabetic characters, complete words, or sentences.

### Internship Details

- **Organization:** CodeAlpha
- **Domain:** Machine Learning
- **Batch:** November 2026
- **Task:** Task 3 — Handwritten Character Recognition
- **Status:** Completed
