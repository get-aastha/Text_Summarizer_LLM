## News summarization using Python, OpenCV, Streamlit, and Txtai on the Google Colab platform.

This project includes using Google Colab in collaboration with Streamlit to summarize text through file upload. **Project report included.**

## Software Specification

i.     Programming Language:
Python (version 3.6 or later recommended)

ii.    Libraries:
1. txtai (v0.8.1 or later): For deploying your summarization model as an API.
2. streamlit (v1.14 or later): For building the web application interface.
3. transformers (v4.25 or later): Provides pre-trained models for text summarization tasks (if not using a custom model).
4. opencv-python (v4.8.0 or later): For image processing tasks (if your project involves summarizing news articles with images).

## Instructions

1. Upload the Colab file on your Google Colab account and run all the code blocks.
2. Once you finish exceuting the last block i.e **!streamlit run app.py & npx localtunnel --port 8501**, it will generate a link labeled 'your url is'
3. Click on the url. You will be redirected to a local tunnel webpage asking you for a pass.
4. In your colab file, when you run the second last block i.e **!wget -q -O - ipv4.icanhazip.com**, you would have gotten an ip address as output. Paste this ip adrress in the local tunnel website and hit Enter.
5. Tadaaa!! Streamlit is now running and you can summarize your text/documents.

## Screenshots

![image](https://github.com/get-aastha/text_summarizer/assets/108509128/2d7b0730-09c3-49d9-9d20-8edddcd62401)
![image](https://github.com/get-aastha/text_summarizer/assets/108509128/393a58c6-3fd9-4bc1-b5ed-e16994c12db7)
![image](https://github.com/get-aastha/text_summarizer/assets/108509128/a24cb99f-7799-412d-8b1f-8ae874cf2a37)
