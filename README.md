# Automate-Grading-Test-NART

This project focuses on the automated grading of premorbid ability tests, specifically reading tasks measured by the National Adult Reading Test (NART). 

The goal is to classify the correct pronunciation of words to assess cognitive ability automatically.




<br>

**Dataset**

This project uses a dataset of audio samples where participants are asked to pronounce a list of 5o words by the National Adult Reading Test (NART). Each sample is labeled as either "correct" or "incorrect" based on the pronunciation accuracy.

Note: The dataset is not publicly available. Please ensure you have the appropriate permissions to use the dataset or collect your own data for testing the model.



<br>

**Model Details**

The model is built using Keras with a Convolutional Neural Network (CNN) architecture. 

The input to the model is a Mel-spectrogram of the audio, which represents the frequency spectrum over time.



<br>

**Model Highlights**

Preprocessing: Converts audio to Mel-spectrogram features.

Architecture: RCNN and Transformer layers to capture spatial patterns in the spectrogram.

Evaluation: Metrics such as accuracy, precision, and recall are used to evaluate model performance.



<br>

**requirements.txt**

Keras==2.4.3

tensorflow==2.5.0

numpy==1.19.5

pandas==1.2.3

librosa==0.8.0



