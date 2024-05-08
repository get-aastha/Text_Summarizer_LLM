## News summarization using Python, OpenCV, Streamlit, and Txtai on the Google Colab platform.

This project includes using Google Colab in collaboration with Streamlit to summarize text through file upload. Project report included.

## SOFTWARE SPECIFICATION

### 1. Backend (Running on Google Colab):
i.     Programming Language:
Python (version 3.6 or later recommended)

ii.    Libraries:
•	txtai (v0.8.1 or later): For deploying your summarization model as an API.
•	streamlit (v1.14 or later): For building the web application interface.
•	transformers (v4.25 or later): Provides pre-trained models for text summarization tasks (if not using a custom model).
•	opencv-python (v4.8.0 or later): For image processing tasks (if your project involves summarizing news articles with images).

iii.     Text Summarization Model:
You can choose a pre-trained model from transformers (e.g., BART, T5) or train your own model using libraries like transformers or deep learning frameworks (TensorFlow, PyTorch).


### 2. Frontend (Web Application):
i. Libraries:
Streamlit (same version as backend) handles the web app development within Python. No separate frontend framework is needed.

ii. Local Tunnel Tool (on your local machine - Optional):
A local tunnel tool like ngrok or Localtunnel is needed if you want to share your Streamlit app running on Colab publicly over the internet.

