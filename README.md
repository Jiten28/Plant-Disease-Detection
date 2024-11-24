# Plant-Disease-Detection
Plant Disease Detection

Hello everyone. My project focuses on using machine learning to detect plant diseases quickly and accurately. Traditional visual inspections are slow and labor-intensive, so I'm leveraging machine learning to automate the process. This approach aims to improve crop health, increase yields, and promote sustainable agriculture.

Python version: 3.11.9

In order to run this program you first need to install some modules:
    • Tensorflow 
        (pip install tensorflow)
    • Matplotlib
        (pip install matplotlib)
    • sSeaborn
        (pip install seaborn)
    • pandas
        (pip install pandas)
    • Keras
        (pip install keras)

In order to run the web application we are using streamlite
    • streamlit
        (pip install streamlit)

# Process
To get the program working, you first need to train and save the model by running "Train_plant_disease.ipynb".

This will save a file named "trained_plant_disease_model.keras," which is our trained model.

You can then test the model by running "Test_plant_disease.ipynb". In this file, you need to provide an image for testing, and based on your model's accuracy, it will predict the result.
