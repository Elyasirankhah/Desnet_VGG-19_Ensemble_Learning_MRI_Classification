***Ensemble Learning: Multi-Modal MRI Image Classification using Combined DenseNet-VGG19 Model***

**Overview:**
This repository contains code for a multi-modal MRI image classification approach utilizing a combined DenseNet-VGG19 model, delving into the realm of ensemble learning. The code is designed to:

- Load and preprocess grayscale MRI images.
- Construct and train individual DenseNet and VGG19 models separately.
- Integrate these models into a unified architecture to leverage ensemble learning for improved classification performance.
- Provide evaluation metrics such as confusion matrices and classification reports to assess model performance.

**Requirements:**
- Python 3.x
- TensorFlow
- NumPy
- OpenCV
- Matplotlib
- Seaborn
- Scikit-learn

**Dataset:**
- The MRI dataset used in this repository can be obtained from the provided source link.

**How to Run?**
1. Ensure all required libraries are installed.
2. Download the dataset linked to this repository, which contains MRI images, and organize them into training and testing directories.
3. Update the file paths in the code to point to the correct directories.
4. Run the code to train and evaluate the models. Note: The code contains all models separately, and individual paths need to be set for each model. The training process may take several hours to complete.

**Code Structure:**
- `load_images`: Contains functions to load and preprocess images.
- `densenet_model`: Defines and trains the DenseNet model.
- `vgg19_model`: Defines and trains the VGG19 model.
- `combined_model`: Combines the DenseNet and VGG19 models and trains the combined model.
- `evaluation`: Includes code for evaluating model performance using confusion matrices and classification reports.

**Results:**
- Confusion Matrices: Visual representations of model predictions compared to ground truth labels.
- Classification Reports: Detailed metrics including precision, recall, and F1-score for each class.

**Collaborators:**
- Elyas Irankhah
- Jash Gandhi
- Naga Sai Tejaswi Gandu
- Rudram Vyas
