# Facial Emotion Detection - Naan Mudhalvan Project

This project is developed as part of the **Naan Mudhalvan** skill development program under the subject **Deep Learning**. It focuses on detecting human emotions from facial images using a pre-trained Mini-XCEPTION model and OpenCV for face detection and visualization.

## Introduction

Facial emotion recognition is an important application of computer vision and deep learning. This project uses a pre-trained Mini-XCEPTION model trained on the FER-2013 dataset to classify facial expressions into seven categories:

- Angry  
- Disgust  
- Fear  
- Happy  
- Sad  
- Surprise  
- Neutral  

The system detects faces in an uploaded image and annotates them with the corresponding predicted emotion.

## Project Structure

- `emotiondetection.ipynb` – Jupyter Notebook with code for loading the model, detecting faces, predicting emotions, and visualizing results.
- `emotion_model.h5` – Pre-trained Mini-XCEPTION emotion recognition model.
- `README.md` – Project documentation.

## Technologies Used

- Python  
- Google Colab  
- Keras & TensorFlow (Deep Learning)  
- OpenCV (Image Processing & Face Detection)  
- NumPy (Data Handling)  

## How to Run

1. Open the notebook in **Google Colab**.
         -[Click here to open in Colab](https://colab.research.google.com/github/Kokisha2004/Emotiondetection/blob/main/emotiondetection.ipynb)
3. Run all cells to install dependencies and load the model.  
4. Upload an image with a face.  
5. The model will detect the face and display the predicted emotion on the image.

## Future Enhancements

- Integrate a live webcam-based emotion detection feature.  
- Improve performance by fine-tuning the model on custom datasets.  
- Add a Gradio or Streamlit interface for easier access and real-time prediction.

## License

This project is developed for educational purposes under the **Naan Mudhalvan** initiative.
