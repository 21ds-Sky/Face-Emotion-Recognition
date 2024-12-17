Project Description
This project involves developing a deep learning model to detect real-time emotions of students through a webcam. The model provides aggregated feedback to instructors, enabling them to understand student engagement and comprehension based on their facial expressions and emotions.

The dataset comprises 48x48 pixel grayscale images of faces, pre-processed to ensure central alignment and consistent scaling. The task is to classify facial expressions into seven distinct categories:
0 = Angry, 1 = Disgust, 2 = Fear, 3 = Happy, 4 = Sad, 5 = Surprise, 6 = Neutral.

Training set: 28,709 examples
Test set: 7,178 examples
The model employs a Convolutional Neural Network (CNN) to analyze emotions accurately and efficiently.

Model Architecture
Convolutional Neural Network (CNN)
The chosen CNN model is designed to extract features and classify facial expressions effectively. Below is the high-level structure of the CNN:



Output
Model File: model.h5 (Contains the trained CNN model for facial emotion detection).
Live Feedback: Real-time emotion detection via webcam.
Media Files: Images and videos showcasing the emotion recognition output.
Conclusion
The model successfully classifies seven facial expressions: Angry, Disgust, Fear, Happy, Sad, Surprise, and Neutral.
Performance: The CNN model achieved a high accuracy of 73.40%, outperforming the ResNet model, which achieved only 63% accuracy.
Due to fewer samples for the emotions Disgust and Surprise, these emotions are harder to detect in live webcam scenarios.
The trained CNN model is capable of real-time face detection and emotion prediction for both video feeds and live webcam input.
