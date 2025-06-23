# Explainable Hybrid Deep Learning for Comorbid Disorder Diagnosis Using EEG & Neuroimaging

## Overview

This project uses advanced deep learning to help doctors automatically identify and classify multiple psychological disorders (including comorbidities) from EEG and Alzheimer's neuroimaging data. It combines several powerful neural network models—AlexNet, ResNet, DenseNet, and EfficientNet—as well as hybrid models that fuse their strengths. The project also explains its predictions using modern AI explainability tools.

## What Does It Do?

- **Reads and processes EEG and Alzheimer's neuroimaging data**
- **Balances and augments the data** so all classes are represented fairly
- **Selects the most important features** for accurate prediction
- **Trains multiple deep learning models** (AlexNet, ResNet, DenseNet, EfficientNet, and hybrid combinations)
- **Evaluates each model** using accuracy, precision, recall, F1-score, and confusion matrices
- **Visualizes training progress and results**
- **Provides explainability** (so you can see why the AI made its decision)

## How Does It Work?

1. **Data Preprocessing:**  
   Cleans the EEG and neuroimaging data, scales features, balances classes using SMOTE, and selects the best features for learning.

2. **Model Training:**  
   Trains several state-of-the-art neural networks (AlexNet, ResNet, DenseNet, EfficientNet) and hybrid models that combine their strengths, using Keras and TensorFlow.

3. **Evaluation:**  
   Measures how well each model performs using standard metrics (accuracy, precision, recall, F1-score) and confusion matrices.

4. **Visualization:**  
   Plots training/validation accuracy and loss graphs, and confusion matrices for easy comparison.

5. **Explainability:**  
   Uses explainable AI techniques (like SHAP and Grad-CAM) to highlight which features or brain regions influenced the model’s decision.

## Why Is It Efficient?

- **Hybrid Models:**  
  Combines multiple neural network architectures to get the best of each, leading to higher accuracy and robustness[2].
- **Automated Feature Selection:**  
  Only uses the most important data, speeding up training and improving results.
- **Balanced Data:**  
  Uses SMOTE to ensure all classes are fairly represented, reducing bias.
- **Explainability:**  
  Makes AI decisions transparent, which is important for clinical trust.

## How To Use

1. **Clone the repository:**  
   `git clone <https://github.com/Praveshika2k/Explainable-Hybrid-Deep-Learning-for-Comorbid-Disorder-Diagnosis-Using-EEG-Neuroimaging.git>`

2. **Install dependencies:**
   
3. **Prepare your data:**  
Place your EEG and Alzheimer's CSV files in the project directory.

4. **Run the main script:**  

5. **Check the results:**  
- Training graphs and confusion matrices will be saved as images.
- Model performance metrics will be printed in the terminal.

## Results

- Achieves high accuracy (often above 90%) on comorbid psychological disorder diagnosis.
- Provides easy-to-understand visualizations and explanations for each prediction.

---

*This project is designed for researchers, clinicians, and students interested in medical AI, neuroscience, and explainable deep learning.*


