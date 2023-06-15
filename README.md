# Stress Detection from Sleep Noises
This project aims to develop a stress detection system using sleep noises. The goal is to analyze audio recordings during sleep and accurately identify stress levels based on the audio patterns and characteristics.

## Features
- Sleep audio data collection: The project includes a data collection module to gather sleep audio recordings from various individuals.
- Preprocessing: The collected audio data undergoes preprocessing to remove noise, artifacts, and irrelevant segments, ensuring the quality and relevance of the data.
- Feature extraction: Relevant features are extracted from the preprocessed audio signals, considering characteristics such as pitch, frequency distribution, and temporal patterns.
- Machine learning models: The extracted features are used to train machine learning models, such as deep neural networks or ensemble methods, to classify and detect stress levels accurately.
- Model evaluation: The performance of the trained models is assessed using appropriate evaluation metrics, such as accuracy, precision, recall, and F1-score.
- Stress level prediction: Once the models are trained and validated, they can be used to predict stress levels in real time by analyzing sleep noises.

## Requirements
- Language: Python 3.10, Kotlin
- Libraries: TensorFlow 2.6.2, sci-kit-learn, NumPy, SciPy, pandas, ffmpeg, and any other necessary libraries for audio processing and machine learning.

## Usage
- Install the required dependencies mentioned above.
- Prepare the sleep audio dataset or use the provided dataset.
- Run the preprocessing script to clean and preprocess the audio data.
- Extract relevant features from the preprocessed audio using the feature extraction script.
- Split the dataset into training and testing sets.
- Train and evaluate the machine learning models using the prepared dataset.
- Use the trained models to predict stress levels from new sleep audio recordings.

## Future Enhancements
- Integration with sleep monitoring devices or applications to collect sleep data more conveniently.
- Implement real-time stress level detection during sleep for immediate feedback and intervention.
- Improve the accuracy of stress detection by incorporating additional features or data modalities.
- Develop a user-friendly interface or application for easy deployment and usage.

## Contributors
1. M017DSX2462 – Kumaras Gideon Sitorus – Institut Teknologi Bandung - Machine Learning
2. M017DKX4134 – Ryo Richardo – Institut Teknologi Bandung - Machine Learning
3. C017DKX4092 – Ramadhana Bhanuharya Wishnumurti – Institut Teknologi Bandung -  Cloud Computing
4. C166DSX2205 – Timothy Bagaskara Haullussy – Universitas Diponegoro - Cloud Computing
5. A309DKY3878 – Fitri Aulia Sanni – Universitas Pendidikan Indonesia - Mobile Development
6. A210DSX3380 – Muhammad Ariq Daffa – Universitas Jenderal Soedirman - Mobile Development

