# SC_ML_4
# Hand Gesture Recognition Using CNN

This project develops a hand gesture recognition model using Convolutional Neural Networks (CNN). The model classifies hand images into 10 different gesture categories from the Leap Gesture Recognition dataset.

## Dataset

Dataset: [Hand Gesture Recognition Database](https://www.kaggle.com/datasets/gti-upm/leapgestrecog)

The dataset contains approximately 20,000 grayscale hand-gesture images. It includes 10 gesture classes performed by 10 different subjects.

## Project Workflow

1. Download the dataset from Kaggle in Google Colab.
2. Load grayscale hand images and their gesture labels.
3. Resize images to 64 × 64 pixels and normalize pixel values.
4. Split the dataset into training, validation, and test sets using different subjects.
5. Build and train a CNN model.
6. Evaluate the model using test accuracy.
7. Display predicted and actual gesture labels for sample test images.
8. Save the trained model as `hand_gesture_model.keras`.

## Technologies Used

- Python
- Google Colab
- TensorFlow and Keras
- NumPy
- Matplotlib
- KaggleHub

## Model Architecture

The CNN model uses:

- Convolutional layers to detect hand features
- Max-pooling layers to reduce image dimensions
- Dropout layers to reduce overfitting
- Dense layers for gesture classification
- Softmax output layer for 10 gesture classes

## Running the Project

1. Open the notebook in Google Colab.
2. Enable GPU from `Runtime → Change runtime type → T4 GPU`.
3. Generate a Kaggle API token from Kaggle Settings.
4. Run each code cell in order.
5. Paste the Kaggle token into the hidden input prompt when requested.
6. Wait for the dataset download and model training to finish.

## Output

The notebook displays:

- Number of images and gesture classes
- Training and validation accuracy
- Final test accuracy
- Sample images with actual and predicted gesture labels

Green labels indicate correct predictions, while red labels indicate incorrect predictions.

## Conclusion

This project demonstrates how CNNs can classify hand gestures from image data. The trained model can support gesture-based control systems and intuitive human-computer interaction applications.
