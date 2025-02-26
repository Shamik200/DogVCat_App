# Cat vs Dog Classifier
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.95%2B-green.svg)](https://fastapi.tiangolo.com/)
[![Hugging Face](https://img.shields.io/badge/Hugging%20Face-Deployment-yellow.svg)](https://huggingface.co/)
[![Retrofit](https://img.shields.io/badge/Retrofit-Android%20Networking-orange.svg)](https://square.github.io/retrofit/)
![badge-Platform](https://img.shields.io/badge/Platform-Android%2C%20API%2C%20Deep%20Learning-brightgreen)

Cat vs Dog Classifier is a deep learning-based mobile application built with **CNN architecture** to classify images as either a cat or a dog. The backend is implemented using **FastAPI** and deployed on **Hugging Face Spaces**, while the Android app interacts with it using **Retrofit** for API requests.

## Key Features ✨
- **Deep Learning-based Image Classification** using a pre-trained CNN model.
- **FastAPI-powered Backend** for handling classification requests.
- **Hugging Face Spaces Deployment** for model execution and API hosting.
- **Android App with Retrofit** for seamless request-response handling.
- **User-friendly Interface** for uploading images and receiving predictions.

## Query Endpoint 📡
You can test the classification API online:
[**Query Endpoint**](https://shamik007-cvd.hf.space/) *(Upload an image to classify it as a cat or dog!)*

## Project Layout Structure
- **Backend:**
  - FastAPI-based REST API to process image classification requests.
  - Model deployed on **Hugging Face Spaces** for real-time inference.
- **Android App:**
  - Uses **Retrofit** to send images to the API and receive classification results.
  - Displays classification output in an intuitive UI.

## Backend Details 💻
### FastAPI Backend
- Handles image upload and processes it using a **CNN model**.
- Returns classification results ("Cat" or "Dog") with confidence scores.
- Deployed on **Hugging Face Spaces** for public access.

### API Reference
- **POST /predict** - Accepts an image file and returns classification results.
- **Query API Online:** [**Test Here**](https://shamik007-cvd.hf.space/)
- **Python Backend Repository:** [**GitHub Link**](https://github.com/Shamik200/CatVDog)

## Android Integration 📱
- **Retrofit** is used for making API requests from the Android app.
- The app captures user images and sends them to the backend for classification.
- Results are displayed with confidence scores and UI elements.

## Built With 🛠
- [FastAPI](https://fastapi.tiangolo.com/) - High-performance API framework.
- [Hugging Face Spaces](https://huggingface.co/) - Model deployment.
- [Retrofit](https://square.github.io/retrofit/) - Android networking.
- [CNN Model](https://www.tensorflow.org/) - Deep learning for classification.
- [Android Studio](https://developer.android.com/studio) - App development.

## Testing 🧪
- Unit tests for API request handling.
- Model accuracy evaluation with test datasets.
- UI/UX testing for Android app image classification results.

<h2> 📬 Connect With Me </h2>

<div>
  <a href="https://www.linkedin.com/in/shamik-munjani/">
    <img src="https://www.vectorlogo.zone/logos/linkedin/linkedin-icon.svg" width="30px" alt="LinkedIn">
  </a>
  <span style="margin: 5px;"></span>
  <a href="mailto:shamikmunjani@gmail.com">
    <img src="https://www.vectorlogo.zone/logos/gmail/gmail-icon.svg" width="30px" alt="Email">
  </a>
</div>
<br>

⭐️ From [Shamik](https://github.com/Shamik200)

