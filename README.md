# 🧑 Face Recognition Using Deep Learning

A deep learning-based face recognition system developed using **TensorFlow/Keras** and the **Yale Faces Dataset**. The project detects faces, preprocesses facial images, trains a Convolutional Neural Network (CNN), and recognises individuals from unseen images.

---

## 📖 Overview

Face recognition is one of the most widely used computer vision applications, with use cases ranging from security systems to biometric authentication.

This project demonstrates an end-to-end face recognition pipeline using the Yale Faces Dataset, covering everything from data preprocessing to model evaluation and prediction.

---

## 🚀 Features

- Face detection using **MTCNN**
- Image preprocessing and normalisation
- CNN model built using TensorFlow/Keras
- Model training and validation
- Accuracy and loss visualisation
- Classification report
- Single image prediction

---

## 🛠 Technologies Used

- Python
- TensorFlow / Keras
- OpenCV
- MTCNN
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

---

## 📂 Dataset

The project uses the **Yale Faces Dataset**.

After extracting the dataset, the folder structure should be:

```text
yalefaces/
├── train/
└── test/
```

The dataset README inside the `data/` folder contains additional setup instructions.

---

## 📁 Repository Structure

```text
Face-Recognition/
│
├── main.ipynb
├── data/
│   ├── archive.zip
│   └── README.md


```

---

## ⚙️ Workflow

1. Load the Yale Faces dataset
2. Detect faces using MTCNN
3. Preprocess and resize images
4. Create training and validation datasets
5. Train a Convolutional Neural Network
6. Evaluate model performance
7. Predict identities from unseen images

---

## 📊 Results

The model is evaluated using:

- Training Accuracy
- Validation Accuracy
- Training Loss
- Validation Loss
- Classification Report
- Confusion Matrix

---

## 📸 Project Screenshots

### Sample Face Detection

<img width="352" height="275" alt="image" src="https://github.com/user-attachments/assets/c5d79fc6-2938-4e8e-8292-33a9a9b9a3af" />


---

### Training Accuracy

<img width="371" height="283" alt="image" src="https://github.com/user-attachments/assets/63c044fe-7e46-44ae-a3be-699c056cc921" />


---

### Validation Loss

<img width="357" height="274" alt="image" src="https://github.com/user-attachments/assets/c346548b-bc70-4c0b-8532-34dc99410c8c" />


---

### Model Prediction

<img width="480" height="44" alt="image" src="https://github.com/user-attachments/assets/0be84beb-9c60-4908-a8d6-987471bebec3" />


---

## ▶ Running the Project

Clone the repository

```bash
git clone https://github.com/NitishW27/Face-Recognition.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Open the notebook

```bash
jupyter notebook main.ipynb
```

Run all cells sequentially.

---

## 💡 Future Improvements

- Improve recognition accuracy using transfer learning
- Compare CNN performance with FaceNet and VGGFace
- Deploy as a web application using Streamlit
- Add webcam-based real-time face recognition
- Support larger face datasets

---

## 👨‍💻 Author

**Nitish Wadpally**

Master of Data Science & Decisions  
UNSW Sydney

- GitHub: https://github.com/NitishW27

---

## 📄 License

This project is licensed under the MIT License.
