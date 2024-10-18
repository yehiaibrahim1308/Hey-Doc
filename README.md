# Hey-Doc Medical Chatbot

Hey Doc is a medical chatbot designed to provide constant medical assistance, reduce the need for unnecessary medical visits, and offer support for individuals with social anxiety. This platform integrates machine learning, deep learning, and various APIs to deliver secure mental health sessions, medical inquiries, emotional support, and diagnostic predictions.    
     
# Project Details
## Aim 
To develop a medical chatbot that acts as a permanent companion, easing the burden of medical visits and assisting people suffering from social anxiety.
## Objectives
Secure Mental Sessions
Diagnosis
Emotional Support
Medical Inquiries

## technologies and frameworks used:


### Primary Technologies
- Languages: Python,HTML,CSS,JS.
- DBMS: MongoDB
### Main Frameworks & Tools
- Scikit-learn: Machine learning algorithms
- Pandas: Data manipulation
- Flask: Backend management and web design
- Elevenlabs API & Google API: Text-to-Speech and Speech-to-Text functionalities
- PubMed API: Access to medical articles
- TensorFlow: Deep learning models
- Transformers: Pretrained models for NLP
### Algorithms & Techniques
- Logistic Regression: For diagnostic classification
- PCA (Dimensionality Reduction): For reducing dataset complexity
- Tfidfvectorizer & Cosine Similarity: For determining similarity in user queries


## Features Provided

### Medical Diagnosis
- Dataset: Comprises 42 diagnoses (e.g., GERD, fungal infections, allergies) with features representing symptoms and diagnosis as the target.
### Emotional Support
- Handles various emotional states like sadness, anxiety, loneliness, anger, grief, stress, and fear.
### Medical Inquiry System
- A question-answering system that provides responses based on a dataset of medical-related questions and keywords.




## Quality Attributes

|Attribute	| Description |
| -------------- | -------------- | 
|Performance	 | Users receive a response within 2-3 seconds for a seamless experience.|
|Security	| User data is protected through strong encryption and secure communication protocols.|
|Maintainability	| The system is built with modular, well-documented code for easy updates and scalability.|
|Medical Accuracy	| Responses are backed by an extensive medical knowledge base, ensuring the chatbot's reliability.|
|Usability	| The intuitive interface and clear instructions make it easy for users to interact with Hey Doc.|





## implementation highlights


- Voice Tone Analysis:

Uses LSTM and librosa for tone analysis
Incorporates hubert-base-speech-emotion-recognition for emotion detection

- Mental Health & Emotional Support:

Sentiment analysis through twitter-roberta-base-sentiment-latest
Similarity detection with paraphrase-MiniLM-L6-v2
DialoGPT for handling non-health related topics

- Symptom Diagnosis:

spaCy for symptom tokenization and extraction
Fuzzy Matching for symptom comparison
Logistic Regression for classification and diagnosis

- Medical Question Answering:

Uses TF-IDF for similarity scoring
Searches medical articles using the PubMed API
Implements BioBERT for keyword extraction and answer generation




# Video documentation of the project

The voice in the video belongs to my project mate, Noor, because my microphone was broken 

https://github.com/user-attachments/assets/4537b6d1-5dca-47b8-8e2f-470f90da0fe3

# Conclusion

Hey Doc is a cutting-edge medical chatbot that provides reliable, fast, and secure healthcare assistance. By offering medical inquiries, emotional support, and diagnostic predictions, it has the potential to empower individuals to manage their health better and reduce their reliance on in-person visits. Built with machine learning and deep learning technologies, Hey Doc prioritizes security, performance, and medical accuracy, making it a promising tool for both patients and healthcare providers.



