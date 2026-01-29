# Leafine: Plant Disease Detection Application

**Leafine** is a cutting-edge mobile application designed to revolutionize agriculture by providing real-time, non-intrusive, and highly accurate plant health assessments. By leveraging **Artificial Intelligence**, **Deep Learning**, and **Computer Vision**, the application empowers farmers and researchers to detect diseases early, thereby reducing crop losses and promoting sustainable farming practices.

---

## 📑 Published Paper

This project was published in the *Journal of Emerging Technologies and Innovative Research (JETIR)*.

**Title:** Leafine: Plant Disease Detection Application 

**Link:** [Read the full paper on JETIR](https://www.jetir.org/view?paper=JETIR2310202) 

---

## 🚀 Features

**Real-time Detection:** Uses a smartphone camera to capture and analyze leaf images instantly.

**High Accuracy:** Built on the **VGG-16 CNN architecture** to differentiate between healthy and diseased plants.

**Early Identification:** Detects subtle visual signals like color variations, lesions, and irregularities before major damage occurs.

**User-Friendly Interface:** Results are presented in a simple, easy-to-understand UI for farmers and conservationists.

**Scalability:** Suitable for various agricultural, horticultural, and ecological applications.

---

## 🛠️ Tech Stack

### Software Requirements

**Language:** Python 3.9 

**Libraries:** TensorFlow, Keras 

**IDE:** PyCharm 

**Platform:** Android (Mobile Application) 


### Hardware Requirements
 
**RAM:** Minimum 8 GB 

**Device:** Android-supported smartphone with a camera 

---

## 📊 Methodology

The system follows a structured pipeline to ensure reliable disease classification:

1. 
**Data Collection:** A large dataset of healthy and diseased plant images is collected and manually annotated.


2. 
**Pre-processing:** Images are resized (e.g., 224x224 pixels) and pixel values are normalized.


3. 
**Model Design:** A pre-trained **VGG-16** model is used as the backbone, with custom classification layers added to the top.


4. 
**Training & Fine-Tuning:** The model is trained using Binary Cross-Entropy loss and optimized with Adam/SGD.


5. 
**Evaluation:** Performance is measured using accuracy, precision, recall, and F1-score, alongside a confusion matrix.

---

## 📈 Results

The model demonstrates impressive performance metrics, effectively differentiating healthy plants from those suffering from diseases like **Common Rust** (Corn) or **Black Rot** (Apple/Grape).
