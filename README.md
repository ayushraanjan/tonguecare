
# **TongueCare**
Our innovative **TensorFlow**- powered project **diagnoses tongue diseases** through a single smartphone picture, providing quick and accessible healthcare insights. Using machine learning, our model ensures early detection, contributing to proactive health management. Seeking investment to optimize the model, expand the dataset, and deploy a user-friendly solution. With market potential driven by smartphone ubiquity, we aim to revolutionize healthcare diagnostics. Join us in making early healthcare intervention a reality.

![TongueCare](https://github.com/ayushraanjan/tonguecare/blob/c528e0183eb6e2b81e35aa4e6424cddd3545b8dd/Tongue%20Care.png)
![TongueCare Landing Page](https://github.com/ayushraanjan/tonguecare/blob/515351ae2e03e118aecd31d887a37ae0c5c9d046/Screenshot%20from%202024-02-23%2010-57-59.png)


## **Overview**

This project utilizes machine learning to predict tongue health based on images captured from your phone's camera. Using **TensorFlow.js**, the model is trained to classify tongues into categories such as healthy, thrashes, ulcer, visit (suggesting a visit to a healthcare professional), and could not predict. The application is deployed on **Firebase**, making it easily accessible for users.

## **Features**

- **Tongue Health Prediction**: Upload a picture of your tongue, and the model will provide a prediction regarding its health status.
- **Multiple Classes**: The model can classify tongues into different classes such as healthy, thrashes, ulcer, visit, or indicate if it could not make a prediction.
- **Firebase Deployment**: The application is hosted on Firebase, ensuring easy access for users through a web-based interface.
- **TensorFlow.js Integration**: The project leverages the TensorFlow.js library, allowing for machine learning model inference directly in the browser.

## **Getting Started**

### **Prerequisites**

- Ensure you have a modern web browser that supports the necessary web technologies for TensorFlow.js.

### **Usage**

1. Visit the deployed application on Firebase: [TongueCare](https://tonguecare-a0c2b.web.app/)
2. Allow camera access when prompted.
3. Capture an image of your tongue.
4. Wait for the model to process the image and display the predicted health status.

### **Local Development**

If you wish to run the project locally:

1. Clone this GitHub repository:  
    bash

        git clone <https://github.com/ayushraanjan/tongue-health-predictor.git>

Navigate to the project directory:  
bash

      cd tongue-health-predictor

1. Open the index.html file in your web browser.
2. Allow camera access when prompted.
3. Capture an image of your tongue.
4. The model will process the image locally and display the predicted health status.

## **Contributing**

If you would like to contribute to the project, feel free to submit a pull request or open an issue.

## **License**

This project is licensed under the MIT License - see the LICENSE file for details.

## **Acknowledgments**

- Thanks to the TensorFlow.js team for providing a powerful library for machine learning in the browser.
- Special thanks to the contributors and users who provide valuable feedback to improve the project.
