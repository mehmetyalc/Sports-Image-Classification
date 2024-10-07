# Sports Image Classification Using Machine Learning

This project is part of the **Business Intelligence II** course at Carl von Ossietzky Universität Oldenburg, supervised by Prof. Dr.-Ing. habil. Jorge Marx Gómez.

## Overview

This project aims to classify sports images using deep learning models, specifically Convolutional Neural Networks (CNNs), to address the challenges of automated image tagging and sports analytics.

### Objective
- Build a machine learning model that classifies images from different sports categories using CNNs.
- Utilize transfer learning to improve the model's performance, leveraging pre-trained models like Xception.

### Dataset
- The dataset is sourced from Kaggle, containing 14,493 images across 100 sports categories, ranging from popular sports like soccer and basketball to niche sports like sumo wrestling and skydiving.
- [Sports Classification Dataset - Kaggle](https://www.kaggle.com/datasets/gpiosenka/sports-classification?resource=download)

### Methods
1. **Data Preprocessing:**
   - Images were resized to 224x224 pixels and normalized.
   - Data augmentation techniques (horizontal flipping, random rotations, and zooming) were applied to address class imbalance.

2. **Exploratory Data Analysis (EDA):**
   - Analyzed the class distribution, identifying imbalances between popular and niche sports categories.
   - Investigated potential misclassifications using confusion matrices to improve model design.

3. **Model Architecture:**
   - **Custom CNN Model** with convolutional and pooling layers, followed by fully connected layers.
   - **Xception Model** (Transfer Learning): A pre-trained model on ImageNet, used for feature extraction.

4. **Results:**
   - Final Test Accuracy: **97.60%** using the Xception model.
   - The model performed well on common sports like soccer and basketball but had difficulty with less-represented categories such as sumo wrestling.

### Future Work
- Address class imbalance using synthetic data generation techniques like SMOTE.
- Explore real-time deployment for sports media companies to automate image tagging during live events.

## Files in This Repository:
- **Notebooks/sport_image_classification_final_final.ipynb:** Jupyter notebook with the full machine learning pipeline.
- **Presentation/BI_2_presentation.pptx:** Final presentation slides summarizing the project.
- **Documentation/BI Term Paper.pdf:** Detailed report explaining the methodology, results, and future work.

## How to Use:
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Sports-Image-Classification.git
