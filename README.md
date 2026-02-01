# HealthTech-Pneumonia-Detection
HealthTech/Medical Imaging : AI-Assisted Diagnostics- Automated Pneumonia Detection

Problem Statement:
Domain: HealthTech / Medical Imaging Title: Al-Assisted Diagnostics: Automated
Pneumonia Detection Theme: Healthcare & Computer Vision
Description: Pneumonia accounts for over 15% o f all deaths of children under five years
old globally. Rapid and accurate diagnosis i s critical, but expert radiologists are often
overworked, leading to delays. Participants are tasked with developing a Computer
Vision model that acts as a "Second Opinion" tool, automatically flagging Chest X-Rays
that show signs of Pneumonia to prioritize them for doctor review.
Challenges:
False Negative Minimization:
In healthcare, missing a sick patient (False Negative) i s worse than flagging a healthy one
(False Positive. Participants must tune their model to maximize Recall/Sensitivity.
Explainability (Heatmaps):
The model cannot just say "Yes/No." I t must generate a Class Activation Map (CAM) or
heatmap showing where in the lungs the infection was detected, so the doctor can verify
it.
Data Provided:
A folder of 5,000 anonymized Chest X-Ray images (JPEG format).
A CSV file mapping Image IDs to labels: 0: Normal, 1: Bacterial Pneumonia, 2: Viral
Pneumonia.
Expected Outcomes:
A classification model with high Recall statistics.
AUl where a doctor can upload an X-ray and see the image with the "infected area"
highlighted in red.
Judge's Note: This appeals to students interested in Deep Learning (CNNs). It is
"Intermediate" because pre-trained models (like ResNet) make this achievable in 24
hours, but getting high accuracy on noisy medical data i s challenging.
