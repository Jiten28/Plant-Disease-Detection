## **Plant Disease Detection**  
**Revolutionizing Agriculture with Machine Learning**

### **Overview**  
Plant Disease Detection is a machine learning-powered project aimed at identifying plant diseases with speed and accuracy. Traditional methods of visual inspection are time-consuming and labor-intensive, often leading to delayed interventions. This project automates the detection process, promoting healthier crops, increasing agricultural yields, and supporting sustainable farming practices.

### **Key Features**  
- **Disease Detection with Machine Learning**: Utilizes deep learning models to analyze images of plants and diagnose diseases.  
- **Web Application Interface**: Powered by Streamlit for easy accessibility and user-friendly interaction.  
- **Data Visualization**: Uses Matplotlib and Seaborn for presenting results and trends in a visual format.  
- **Scalable Solution**: Designed to accommodate diverse crops and diseases.  

### **Challenges**  
- **Dataset Quality**: Ensuring the training data is diverse and accurately labeled for high model performance.  
- **Model Optimization**: Balancing accuracy with computational efficiency for faster predictions.  

### **Future Enhancements**  
- **Integration with IoT**: Combine with IoT devices like drones and cameras for real-time field monitoring.  
- **Multi-Crop Support**: Extend support to a wider variety of plants and diseases.  
- **Mobile Application**: Develop a mobile-friendly version for farmers to diagnose plants on the go.

### **Steps to Start the Project**  

#### **1. Training the Model**  
   - Open and run the `Train_plant_disease.ipynb` notebook.  
   - This will train the model using the provided dataset and save it as `trained_plant_disease_model.keras`.

#### **2. Testing the Model**  
   - Open and run the `Test_plant_disease.ipynb` notebook.  
   - Provide an image of a plant leaf for testing. The model will predict whether the plant is healthy or diseased based on its training.  

#### **3. Running the Web Application**  
   - Install Streamlit (see library installation commands below).  
   - Launch the web application to test the model through an interactive interface.

### **Libraries and Installation Commands**  

1. **TensorFlow**  
   - **Install Command**:  
     ```bash
     pip install tensorflow
     ```  
   - **Use**: For building and training the deep learning model.  
     ```python
     import tensorflow as tf
     ```

2. **Keras**  
   - **Install Command**:  
     ```bash
     pip install keras
     ```  
   - **Use**: High-level API for neural network construction and training.  
     ```python
     from keras.models import load_model
     ```

3. **Matplotlib**  
   - **Install Command**:  
     ```bash
     pip install matplotlib
     ```  
   - **Use**: For plotting results, trends, and data visualizations.  
     ```python
     import matplotlib.pyplot as plt
     ```

4. **Seaborn**  
   - **Install Command**:  
     ```bash
     pip install seaborn
     ```  
   - **Use**: For creating visually appealing and detailed plots.  
     ```python
     import seaborn as sns
     ```

5. **Pandas**  
   - **Install Command**:  
     ```bash
     pip install pandas
     ```  
   - **Use**: For data manipulation and analysis.  
     ```python
     import pandas as pd
     ```

6. **Streamlit**  
   - **Install Command**:  
     ```bash
     pip install streamlit
     ```  
   - **Use**: For building a web-based interface to interact with the trained model.  
     ```bash
     streamlit run app.py
     ```

### **File Details**  
- **`Train_plant_disease.ipynb`**: Jupyter notebook for training the model.  
- **`Test_plant_disease.ipynb`**: Jupyter notebook for testing the trained model with an input image.  
- **`trained_plant_disease_model.keras`**: The saved machine learning model after training.
