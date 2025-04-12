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
        - Importing the required libraries
        - Routing the path of the dataset
        - Loading the data and preprocessing
        - Training the CNN and Mobilenetv2 model in respective notebook
        - Evaluation of the trained model
        - Performance graph for the model
        - Save the model
          ![SAVE_model](https://github.com/user-attachments/assets/d45c1ac6-ee9f-4362-9864-7bb90ba938b1)

