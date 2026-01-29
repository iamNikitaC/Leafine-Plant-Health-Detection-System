# Leafine: Plant Disease Detection Application

**Leafine** is a cutting-edge mobile application designed to provide real-time, non-intrusive, and highly accurate plant health assessments. Developed to address the rising challenges of climate change and pest infestations, it leverages **Deep Learning** and **Convolutional Neural Networks (CNNs)** to help farmers and researchers make informed crop management decisions.

---

## 📑 Published Paper

This project was documented and published in the *Journal of Emerging Technologies and Innovative Research (JETIR)*.

* **Title:** Leafine: Plant Disease Detection Application 

* **Paper Link:** [View on JETIR](https://www.jetir.org/view?paper=JETIR2310202) 

---

## 🚀 Key Features

* **Real-time Detection:** Analyzes leaf images via a smartphone camera to provide immediate disease status.

* **Visual Signal Recognition:** Quickly detects subtle signals such as lesions, color variations, and irregularities.

* **User-Friendly Interface:** Presents complex AI analysis in an easy-to-understand UI for farmers and conservationists.

* **Scalability:** Flexible enough for diverse agricultural, horticultural, and ecological applications.

* **Early Intervention:** Empowers stakeholders to identify diseases early, reducing crop losses that can reach up to 50%.

---

## 💡 Motivation & Problem Statement

In India, agriculture employs more than 60% of the population, yet crop diseases lead to devastating yield losses.

* **The Problem:** Many farmers lack the tools or technical knowledge to identify a wide range of infections, often noticing damage only when it is too late.

* **The Goal:** To bridge this gap by providing an automated, computer-aided technique for disease identification and classification through simple leaf photos.

---

## 🛠️ Technical Architecture

The system is built on the **VGG-16** CNN architecture, chosen for its effectiveness in image classification tasks.

### Implementation Workflow

1. **Data Collection:** Gathering a large dataset of healthy and diseased plant images.

2. **Pre-processing:** Resizing images to **224x224** pixels and normalizing pixel values to a [0, 1] scale.

3. **Model Design:** Using a pre-trained VGG-16 base, removing the top layer, and adding custom layers for binary classification.

4. **Training:** Utilizing **Binary Cross-Entropy** as the loss function and the **Adam/SGD** optimizer.

5. **Deployment:** Integrating the trained model into an Android mobile application for live detection.


### Tech Stack

**Software Requirements**

* **Language:** Python 3.9 

* **Deep Learning Framework:** TensorFlow 

* **Neural Networks Library:** Keras 

* **IDE:** PyCharm
  

**Hardware Requirements**

* **Mobile Operating System:** Android 

* **Memory:** Minimum 8 GB RAM 

---

## 📊 Performance & Results

The model demonstrated high metrics across accuracy, precision, recall, and F1-score. Successful detections observed in testing include:

* **Corn (Maize):** Common Rust 

* **Grape Plant:** Black Rot 

* **Apple Plant:** Black Rot 

* **Healthy Status:** Correct identification of healthy grape leaves 

---

## 👥 Authors & Acknowledgments

**Department:** Computer Engineering, SIES Graduate School of Technology 

**Acknowledgment:** We extend our sincere gratitude to our coordinator, Director, HOD, and faculty members for their continuous support and resources.
