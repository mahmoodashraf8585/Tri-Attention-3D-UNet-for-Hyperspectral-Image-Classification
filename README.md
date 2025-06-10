More datasets can be downloaded from the given link: https://www.ehu.eus/ccwintco/index.php/Hyperspectral_Remote_Sensing_Scenes
Download the datasets from this repository or from the given above link
Upload the datasets to your Google Drive in dataset folder
Open the notebook: Tri 3D-Unet_architecture22.ipynb in the google colab
Mount Google Drive in the notebook: from google.colab import drive drive.mount('/content/drive')
Set the dataset path in the notebook
Run the cells step by step to:
Load and preprocess the hyperspectral dataset
Build the Tri-Attention 3D UNet model
Train and evaluate the model
Visualize classification results (accuracy, loss, confusion matrix, etc.)

Requirements:
All dependencies are handled inside Google Colab. Key libraries include:
tensorflow
numpy
scipy
matplotlib
scikit-learn
No manual installation is needed.
