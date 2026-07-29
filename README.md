# 🐶 Pet Breed Classification using TensorFlow

## 📌 Project Overview

This project classifies cat and dog breeds using **Transfer Learning** with the **ResNet50** deep learning model. Images from the Oxford-IIIT Pet Dataset are preprocessed and used to train a classifier capable of predicting the breed of a pet from an input image.

---

## 📂 Dataset

- **Dataset:** Oxford-IIIT Pet Dataset
- **Number of Classes:** 37 pet breeds
- **Image Size:** 224 × 224 pixels

---

## 🛠️ Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

---

## 🚀 Project Workflow

1. Import libraries
2. Load the Oxford-IIIT Pet Dataset
3. Extract breed labels
4. Encode labels
5. Load and preprocess images
6. Split data into training, validation, and test sets
7. Build a ResNet50 transfer learning model
8. Train the model
9. Evaluate model performance
10. Predict pet breeds on unseen images

---

## 📊 Model Performance

- EarlyStopping was used to prevent overfitting.
- Training stopped automatically after the best validation performance was reached.
- Training Accuracy: ~88%
- Validation Accuracy: ~86%

---

## 📈 Results

The notebook includes:

- Training Accuracy graph
- Validation Accuracy graph
- Training Loss graph
- Validation Loss graph
- Test evaluation
- Prediction on random test images

---

## 📷 Sample Prediction

> Add a screenshot of your prediction output here after uploading the project.

---

## 📁 Project Structure

```text
Pet_Breed_Classification/
│
├── images/
├── Pet_Breed_Classification.ipynb
├── README.md
└── pet_breed_classifier.keras
```

---

## 👩‍💻 Author

**Anwesha Barik**