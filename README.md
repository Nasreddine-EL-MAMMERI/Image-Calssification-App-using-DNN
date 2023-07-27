# Image-Calssifying-App-using-DNN


## Overview
This is a Streamlit app for performing image classification using OpenCV and a pre-trained Deep Learning model. The app allows users to either upload an image file or provide an image URL to perform image classification. The app uses the DenseNet-121 model trained on the ILSVRC2012 dataset for image classification.

## Demo
to try this app please visit this link :  
http://localhost:8501/ 

## How to Run the App Locally
To run the Streamlit app locally on your machine, follow the steps below:

### Clone the repository to your local machine:
git clone https://github.com/your_username/your_repository.git

### Navigate to the app's directory:

cd your_repository

### Install the required dependencies:

pip install -r requirements.txt

### Run the Streamlit app:

streamlit run app.py

### Access the app in your web browser at http://localhost:8501.

## Usage

Upon running the app, you will see the title "OpenCV Deep Learning based Image Classification."

You can either choose a file or use the text input to enter an image URL.

If you choose a file, click on the "Choose a file or Camera" button and select an image file (supported formats: jpg, jpeg, png).

If you want to use an image URL, enter the URL in the text input box labeled "Enter URL" and press Enter.

The app will display the uploaded image, and below it, you will see the result of image classification in the format "Class: {class_name}, Confidence: {confidence_score}%."

The image classification is performed using the DenseNet-121 model pre-trained on the ILSVRC2012 dataset. The classification result includes the class name and the confidence score.

If you encounter any issues or errors, you may see relevant messages displayed on the app interface.

## Data Source and Credits

The pre-trained DenseNet-121 model is provided by the DenseNet-Caffe repository.
The ILSVRC2012 dataset contains the ImageNet class names used for image classification.
Dependencies
Python 3.x
Streamlit
OpenCV
NumPy
PIL (Pillow)
Requests
Limitations
The app currently supports image classification for jpg, jpeg, and png formats only.
Contributing
Contributions to the app are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.


## DenseNet_121.caffemodel

Since the file has a large size, you can use the link below to download it: 

[Download Large File](https://www.dropbox.com/scl/fi/67k82raspopx841mj87ep/DenseNet_121.caffemodel?rlkey=ccvhp234v5euqnz3c6ftdz5bg&dl=0)
