# BRAIN-TUMOUR-DISEASE-DETECTION-USING-MACHINE-LEARNING-AND-DEEP-LEARNING-
A deep learning project utilizing Convolutional Neural Networks (CNN2D) and pre-trained VGG16 to accurately detect and classify 4 types of brain tumors from MRI scans.
# Brain Tumour Disease Detection Using Deep Learning (CNN & VGG16) 🧠💻

## About the Project
This repository contains a deep learning-based system designed to automatically detect and classify brain tumors from Magnetic Resonance Imaging (MRI) scans [2]. The project is built entirely within a **Jupyter Notebook** environment and focuses on utilizing advanced neural network architectures to provide an automated, non-invasive method for early disease detection [2, 3].

The model is trained to classify MRI images into 4 distinct categories based on a dataset sourced from Kaggle [2, 3]:
* `glioma_tumor`
* `meningioma_tumor`
* `pituitary_tumor`
* `no_tumor` (Healthy/Safe)

## Key Features & Methodology
* **Data Preprocessing:** Raw MRI images undergo several processing techniques before training, including resizing, pixel normalization, and shuffling [1]. The data is split into an 80% training set and a 20% testing set [1].
* **Custom CNN Architecture:** A Convolutional 2D Neural Network (CNN2D) was built from scratch to automatically extract spatial features directly from the MRI pixels [1]. This model achieved an outstanding accuracy of **98% to 99%** with minimal incorrect predictions [1, 4].
* **Transfer Learning (VGG16):** A pre-trained VGG16 model was also implemented to evaluate transfer learning performance, achieving a highly reliable accuracy of **83%** [1, 5].
* **Automated Prediction System:** Includes a predictive function that takes an input test MRI image path, processes the image, and accurately outputs the predicted brain tumor disease type directly on the screen [5, 6].

## Tech Stack
* **Language:** Python 3.8+
* **Deep Learning Frameworks:** TensorFlow 2.x, Keras [7]
* **Image Processing:** OpenCV, NumPy [8, 9]
* **Environment:** Jupyter Notebook [3]

## How to Use
1. Clone the repository and navigate to the project folder.
2. Download the dataset and ensure the folder structure matches the 4 class labels.
3. Open the Jupyter Notebook and run the cells sequentially to preprocess the data and train the CNN2D and VGG16 models.
4. Use the built-in predict function at the end of the notebook to test the model on new, unseen MRI images [5, 6].
