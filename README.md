# Emergency vs Non-Emergency Audio Classification using Deep Learning

**Introduction:**

Classifying audio signals as emergency or non-emergency can significantly enhance response times in critical situations, such as detecting distress calls, alarms, or other urgent sounds. Deep learning techniques can be effectively employed to analyze audio data, identifying patterns that distinguish between emergency and non-emergency situations. This project focuses on developing a deep learning model to classify audio recordings, ensuring that emergency sounds are quickly and accurately detected, thereby improving response efficiency and safety measures.

**Problem Statement:**

The objective of this project is to develop a deep learning model that classifies audio recordings into emergency and non-emergency categories. By training the model on a diverse dataset of audio signals, the neural network will learn to recognize distinctive features that indicate an emergency. 

**Dataset:**

The Dataset used for this project are the audio files containing records of Emergency (emergency.wav) vs Non-Emergency (non-emergency.wav)

**Project Description:**

• Utilized audio processing libraries such as Librosa and SciPy.

• Split audio data into consistent chunks to ensure uniform input for model training.

• Concatenated emergency and non-emergency audio chunks into a single dataset.

• Developed, compiled, and trained a deep learning model for audio classification.

• Implemented model checkpointing to load the best model.

• Achieved a model accuracy of 87%.

**Skills:** Deep Learning · Audio Classification · Librosa · SciPy · Model Checkpointing
