# Brain Tumor Classification Using Convolutional Neural Networks (CNN)

## Summary of the Model

### 1. Data Loading and Preprocessing
- **Dependencies**: The notebook begins by importing essential libraries, including NumPy, pandas, OpenCV, and Matplotlib.
- **Data Loading**: It loads training and testing data from a directory containing brain tumor MRI images. These images are categorized into four types: glioma, meningioma, no tumor, and pituitary tumors.
- **Preprocessing**: Images are read and resized to a uniform size of 512x512 pixels. They are then flattened into one-dimensional arrays to prepare them for further processing.

### 2. Dataset
- **Data Division**: The dataset is split into training and testing sets. Each image is labeled according to one of the four tumor types.
- **Label Encoding**: Labels are encoded into numerical values to be used in the machine learning model.

### 3. Modeling
- **Model Building**: The notebook includes steps for constructing and training a machine learning model. This model classifies images into the four tumor categories based on the preprocessed data.

## Importance of the Model
- **Medical Diagnostics**: This model is vital for the automated detection of brain tumors, which can significantly aid in early diagnosis and treatment. It helps reduce the workload on radiologists and enhances diagnostic accuracy.
- **Efficiency**: Automating brain tumor classification with this model can lead to faster analysis, which is crucial in medical emergencies.
- **Scalability**: Once trained, the model can be deployed across various healthcare facilities, offering consistent and accurate diagnostic support.

## Dataset

The dataset used for this project is obtained from Kaggle and includes MRI images for different types of brain tumors:

- **Dataset Source**: [Kaggle Brain Tumor MRI Dataset](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset)

## Tools & Technologies
- **Programming Languages**: Python
- **Libraries & Frameworks**: OpenCV, NumPy, Pandas, Matplotlib
- **Techniques**: Computer Vision, Convolutional Neural Networks (CNN)
