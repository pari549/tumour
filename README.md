Stomach Tumour Detection using Image Recognition:

This project implements an AI-based image classification system to detect stomach tumours using medical images. It uses deep learning techniques to classify images into tumour and non-tumour categories.
Overview

The goal of this project is to build a simple and effective image classification model for medical diagnosis support. The implementation is contained in a single Python file for clarity and ease of understanding.


Dataset:

- This project is based on the Kvasir Dataset, a publicly available dataset for gastrointestinal image analysis.
- The dataset is not included in this repository due to size constraints.
- Users are required to download the dataset separately and provide the appropriate path in the code.

---

Tech Stack

- Python
- NumPy
- TensorFlow / Keras (or PyTorch, depending on implementation)
- OpenCV
- Matplotlib

---

Features

- Image preprocessing and normalization
- Binary classification (tumour vs non-tumour)
- Model training and evaluation
- Simple and easy-to-understand implementation in a single script

---

Project Structure

stomach-tumour-detection/

│
├── one_cancer(1).py
├── README.md

---

How to Run

1. Clone the repository:

git clone https://github.com/pari549/tumour.git

2. Navigate to the project directory:

cd tumour

3. Install dependencies:

pip install -r requirements.txt

4. Download the Kvasir dataset and update the dataset path in the code

5. Run the script:

python one_cancer(1).py

---

Results

- The model is capable of distinguishing between tumour and non-tumour images
- Performance depends on dataset size and training configuration

---

Future Improvements

- Improve model accuracy with larger datasets
- Use advanced architectures such as ResNet or EfficientNet
- Add a graphical interface for predictions
- Deploy as a web application

---

License

This project is intended for educational and research purposes.

---

Author

Pari Bardia
AI and Software Enthusiast
