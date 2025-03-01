# MonkeyPox Detection App

## 📌 Project Overview
This project implements a **MonkeyPox Detection App** using Deep Learning models. The app is built with Streamlit to provide a user-friendly interface for uploading medical images and predicting whether the image contains MonkeyPox or not.

## 🚀 Features
- Image Upload via Web Interface
- Preprocessing of Medical Images
- Deep Learning Model Prediction
- Display of Original Image with Prediction Results

## 🛠️ Tech Stack
- Python
- TensorFlow
- Streamlit
- OpenCV
- NumPy

## 🔑 Installation

### Prerequisites
- Python 3.8+
- TensorFlow
- Streamlit
- OpenCV

### Steps
```bash
# Clone the repository
git clone https://github.com/your-username/MonkeyPox-Detection.git

# Navigate to the project directory
cd MonkeyPox-Detection

# Install dependencies
pip install -r requirements.txt

# Run the app
streamlit run app.py
```

## 📄 Usage
1. Upload an image of skin lesions through the web interface.
2. The model will classify the image as **Monkey Pox** or **Non Monkey Pox**.
3. The original image will be displayed along with the prediction result.

## ⚙️ Folder Structure
```
MonkeyPox-Detection/
│
├─ model/             # Model Training Notebooks
├─ app.py             # Streamlit App
├─ monkeypox_model.h5 # Trained model
└─ requirements.txt   # Dependencies
```

## 📌 Model Details
- **Base Model**: Convolutional Neural Network (CNN)
- **Input Image Size**: 256x256
- **Activation Function**: Sigmoid
- **Loss Function**: Binary Cross Entropy

## 🎯 Future Improvements
- Use Transfer Learning models like ResNet or EfficientNet
- Deploy the model using Docker
- Add Real-time Camera Detection

## 🤝 Contributing
Contributions are welcome! Please submit a pull request or open an issue.

## 📧 Contact
For questions or collaborations, reach out at **your-email@example.com**.

## ⭐ Acknowledgements
- TensorFlow Community
- Streamlit Community

dataset - https://www.kaggle.com/datasets/nafin59/monkeypox-skin-lesion-dataset
