🌿 **MediPlant – Plant Leaf Disease Detection & Pesticide Recommendation System**


📌 **Project Overview**

MediPlant is a Deep Learning-based plant disease detection system that identifies leaf diseases using image classification and recommends suitable pesticides based on the predicted disease.

The system is designed to assist farmers and agricultural professionals by providing fast, accurate, and intelligent crop disease diagnosis.

This project leverages Convolutional Neural Networks (CNN) for image classification and integrates pesticide recommendation data stored in an Excel file.

🎯 **Problem Statement**

Plant diseases significantly reduce agricultural productivity. Early detection and proper pesticide selection are critical to preventing crop loss.

**MediPlant aims to:**

Detect plant leaf diseases using image input

Provide pesticide recommendations

Assist in faster agricultural decision-making

🚀 **Key Features**

🌿 Leaf image-based disease detection

🤖 CNN-based deep learning model

📊 Model training and testing using Jupyter Notebooks

💊 Pesticide recommendation system (Excel-based dataset)

🖼️ Simple user interface using Python

🛠️ **Tech Stack**
Category	Technology
Programming Language	Python
Deep Learning	TensorFlow / Keras
Model Type	Convolutional Neural Network (CNN)
Data Handling	Pandas
Dataset	Plant leaf disease image dataset
UI	Python-based interface
Data Storage	Excel (pest.xlsx)


🧠 **System Workflow**

Collect plant leaf image dataset.

Train CNN model using Train_plant_disease.ipynb.

Validate model using Test_plant_disease.ipynb.

Load trained model in main.py.

User provides leaf image input.

System predicts disease.

Based on prediction, pesticide recommendation is fetched from pest.xlsx.

Final result is displayed to the user.

📂 **Project Structure**
MediPlant-Plant-Recognition-System/
│
├── Train_plant_disease.ipynb   # Model training
├── Test_plant_disease.ipynb    # Model testing
├── main.py                     # Application entry point
├── pest.xlsx                   # Pesticide recommendation data
├── background.jpg              # UI background image
├── home_page.jpeg              # Home screen image
└── README.md



📊 **Model Details**

Architecture: Convolutional Neural Network (CNN)

Image Preprocessing: Resizing & normalization

Loss Function: Categorical Crossentropy

Optimizer: Adam

Evaluation Metrics: Accuracy

📈 **Results**

Achieved high classification accuracy on validation dataset.

Successfully mapped predicted diseases to relevant pesticide recommendations.

Reduced manual effort in disease identification.

🌟 **Project Highlights**

Real-world agriculture problem solving

Deep learning model implementation

End-to-end pipeline (Training → Testing → Deployment)

Data-driven pesticide recommendation system

🔮 **Future Enhancements**

🌍 Web-based deployment (Streamlit / Flask)

📱 Mobile application integration

📊 Real-time camera-based detection

🧠 Improved accuracy with larger dataset

☁️ Cloud deployment (AWS / Azure)

👩‍💻 **Developed By**

Yasaswi Challa
