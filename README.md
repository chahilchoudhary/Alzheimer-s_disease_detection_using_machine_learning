# Alzheimer-s_disease_detection_using_machine_learning


Alzheimer's Disease (AD) is a progressive neurological disorder affecting memory, thinking, and behavior. One of the early signs of cognitive impairment linked to Alzheimer's is changes in handwriting. This project taps into machine learning techniques to analyze handwriting samples and predict the onset or presence of Alzheimer's Disease.

Dataset
The dataset encompasses handwriting samples from:

Individuals diagnosed with Alzheimer's Disease
Healthy controls
Features derived from these samples include, but are not limited to:

Pen pressure
Writing speed
Letter spacing
Size of characters
Variability in letter formation
Methodology
Data Preprocessing: Handwriting samples are digitized and processed to extract relevant features that might indicate cognitive decline.

Feature Extraction: Techniques like image processing and time-series analysis are used to derive key characteristics from the handwriting samples.

Model Building: Various machine learning models, including Support Vector Machines (SVM), Decision Trees, Random Forests, and Neural Networks, have been explored to determine which best captures the nuances in the handwriting of individuals with Alzheimer's.

Evaluation: Models are assessed based on accuracy, precision, recall, and the area under the ROC curve. This ensures that the models not only predict accurately but also minimize false positives and negatives.

Deployment: The highest-performing model is integrated into an application where users can upload a handwriting sample and receive a prediction promptly.
