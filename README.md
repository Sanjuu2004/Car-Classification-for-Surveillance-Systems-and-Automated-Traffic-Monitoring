# Car-Classification-for-Surveillance-Systems-and-Automated-Traffic-Monitoring

## 📖 Project Overview

This project leverages **Convolutional Neural Networks (CNN)** and deep learning techniques to automatically classify vehicles into 7 categories based on image data. The system is designed for **surveillance systems and automated traffic monitoring**, aiming to enhance vehicle identification accuracy and real-time traffic management.

Achieving an accuracy of **over 90%** in classification tasks, the model demonstrates robust performance across diverse vehicle types and traffic environments.

---

## 🎯 Aim and Objectives

### Aim
To utilize Convolutional Neural Networks and machine learning to achieve **precise detection and classification of 7 car types**, enhancing surveillance system efficiency with a target accuracy of 98%.

### Objectives
- Develop a CNN-based classification model
- Identify and classify 7 car types from images
- Integrate the model into a system for **real-time surveillance and traffic monitoring**
- Achieve and validate a high classification accuracy

---

## 🚘 Car Categories
The system classifies the following 7 car types:
1. Audi
2. Hyundai Creta
3. Mahindra Scorpio
4. Rolls Royce
5. Maruti Suzuki Swift
6. Tata Safari
7. Toyota Innova

---

## 🗄️ Dataset

We utilized the **Cars Image Dataset by Kshitij Kumar** from Kaggle:
- ✅ 4,165 images
- ✅ 7 classes
- ✅ Organized into train/test folders with labeled subfolders

📎 Dataset link: [https://www.kaggle.com/datasets/kshitij192/cars-image-dataset](https://www.kaggle.com/datasets/kshitij192/cars-image-dataset)

---

## 🏗️ System Architecture

The system follows this pipeline:

1. **Data Collection**: Aggregated car images from Kaggle dataset
2. **Data Preprocessing**: Resizing, normalization, augmentation
3. **Model Building**: CNN architecture with:
   - 2 convolutional layers (32 filters, ReLU activation)
   - MaxPooling layers
   - Fully connected layers (96, 32 units)
   - Dropout layer (0.4)
   - Output Dense layer (7 units, softmax)
4. **Training & Validation**: Trained for 50 epochs
5. **Testing & Evaluation**: Accuracy, precision, recall, F1-score computed
6. **Deployment**: Ready for integration with surveillance/traffic systems

### 🧠 CNN Components
- Convolutional layers
- Pooling layers
- Fully connected layers
- Dropout layer
- ReLU activation

---

## 📊 Performance & Results

- ✅ **Accuracy achieved**: 90%+ on validation/test data
- ✅ Effective **real-time classification**
- ✅ Robust to different surveillance environments
- ✅ Shows **generalizability** to unseen traffic data

Example outcomes:
- Correct classification (100% confidence) for Mahindra Scorpio
- Misclassification cases analyzed and documented for improvement

---

## 📈 Visual Analysis

Plots include:
- Training vs Validation Accuracy
- Training vs Validation Loss
- Misclassification examples

👉 Highlights potential model overfitting after certain epochs  
👉 Suggests need for **dataset expansion and augmentation** for further improvement

---

## 🏆 Contributions & Applications

✅ Enables:
- Automated vehicle identification
- Real-time surveillance integration
- Traffic monitoring & pattern analysis
- Improved urban security and law enforcement support

Ideal for:
- Intelligent Transportation Systems (ITS)
- Toll booths
- Public security systems
- Smart city traffic management

---

## 📝 How to Use

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/car-classification-surveillance.git
   cd car-classification-surveillance

Future Improvements
Expand dataset with more diverse car types and images

Improve model’s ability to distinguish subtle design features

Integrate additional sensor data (e.g., LIDAR, infrared)

Optimize model for mobile/edge deployment

Add license plate recognition module

**##Acknowledgements**
We thank:

Dataset contributors (Kaggle)

Mentors and reviewers from Vellore Institute of Technology (VIT)

Open-source community for their tools and frameworks

**##References**
See references.md for the complete list of research papers and resources used in this project.
