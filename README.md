# Facial-Expression-Recognition-
Using the FER2013 dataset of facial expressions with the following categories: {0:'Angry', 1:'Disgust', 2:'Fear', 3:'Happy', 4:'Sad', 5:'Surprise', 6:'Neutral'}  Train a CNN model on the dataset then further use the transfer learning model with VGG19 as a base and train that as well on the dataset Save the models and then predict using a test image on both models to see which is better suited for the task.

##################################################
Please ensure to install the dataset and extract the train.csv and test.csv from the compressed files.
Also ensure that these files are present in the same folder as the code.

Furthurmore the transfer learning model may not work if the system does not have enough RAM (mine has 16 so training 25K+ 96,96 images is not a problem)
-----Incase of a OOM error you could save numpy array as images on your system and use .flow_from_directory or .image_dataset_from_directory rather then .flow method

check https://keras.io/api/preprocessing/image/ for more details

###################################################
Install the FER2013 dataset from kaggle
https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data
