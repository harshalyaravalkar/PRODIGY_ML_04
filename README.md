# PRODIGY_ML_04

# Hand Gesture Recognition using Convolutional Neural Networks (CNN)

## Internship Details

- Company: Prodigy InfoTech
- Track Code: ML
- Task Number: 04
- Intern Name: Harshal Laxman Yaravalkar
- Domain: Machine Learning
- Duration: 1 Month
- Mentor: Prodigy InfoTech Team

---

## LinkedIn Post

As part of the internship requirements, I documented this task and the knowledge gained throughout the implementation process on LinkedIn.

🔗 LinkedIn Post:

[View LinkedIn Post](https://www.linkedin.com/posts/your-post-link-here)

---

## Task Objective

The objective of this task was to develop a Hand Gesture Recognition system using Deep Learning. The model was trained to identify different hand gestures from images and classify them into predefined categories.

Hand gesture recognition is an important application of computer vision and human-computer interaction. It is commonly used in gesture-controlled systems, gaming, robotics, virtual reality, and accessibility technologies.

This project demonstrates how Convolutional Neural Networks (CNNs) can automatically learn image features and accurately classify hand gestures.

---

## Dataset

Dataset Source:

https://www.kaggle.com/datasets/gti-upm/leapgestrecog

The LeapGestRecog dataset contains thousands of images representing different hand gestures performed by multiple individuals.

Gesture Classes Used:

- Palm
- L Shape
- Fist
- Fist Moved
- Thumb
- Index
- OK
- Palm Moved
- C Shape
- Down

Each folder contains gesture images from a different participant.

---

## Technologies Used

- Python
- TensorFlow
- Keras
- OpenCV
- NumPy
- Matplotlib
- Scikit-Learn
- Jupyter Notebook

---

## Project Workflow

### 1. Data Collection

The LeapGestRecog dataset was loaded and organized for training.

### 2. Image Preprocessing

The following preprocessing techniques were applied:

- Image loading using OpenCV
- Grayscale conversion
- Image resizing
- Pixel normalization
- Label encoding

These steps improved model efficiency and reduced computational requirements.

### 3. Dataset Preparation

Images and labels were converted into NumPy arrays and split into:

- Training Set
- Testing Set

This ensured proper evaluation on unseen data.

### 4. CNN Model Development

A Convolutional Neural Network (CNN) was developed using TensorFlow and Keras.

The architecture included:

- Convolutional Layers
- Max Pooling Layers
- Flatten Layer
- Dense Layers
- Dropout Layer
- Softmax Output Layer

The CNN automatically learned visual features from gesture images during training.

### 5. Model Training

The model was trained using multiple epochs and optimized using the Adam optimizer.

Categorical cross-entropy was used as the loss function, while accuracy was used as the evaluation metric.

### 6. Model Evaluation

The trained model was evaluated on the test dataset to measure its ability to correctly classify hand gestures.

### 7. Visualization

Training accuracy and validation accuracy graphs were generated to analyze model performance.

Sample gesture predictions were also displayed for visual verification.

---

## Results

The CNN model successfully learned gesture patterns and achieved high classification accuracy on the test dataset.

The project demonstrated the effectiveness of deep learning for image classification tasks and showed how convolutional neural networks can automatically extract meaningful visual features without manual feature engineering.

---

## Key Learnings

During this task, I gained practical experience in:

- Deep Learning
- Convolutional Neural Networks (CNN)
- Computer Vision
- Image Classification
- TensorFlow and Keras
- Data Preprocessing
- Model Training and Evaluation
- Gesture Recognition Systems

---

## Screenshots

### Model Training

<img width="1048" height="516" alt="Screenshot 2026-06-01 225527" src="https://github.com/user-attachments/assets/ee8be1bd-b58e-4b92-8960-6cc35c188891" />


### Accuracy Graph

<img width="672" height="244" alt="Screenshot 2026-06-01 225536" src="https://github.com/user-attachments/assets/245c1d68-baeb-4ea1-9733-467b4af817ee" />

<img width="813" height="525" alt="Screenshot 2026-06-01 225549" src="https://github.com/user-attachments/assets/0ae38d6f-a9ad-4a10-99b5-1462149fed97" />

### Gesture Predictions

<img width="832" height="605" alt="Screenshot 2026-06-01 225615" src="https://github.com/user-attachments/assets/deff81cf-1fab-4bd6-9a60-786952b5cce5" />

---

## Conclusion

This project provided valuable experience in applying deep learning techniques to computer vision problems. By developing a CNN-based gesture recognition model, I learned how neural networks process image data and automatically extract features for classification.

The project successfully demonstrated how deep learning can be used to recognize human gestures and highlighted the importance of image preprocessing, model architecture design, and performance evaluation in computer vision applications.

---

## How to Run

1. Clone the repository

```bash
git clone https://github.com/harshalyaravalkar/PRODIGY_ML_04.git
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Open Jupyter Notebook

```bash
jupyter notebook
```

4. Run all cells to preprocess images, train the CNN model, and generate gesture predictions.

---

## Requirements

```txt
tensorflow
opencv-python
numpy
matplotlib
scikit-learn
jupyter
```

---

#MachineLearning #DeepLearning #CNN #TensorFlow #ComputerVision #HandGestureRecognition #ImageClassification #Python #DataScience #ProdigyInfoTech #Internship
