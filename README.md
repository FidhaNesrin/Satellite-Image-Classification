🌍 Satellite Image Classification using CNN
📌 Overview

This project builds a Convolutional Neural Network (CNN) to classify satellite images into three land categories:

☁️ Cloudy
🏜️ Desert
🌿 Green Area

The objective is to automate land-type detection from satellite imagery, reducing manual effort and enabling faster geospatial analysis.

⚙️ What I Implemented
Loaded image datasets using glob
Performed image preprocessing & resizing (64×64)
Assigned labels for multi-class classification
Built a CNN model using TensorFlow/Keras
Trained and validated the model
Evaluated performance using:
Accuracy
Confusion Matrix

🧠 Model Architecture

The CNN model consists of:

Conv2D (16 filters) + ReLU
MaxPooling
Conv2D (32 filters) + ReLU
MaxPooling
Flatten layer
Dense layer (64 neurons)
Output layer (Softmax for 3 classes)

📊 Tech Stack
Language: Python
Libraries:
TensorFlow / Keras
NumPy
MatplotlibSeaborn
Scikit-learn
skimage

📈 Workflow
Data collection from image folders
Label encoding (0: Cloudy, 1: Desert, 2: Green Area)
Data shuffling and splitting
Image resizing for uniform input
Model training (30 epochs)
Prediction and evaluation
📉 Results
The model is able to distinguish between different land types with reasonable accuracy
Confusion matrix visualization shows class-wise prediction performance

(Note: Performance can improve with larger datasets and deeper architectures)

🌐 Applications
Environmental monitoring
Land-use analysis
Agriculture insights
Climate-related studies

🔮 Future Improvements
Use transfer learning (ResNet / VGG16)
Increase dataset size for better generalization
Add data augmentation
Deploy as a web application

🤝 Let’s Connect

I’m actively looking for Data Analyst / Data Science roles.
If you have feedback or opportunities, feel free to connect!

⭐ Support

If you found this useful, consider giving it a ⭐

fidhanesrin278@gmail.com
https://www.linkedin.com/in/fidha-nesrin-50832b381/

Seaborn
Scikit-learn
skimage
