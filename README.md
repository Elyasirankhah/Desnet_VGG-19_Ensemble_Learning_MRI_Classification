
README_File: Ensemble Learning: Multi-Modal MRI Image Classification using Combined DenseNet-VGG19 Model 

Overview:
This code represents a multi-modal MRI image classification approach using a combined DenseNet-VGG19 model to jump into ensemble learning world. It loads and preprocesses grayscale images, constructs and trains individual DenseNet and VGG19 models separately, and finally integrates these models into a unified architecture for improved classification performance. The code also includes evaluation metrics such as confusion matrices and classification reports to assess model performance.

Requirements:
●	Python 3.x
●	TensorFlow
●	NumPy
●	OpenCV
●	Matplotlib
●	Seaborn
●	Scikit-learn

Dataset:
●	Dataset source: Provided the source of the MRI dataset used in the repository. [Link]

How to run?
●	Please ensure all required libraries are installed.
●	Download the dataset which is linked to this repository, containing MRI images and organize them into training and testing directories.
●	Update the file paths in the code to point to the correct directories.
●	Run the code to train and evaluate the models. Please remember, this code contains all models separately and you have to set the path individually for each model specifically while it takes some hours to complete the process.

Code Structure:
●	load_images: Contains functions to load and preprocess images.
●	densenet_model: Defines and trains the DenseNet model.
●	vgg19_model: Defines and trains the VGG_19 model.
●	combined_model: Combines the DenseNet and VGG_19 models and trains the combined model.
●	evaluation: Includes code for evaluating model performance using confusion matrices and classification reports.

Results:
●	Confusion matrices: Visual representations of model predictions compared to ground truth labels.
●	Classification reports: Detailed metrics including precision, recall, and F1-score for each class.

Collaborators:
●	Elyas Irankhah
●	Jash Gandhi
●	Naga Sai Tejaswi Gandu
●	Rudram Vyas

