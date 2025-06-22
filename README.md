📦 MNIST Digit Generator Web App (CVAE)
This Streamlit app generates handwritten digits (0–9) using a trained Conditional Variational Autoencoder (CVAE) on the MNIST dataset.

🚀 Features
Select a digit (0 to 9)

Generates 5 handwritten-style variations of the selected digit

Uses a CVAE decoder trained from scratch on MNIST

Fast and interactive interface via Streamlit

📁 Files in This Repo
File	Description
streamlit_app.py	Streamlit web app interface
decoder.h5	Trained Keras decoder model (CVAE)
requirements.txt	Python dependencies
README.md	You're reading it!

🧠 Model Details
Model: Conditional Variational Autoencoder (CVAE)

Framework: TensorFlow / Keras

Dataset: MNIST (28×28 grayscale)

Trained using: Google Colab on T4 GPU

No pre-trained weights used (trained from scratch)

🌐 Live App
🔗 Click here to access the deployed app

📦 Install & Run Locally
bash
Copy
Edit
pip install -r requirements.txt
streamlit run streamlit_app.py
