# Brain-Tumour-Segementation
This is a deep learning-based web application for Segmenting Brain tumor and classifying brain tumors into four categories: glioma, meningioma, pituitary, or no tumor. It is trained on a labeled MRI image dataset and has Gradio interface.
# Brain Tumor Classification using CNN

This project uses a Convolutional Neural Network (CNN) built with TensorFlow and Keras to classify MRI brain scans into four categories:

- Glioma
- Meningioma
- Pituitary
- No Tumor

A simple web interface is created using [Gradio](https://gradio.app/) to allow easy image upload and prediction.

---

## 🔍 Demo

Upload an MRI scan and get an instant classification prediction via the Gradio interface.

---

## 🧰 Tech Stack

- Python
- TensorFlow & Keras
- OpenCV
- NumPy
- Scikit-learn
- Gradio

---

## 📁 Dataset

The dataset should be organized in the following format under the `Training` folder:
/Training
/glioma
/meningioma
/notumor
/pituitary

Each folder must contain respective images in `.jpg`, `.png`, or similar formats.

---

##  How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/brain-tumor-classifier.git
   cd brain-tumor-classifier
````

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Make sure your dataset path is correctly set in the script:

   ```python
   DATASET_PATH = '/your/path/to/Training'
   ```

4. Run the script:

   ```bash
   python app.py
   ```

---

## 🖼 Interface

The app will launch in your browser using Gradio. Upload an image and it will predict the tumor class.

---

##  Author

Created by **Bertil Jovita JP**
Contact: []
GitHub: []





