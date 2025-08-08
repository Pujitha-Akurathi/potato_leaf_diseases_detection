# Potato Leaf Disease Detection

A machine learning-powered web app that identifies and classifies potato leaf diseases using computer vision and deep learning, deployed using Streamlit.

##  Live Demo
You can try the app live here: [Streamlit App](https://potatoleafdiseasesdetection-d9ugwtzekffawhnkurqkfj.streamlit.app/)

## Features
- Upload images of potato leaves to automatically detect disease types.
- Supports multiple disease classes with high accuracy.
- User-friendly interface for hobbyist farmers and agricultural professionals.

## Technologies Used
- **Python**, **TensorFlow**, and **OpenCV** for model training and image processing.
- **Streamlit** for building and deploying the interactive web interface.
- **app.py** handles image input, model inference, and UI rendering.
- **Train_potatoleaf_disease.ipynb** includes data processing, model training, and evaluation workflows.
- **requirements.txt** specifies project dependencies for reproducibility.

## Project Structure
```bash
├── app.py
├── Train_potatoleaf_disease.ipynb
├── Diseases.jpg
├── requirements.txt
└── README.md
```

## Usage / Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/Pujitha-Akurathi/potato_leaf_diseases_detection.git

2. Install dependencies:
   ```bash
   pip install -r requirements.txt

3. Run the app:
   ```bash
   streamlit run app.py
   ```
4. Interact with the UI to upload leaf images and receive disease predictions.

## Results
A working interface where users can upload an image and get real-time predictions of leaf diseases, complete with visuals and accuracy scores.

## Acknowledgments
Based on standard plant disease datasets and classification models.

Powered by the Streamlit platform for rapid prototyping and deployment.
