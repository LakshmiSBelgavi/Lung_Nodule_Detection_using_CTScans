# Evolutionary CNN Framework for Precise Lung Nodule Detection using CT Scan images.

## Introduction
This project aims to detect and analyze lung nodules from CT scans using advanced machine learning techniques, facilitating early diagnosis of potential lung cancers. It improves healthcare outcomes by providing accurate and efficient analysis of medical images.

---

## Features
- Detection of lung nodules from CT scan images.
- High accuracy in prediction using state-of-the-art machine learning algorithms.

---

## Technologies Used
- **Languages**: Python 3
- **Libraries**: TensorFlow, Keras
- **Tools**: Jupyter Notebook,PyCharm [IDE]
- **Platform**: Google Colab
- **Algorithms used**: Convolutional Neural Netwrok[CNN] , Gray Wolf Optimization[GWO]




---

## Dataset
- **Source**: LIDC-IDRI database.
- **Description**: The dataset contains 10,000 CT scan images of lungs with annotations for nodule locations.
- **Preprocessing**: 
  - Normalized intensity levels.
  - Resized images to 256x256 resolution.
  - Applied data augmentation to address class imbalance.

---

## Methodology
1. **Data Preprocessing**:
   - Resizing images.
   - Normalization and augmentation.
2. **Feature Extraction**:
   - Utilized Convolutional Neural Networks (CNNs) for feature extraction.
3. **Model Building**:
   - Built and trained a deep learning model using TensorFlow and Keras.
4. **Evaluation**:
   - Used metrics like accuracy, precision, recall, and F1-score to evaluate the model's performance.

---

## Results
- **Accuracy**: 97%
- **Precision**: 94%
- **Recall**: 93%
- **F1-Score**: 97%


### Visual Results of Web Application
1. **The lung nodule detection Page**:<br>


   ![Web Application](images/web%20app.png)


2. **Uploading the images**:<br>


   ![Image Upload](images/image%20upload.png)


3. **Result : CASE 1**:<br>


   ![Normal](images/case%201.png)


4. **Result : CASE 2**:<br>


   ![Benign](images/case%202.png)


5. **Result : CASE 3**:<br>


   ![Malignant](images/case%203.png)


