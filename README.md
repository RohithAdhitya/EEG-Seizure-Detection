# 🧠 EEG Classification Model for Seizure Detection

**This project builds and evaluates classification models on EEG data to identify epileptic seizure activity. It applies both traditional and deep learning techniques, using rich features and real-world medical datasets.**

---

## 📄 Overview
The project aims to detect seizures from EEG (Electroencephalogram) signals using classification models trained on the CHB-MIT Scalp EEG dataset. By combining signal processing, statistical and frequency-based features, and machine learning models, the goal is to aid timely seizure recognition and support epilepsy care.

---

## 🎯 Objectives
- Preprocess EEG data from the CHB-MIT dataset
- Extract statistical, entropy, and spectral features
- Apply SMOTE to address class imbalance
- Train and compare Decision Tree and CNN models
- Evaluate performance using accuracy and F1 score
- Visualize predictions and model performance

---

## 🧰 Tech Stack
- **Python**: NumPy, Pandas, SciPy, MNE, Scikit-learn, Keras, TensorFlow
- **Libraries**: Matplotlib, Seaborn, Imbalanced-learn (SMOTE)
- **Models**: Decision Tree, Convolutional Neural Network (CNN)

---

## 🧪 Data Preprocessing & Feature Engineering
- **Normalization** of EEG signals
- **Entropy metrics**: Sample entropy, fuzzy entropy
- **Frequency analysis**: STFT, power spectral density
- **Filtering**: Bandpass (1–50 Hz), channel selection
- **Windowing**: Timestamped sliding windows
- **Labeling**: Based on seizure annotations

---

## 🏗️ Model Architectures

### ✅ Decision Tree
- Balanced with SMOTE
- Achieved **88.9% accuracy**, **0.89 F1-score**

### 🧠 CNN (Deep Learning)
- Conv1D layers with max pooling
- Trained using binary cross-entropy and Adam optimizer
- Achieved **63.1% accuracy**, **0.64 F1-score**
- Could benefit from further tuning

---

## 🔍 Visualizations
- EEG signal plots with predicted seizure regions
- Confusion matrix for classification evaluation
- Accuracy and F1-score metrics comparison

---

## 📥 Dataset
**Content**: EEG recordings from pediatric patients with epilepsy  
**Annotations**: 182 labeled seizure events

---

## 📈 Future Improvements
- Explore ensemble methods (Random Forest, XGBoost)
- Hyperparameter tuning for CNN
- Real-time monitoring integration
- Transfer learning and model generalization
- Clinical testing and ethical compliance

---

## 👥 Contributors
- Pramoth Guhan  
- Rohith Adhitya Chinnannan Rajkumar  
- Divyia Venkat Eachampatti Thirunavukarasu

---

## 📅 Submission
**IE6400 Foundations of Data Analytics Engineering**  
Fall Semester 2023 | Group 22  
Submitted: December 15, 2023

---

## 📜 License
This project is for educational and research purposes only, using publicly available medical datasets.

