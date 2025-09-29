Online Student Learning Experience – Engagement Detection

OVERVIEW:

This project presents a novel model for evaluating student engagement and learning experience in online education using computer vision and deep learning.
The system analyzes real-time facial expressions to detect attentiveness and emotions during online lectures. To ensure reliability, only reviews from attentive students are included in sentiment analysis using the VADER tool.

By integrating facial expression analysis, eye-tracking technology, physiological sensors (e.g., heart rate variability, skin conductance), and Natural Language Processing (NLP), this model provides teachers with actionable insights into student engagement and emotions.


OBJECTIVES:

Measure real-time student engagement via facial expression recognition.

Perform sentiment analysis on feedback from attentive students.

Improve robustness by integrating multimodal data: facial cues, eye-tracking, and physiological signals.

Provide teachers with data-driven insights to adapt teaching strategies.

Enhance overall quality of online learning experiences.


METHODOLOGY:

Facial Expression Recognition

Uses OpenCV and a pre-trained CNN (Keras) model.

Detects emotions: angry, disgust, fear, happy, sad, surprise, neutral.

Real-time analysis from webcam/video feed.

Sentiment Analysis

Implements VADER (Valence Aware Dictionary and sEntiment Reasoner).

Filters out reviews from inattentive students to avoid bias.

Classifies feedback into Positive, Negative, or Neutral.


DATASET:

Trained on a dataset of student interactions and facial expressions (Udemy dataset).

Includes diverse emotional and attentional states for accuracy.


RESULTS:

Facial recognition model achieved 85% accuracy in classifying attention levels.

Neutral expressions dominated during real-time tests, with happy/sad variations showing engagement patterns.

Sentiment analysis produced more reliable feedback by excluding inattentive students’ reviews.


FUTURE SCOPE:

Integration of eye-tracking and physiological sensors for richer engagement metrics.

Personalized feedback loops for students based on attention and sentiment.

Automated real-time feedback for teachers to adapt lectures instantly.


TECH STACK:

Python

OpenCV – Real-time video analysis

Keras / TensorFlow – CNN for facial expression recognition

spaCy – NLP processing

VADER – Sentiment analysis


REFERENCES:

Published in: Journal of Information Systems Engineering and Management (JISEM), 2025
Link to Article: https://www.jisem-journal.com/index.php/journal/article/view/5786
