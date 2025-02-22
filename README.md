# **Plant Disease Detection: Revolutionizing Agriculture with Machine Learning**  
gASD
## Overview  
The **Plant Disease Detection** project leverages machine learning to identify plant diseases accurately and quickly. Traditional visual inspection is time-consuming and prone to delays, which can negatively impact crop health. By automating the disease detection process, this project supports healthier crops, boosts agricultural productivity, and promotes sustainable farming.

## Key Features  
- **Machine Learning for Disease Detection**: Deep learning models analyze plant images to diagnose diseases efficiently.  
- **Data Visualization**: Matplotlib and Seaborn are used to present results and trends in a visually appealing format.  
- **Scalable Solution**: The system supports multiple crops and diseases, making it adaptable to various agricultural contexts.

## Challenges  
- **Dataset Quality**: Ensuring diverse and accurately labeled data to optimize model performance.  
- **Model Optimization**: Balancing prediction accuracy with computational efficiency to ensure faster results.

## Future Enhancements  
- **IoT Integration**: Use drones and cameras for real-time field monitoring.  
- **Multi-Crop Support**: Expand the model to accommodate a wider variety of plants and diseases.  
- **Mobile Application**: Develop a mobile version to allow farmers to diagnose plant diseases on the go.

## **Python Version**
- Python 3.11.9 or higher.

## Steps to Start the Project  

1. **Training the Model**  
   Open and run the `Train_plant_disease.ipynb` notebook. This will train the model using the provided dataset and save it as `trained_plant_disease_model.keras`.

2. **Testing the Model**  
   Open and run the `Test_plant_disease.ipynb` notebook. Provide an image of a plant leaf for testing. The model will predict whether the plant is healthy or diseased based on the trained data.

3. **Running the Model**  
   Install required libraries and run the model for predictions.

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
  Use: High-level API for constructing and training neural networks.  
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
  Use: For building the web interface (if applicable).  
  ```bash  
  streamlit run app.py  
  ```

## File Details  
- **Train_plant_disease.ipynb**: Jupyter notebook for training the model.  
- **Test_plant_disease.ipynb**: Jupyter notebook for testing the trained model with an input image.  
- **trained_plant_disease_model.keras**: The saved machine learning model after training.
