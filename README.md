🧬 Skin Cancer Detection & Dermatologist Finder

A deep learning-powered web application that detects 9 common skin diseases from uploaded images and suggests nearby dermatologists based on your location. Built using TensorFlow, Streamlit, and Google Places API.

🌟 Features
🔬 Disease Prediction: Detects 9 types of skin conditions:
Actinic Keratosis
Basal Cell Carcinoma
Dermatofibroma
Melanoma
Nevus
Pigmented Benign Keratosis
Seborrheic Keratosis
Squamous Cell Carcinoma
Vascular Lesion
📍 Find Dermatologists Nearby: Automatically recommends skin specialists near your location using Google Places API.
🧠 Deep Learning Model: TensorFlow model trained on dermatology datasets to classify skin diseases based on uploaded images.
🖼️ Educational Visualizations: Image gallery and information on each disease type to raise awareness.
🎥 Interactive UI: Engaging Lottie animations for a friendly experience.


🚀 Getting Started
🔧 Installation
Clone the repository:
git clone https://github.com/yourusername/skin-cancer-detection.git
cd skin-cancer-detection
Install dependencies:
pip install -r requirements.txt
Add your Google Places API Key:
Create a .streamlit/secrets.toml file and add your API key:
api_key = "YOUR_GOOGLE_PLACES_API_KEY"
Run the app:
streamlit run main.py
🗂 Project Structure
bash
Copy
Edit
skin-cancer-detection/
│
├── .streamlit/
│   └── secrets.toml        (# Google Maps API key)
├── images/                 (# Sample disease images)
├── model/
│   └── model.h5            (# Trained TensorFlow model)
├── main.py                 (# Entry-point for the application)
├── diagnosis.py            (# Skin disease prediction from image)
├── doctor_locator.py       (# Google Maps-based dermatologist finder)
├── learn_more.py           (# Disease details and image gallery)
├── requirements.txt
└── README.md


🧠 Tech Stack
Streamlit – Frontend
TensorFlow – Image classification model
Google Maps API – Dermatologist location services
Pillow – Image preprocessing
Geopy – City-to-coordinates conversion
Lottie – Animations for better UX

⚠️ Disclaimer
This tool provides AI-based predictions and does not substitute professional medical advice. Please consult a certified dermatologist for diagnosis and treatment.

🤝 Contributors
👨‍💻 Your Name – K.Prapulla Kumar

📜 License
This project is open-source under the MIT License.



