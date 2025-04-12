# **PDE4433 – Machine Learning for Robotics**

# **Coursework 2 (CW2)**

# **Topic: Nut and Bolt Detection using Machine Learning**

## Project Overview:

This project automates the detection and classification of bolts and nuts usign Machine Learning Models Custom CNN and MobileNetv2 models. It is implemented in Python using Jupyter Notebook and is compatible across windows, macOS and Linux platforms

## System requirements :

- python 3.8 or above
- If Python not installed. Please download and install from https://www.python.org/downloads/

- PIP 
- If Pip not installed. Please download and install from https://packaging.python.org/en/latest/tutorials/installing-packages/

- Jupyter Notebook
- If Jupyter Notebook not installed, use the below code to install in the windows powershell
  
             pip install notebook

- Libraries like TensorFlow, Keras, OpenCV, Numpy, Matplotlib, Pathlib, Sklearn

              pip install tensorflow keras opencv-python numpy matplotlib scikit-learn pathlib

## Downloading the file and dataset:

- Download the Zip file of the coursework and unzip it, place it in the desired folder.
- Click the github repository link form the report and download the file, place it in the desired folder or location in the system.

## Running the Program:

- Launch the Jupyter Notebook

      jupyter notebook

- Jupyter notebook opens in the browser and displays the file in the home folder.
- Navigate to the Folder where the unzipped file of the coursework is pasted.
- You can see the files and folders as in the image below,
  
  ![Screenshot 2025-04-12 012400](https://github.com/user-attachments/assets/6c8c3219-1eca-49cb-bd9e-37c4e446df14)

- To run the Custom CNN model - double click - Bolt_nut_classification_using_CNN.ipynb
- To run the MobileNetV2 Pretrained model - double click - Bolt_nut_classification_using_Mobilenet2.ipynb
- To visualize the pre processing used in the project - open - Preprocessing_sample.ipynb

### Executing the Notebook Cells
For both Custom CNN and MobileNetv2 models the notebook format is exactly the same, except the model script-
- To run the machine learning and Evaluation
    - Follow the order of the notebook
        - Step 1 : Importing the required libraries
        - Step 2 : Routing the path of the dataset
        - Step 3 : Loading the dataset and preprocessing
        - Step 4 : Loading the data and reshaping to prepare for training process
        - Step 5 : Spliting the data for training and testing
        - Step 6 : CNN Model
        - Step 7 : Compiling the model
        - Step 8 : Training the model
        - Step 9 : Evaluating the accuracy of the model
        - Step 10 : Model Summary
        - Step 11 : Model Performance graph
        - Step 12 : Save the Model
          - For Custom CNN, it is saved as
          ![save_model_cnn](https://github.com/user-attachments/assets/9b18a937-ab5e-4be1-8d3d-b3df836d3374)
          - For MobileNetV2, it is saved as
          ![SAVE_model](https://github.com/user-attachments/assets/d45c1ac6-ee9f-4362-9864-7bb90ba938b1)

### Testing the model with images:
To execute the testing program, the saved keras file is mandatory. Please ensure the keras is saved in the same folder of the coursework. Follow the below steps to see the result images.

- Step 13 : Function for ploting the image
  - Run the function "show image" which contain the image ploting program
- Step 14 : Testing the Model with Images which are not involved in training
  - Test Result - ![Git_test_image](https://github.com/user-attachments/assets/a4249312-206d-48bc-bd85-0a82c8d7e098)

### Testing the model with live streaming webcam:
- Step 15 : Live Detection 
  - Live detection Screenshot - ![live_dection](https://github.com/user-attachments/assets/bf3594f3-3a50-43b1-b761-8b6422145f41)

