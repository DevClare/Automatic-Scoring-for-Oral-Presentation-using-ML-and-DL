This project implements machine learning (SVM, Random Forest) and deep learning (CNN, YOLOv8) approaches to automatically score oral presentations using audio features and spectrogram images.

📌Features
Extracted Audio Features: MFCC, Chroma, Pitch, Intensity, Tempo, Zero-Crossing Rate Mean, Spectral Centroid Mean
Human Evaluation Scores: Volume, Pace, Tone, Pronunciation, Vocal Variety, Vocal Control, Fluency

🖥️Models Implemented:
Support Vector Machine (SVM)
Random Forest (RF)
Convolutional Neural Network (CNN)
YOLOv8 Classification

📂Dataset

CSV File: AudioScoreLatest.csv(Contains human evaluation scores), aggregated_results_mean.csv(Contains extracted audio features)

Spectrogram Images: .jpg files generated from audio samples.

🖋️Scores are categorized into three labels:
0 → Bad (1–2)
1 → Neutral/Good (3)
2 → Very Good (4–5)
