# Fashion clothes classification
This project demonstrates an image classification application using both a custom Convolutional Neural Network (CNN) and a fine-tuned ResNet18 model built on top of PyTorch. The models are trained to classify images from the FashionMNIST dataset, a popular dataset for fashion-related image classification.

# Demo 🚀
https://clothesclassification-8zdkbaauyd8jegrahdd7py.streamlit.app/

![image](https://github.com/user-attachments/assets/65c40c2f-91fd-4dcf-aa02-e9ad3382fe7c)


# Features:
- Streamlit Interface: A simple web application built using Streamlit, allowing users to upload images and classify them using the pre-trained and custom models.
- Custom CNN: In addition to the ResNet model, we designed and fine-tuned our own Convolutional Neural Network (CNN) architecture to improve performance on the FashionMNIST dataset.
- ResNet18 Model: The ResNet18 model is fine-tuned with custom modifications to the fully connected layers, trained on FashionMNIST data to classify fashion items.
- Class Predictions: The models output the predicted class of the uploaded image from a set of predefined categories, such as T-shirt/top, Trouser, Dress, etc.
- Easy Setup: No need for complex installations. You can run the app locally using streamlit run and start classifying images instantly. write all of this in one text without dividing

# Setup and Installation
To get started, clone the repository and install the required dependencies:
  - git clone https://github.com/aloaew/fashion_classification.git
  - cd image-classification-advanced-resnet
  - pip install -r requirements.txt

# Running the App
To run the Streamlit app locally, follow these steps:
Download or clone this repository.
Make sure the model file advanced_resnet.pth is available in the project folder or specify the correct path.
Open a terminal in the project directory and run:
   - streamlit run app.py
The app will launch and provide a URL (typically http://localhost:8501). Open the URL in your browser, upload an image, and see the predicted class!

# Classes
The model is trained to classify images into the following 10 categories:
- T-shirt/top
- Trouser
- Pullover
- Dress
- Coat
- Sandal
- Shirt
- Sneaker
- Bag
- Ankle boot
  
![image](https://github.com/user-attachments/assets/4c9e4907-0dd7-465f-af18-ba104f3acb17)


# Contributions
Feel free to fork this repository, make changes, and submit pull requests. Contributions are always welcome!

