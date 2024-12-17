**Plant Disease Detection: Revolutionizing Agriculture with Machine Learning**

## Overview  
The **Plant Disease Detection** project leverages machine learning to identify plant diseases accurately and quickly. Traditional visual inspection is time-consuming and prone to delays, which can negatively impact crop health. By automating the disease detection process, this project supports healthier crops, boosts agricultural productivity, and promotes sustainable farming.

## Key Features  
- **Machine Learning for Disease Detection**: Deep learning models analyze plant images to diagnose diseases efficiently.  
- **Web Application Interface**: Built with Streamlit for easy access and a user-friendly experience.  
- **Data Visualization**: Matplotlib and Seaborn for visual representation of results and trends.  
- **Scalable Solution**: Supports multiple crops and diseases, adaptable to various agricultural contexts.  

## Challenges  
- **Dataset Quality**: Ensuring the training data is diverse and accurately labeled for optimal model performance.  
- **Model Optimization**: Balancing prediction accuracy with computational efficiency for faster results.  

## Future Enhancements  
- **IoT Integration**: Utilize drones and cameras for real-time monitoring of crops in the field.  
- **Multi-Crop Support**: Expand the model to include more plant types and diseases.  
- **Mobile Application**: Develop a mobile version to allow farmers to diagnose plant diseases on the go.  

## Steps to Start the Project  
1. **Training the Model**  
   Open and run the `Train_plant_disease.ipynb` notebook. This trains the model using the provided dataset and saves it as `trained_plant_disease_model.keras`.  
   
2. **Testing the Model**  
   Open and run the `Test_plant_disease.ipynb` notebook. Provide an image of a plant leaf for testing. The model will predict whether the plant is healthy or diseased based on the training.  

3. **Running the Web Application**  
   Install Streamlit and launch the web application to interact with the trained model.  

## Libraries and Installation Commands  
- **TensorFlow**  
  Install Command:  
  ```bash  
  pip install tensorflow  
  ```  
  Use: For building and training the deep learning model.  
  ```python  
  import tensorflow as tf  
  ```  
- **Keras**  
  Install Command:  
  ```bash  
  pip install keras  
  ```  
  Use: High-level API for neural network construction and training.  
  ```python  
  from keras.models import load_model  
  ```  
- **Matplotlib**  
  Install Command:  
  ```bash  
  pip install matplotlib  
  ```  
  Use: For plotting results and visualizing data trends.  
  ```python  
  import matplotlib.pyplot as plt  
  ```  
- **Seaborn**  
  Install Command:  
  ```bash  
  pip install seaborn  
  ```  
  Use: For creating visually appealing plots.  
  ```python  
  import seaborn as sns  
  ```  
- **Streamlit**  
  Install Command:  
  ```bash  
  pip install streamlit  
  ```  
  Use: For building the web interface.  
  ```bash  
  streamlit run app.py  
  ```  

## File Details  
- **Train_plant_disease.ipynb**: Notebook for training the model.  
- **Test_plant_disease.ipynb**: Notebook for testing the trained model with an input image.  
- **trained_plant_disease_model.keras**: The saved machine learning model after training.  
