### Intelligently Extract text from Document Web App using OCR and NER

In this course you will learn how to develop customized Named Entity Recognizer. The main idea of this course is to extract entities from the scanned documents like invoice, Business Card, Shipping Bill, Bill of Lading documents etc. However, for the sake of data privacy we restricted our views to Business Card. But you can use the framework explained to all kinds of financial documents. Below given is the curriculum we are following to develop the project.

To develop this project we will use two main technologies in data science are,

- Computer Vision
- Natural Language Processing

In Computer Vision module, we will scan the document, identify the location of text and finally extract text from the image. Then in Natural language processing, we will extract the entitles from the text and do necessary text cleaning and parse the entities form the text.

Python Libraries used in Computer Vision Module.

- OpenCV
- Numpy
- Pytesseract

Python Libraries used in Natural Language Processing

- Spacy
- Pandas
- Regular Expression
- String

As are combining two major technologies to develop the project, for the sake of easy to understand we divide the course into several stage of development.

Stage -1: We will setup the project by doing the necessary installations and requirements.

Install Python

Install Dependencies

Stage -2: We will do data preparation. That is we will extract text from images using Pytesseract and also do necessary cleaning.

Gather Images

Overview on Pytesseract

Extract Text from all Image

Clean and Prepare text

Stage -3: We will see how to label NER data using BIO tagging.

Manually Labeling with BIO technique

B - Beginning

I  -  Inside

O - Outside

Stage -4: We will further clean the text and preprocess the data for to train machine learning.

Prepare Training Data for Spacy

Convert data into spacy format

Stage -5: With the preprocess data we will train the Named Entity model.

Configuring NER Model

Train the model

Stage -6: We will predict the entitles using NER and model and create data pipeline for parsing text.

Load Model

Render and Serve with Displacy

Draw Bounding Box on Image

Parse Entitles from Text

Finally, we will put all together and create document scanner app.

Are you ready !!!

Let start developing the Artificial Intelligence project.

COURSE URL: https://www.udemy.com/course/business-card-reader-app/?referralCode=CBF4B439BDEF5F8AB0DB
