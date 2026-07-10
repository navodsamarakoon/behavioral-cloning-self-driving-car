# 🚗 End-to-End Self-Driving Car using Behavioral Cloning

An end-to-end autonomous driving system built using **Deep Learning** and the **NVIDIA Behavioral Cloning Convolutional Neural Network (CNN)**. The model learns to predict steering angles directly from front-facing camera images and drives autonomously in the **Udacity Self-Driving Car Simulator**.

---

## 🎥 Demo

The project demo video is available in this repository:

📹 **demo.mp4**

Download or open `demo.mp4` from the repository to watch the autonomous driving demonstration.

---

## 📌 Project Overview

This project demonstrates an **end-to-end self-driving car system** using **behavioral cloning**. Instead of manually programming driving rules, a CNN learns steering behavior directly from human driving data.

The trained model predicts steering angles from camera images in real time and controls the vehicle inside the Udacity simulator.

---

## ✨ Features

- End-to-End Behavioral Cloning
- NVIDIA CNN Architecture
- Image preprocessing pipeline
- Data augmentation
- Real-time autonomous driving
- Steering angle prediction
- TensorFlow/Keras implementation
- Udacity Self-Driving Car Simulator integration

---

## 🧠 Model Architecture

This project is based on the NVIDIA End-to-End Learning architecture presented in:

> **End to End Learning for Self-Driving Cars**  
> NVIDIA Research (2016)

The CNN consists of multiple convolutional layers followed by fully connected layers to directly predict steering angles from input images.

---

## 📊 Dataset

The model was trained using a **publicly available behavioral cloning dataset** containing:

- **50,000+ driving images**
- Center camera images
- Left camera images
- Right camera images
- Steering angle labels
- Throttle and speed information

Dataset includes a variety of:

- Straight roads
- Left turns
- Right turns
- Recovery driving
- Different steering angles

---

## 🛠 Technologies Used

- Python
- TensorFlow
- Keras
- OpenCV
- NumPy
- Pandas
- Matplotlib
- Udacity Self-Driving Car Simulator

---

## 📂 Project Structure

```
behavioral-cloning-self-driving-car/
│
├── notebooks/
│   └── 1-self-driving-car.ipynb
│
├── data/
│   ├── IMG/
│   └── driving_log.csv
│
├── drive.py
├── utils.py
├── model.h5
├── requirements.txt
├── NVIDIA Research Paper.pdf
├── demo.mp4
└── README.md
```

---

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/navodsamarakoon/behavioral-cloning-self-driving-car.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run autonomous driving

```bash
python drive.py model.h5
```

Open the Udacity Self-Driving Car Simulator and select **Autonomous Mode**.

---

## 📈 Results

- Successfully predicts steering angles
- Drives autonomously inside the Udacity simulator
- Handles straight roads and curves smoothly
- Demonstrates real-time CNN inference

---

## 📖 Reference

NVIDIA Research

**End to End Learning for Self-Driving Cars**

https://developer.nvidia.com/blog/deep-learning-self-driving-cars/

---

## 🙏 Acknowledgements

- NVIDIA Research
- Udacity Self-Driving Car Simulator
- TensorFlow
- Keras
- OpenCV

---

## 👨‍💻 Author

**Navod Dulsara**

GitHub:
https://github.com/navodsamarakoon

LinkedIn:
https://www.linkedin.com/in/navodsamarakoon
