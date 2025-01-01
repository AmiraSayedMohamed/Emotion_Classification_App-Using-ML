# Emotion Classification with Deep Learning 🤖💥
![Alt text](https://github.com/AmiraSayedMohamed/Emotion_Classification_App-Using-ML/blob/master/Imgtest.jpg)

Welcome to the **Emotion Classification Project**! 🎉

This project leverages deep learning to classify human facial expressions into 7 categories: **Angry, Disgust, Fear, Happy, Sad, Surprise, and Neutral**. With this model, you can identify emotions from facial images in real-time! 😁

---

## Features 🌟

- **Emotion Detection**: Detect emotions from facial images.
- **Real-Time Predictions**: Upload an image to get instant predictions.
- **Grayscale Images**: Model trained on grayscale images for efficiency.

---

## Technologies Used 🛠️

- **TensorFlow**: Powerful deep learning framework for building and training models.
- **Keras**: High-level neural networks API, built on top of TensorFlow.
- **Streamlit**: User-friendly web framework to visualize the model and interact with it.
- **OpenCV & Pillow**: Image processing libraries for handling uploaded images.
- **Python**: The backbone of the project, providing the logic and structure.

---

## How It Works ⚙️

1. **Data Collection**: The model is trained on the **FER-2013** dataset, which contains images of facial expressions labeled with their corresponding emotions.
2. **Preprocessing**: The images are resized to 48x48 pixels and converted to grayscale to standardize the input.
3. **Convolutional Neural Network (CNN)**: The model uses multiple convolutional layers to extract features from images, followed by max-pooling layers for dimensionality reduction.
4. **Prediction**: The model outputs a probability for each emotion, and the highest probability determines the predicted emotion.

---

## Get Started 🚀

To run the **Emotion Classification App** locally, follow these steps:

# here it's the link of the app:
https://emotionclassificationapp-using-ml-isipebgcurlrtdqfqksayg.streamlit.app/

### 1. Clone the Repository
```bash
git clone https://github.com/AmiraSayedMohamed/Emotion_Classification_App-Using-ML.git
cd Emotion_Classification_App-Using-ML



