# CS4347Project
Pokemon Image classification

The goal of this project is to build a machine learning model capable of correctly identifying a pokemon species from an input image. To address this problem, I used transfer learning with MobileNetv2, which allows efficient feature extraction while reducing training time and overfitting risk. 

The model was developed and trained using Google Colab. The dataset used for this model can be found here:
https://www.kaggle.com/datasets/noodulz/pokemon-dataset-1000?utm_source=chatgpt.com

The model is designed to connect to your Google Drive, specifically the directory: "drive/MyDrive/pokemon-dataset-1000/dataset"
The dataset comes with its own val and train directories, however these were ignored and the model used validation splitting with the dataset folder.

The test set was included at the directory: "drive/MyDrive/pokemon-dataset-1000/test"

To run the model, download the dataset and place at the directory listed above or feel free to alter the pathing.
