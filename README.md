## Introduction
This project addresses the critical need for mental health monitoring in the digital age. A healthcare company aims to leverage social media analytics to detect stress patterns, understand prevalent triggers, and develop tailored interventions. By analyzing Reddit posts, this project offers a scalable NLP-based approach for stress detection.

## Objective
The primary goal is to design a machine-learning model that:
- Identifies stress indicators in social media articles.
- Assists healthcare providers in understanding population stress trends.
- Supports personalized mental health interventions.

## Dataset
- **Source**: Kaggle Stress Detection Dataset
- **Format**: CSV, with features separated by semicolons.
  
### Key Features:
- **Body_Title**: Contains unclean text of Reddit posts.
- **label**: Binary classification (1 = Positive Stress, 0 = Negative Stress).

## Methodology

### Data Preprocessing:
- Cleaning text (lowercasing, punctuation removal, etc.).
- Tokenization, stopword removal, and lemmatization.

### Feature Extraction:
- Using TF-IDF to transform text into numerical features.

### Model Training:
- Training regression and SVM models.
- Hyperparameter tuning for optimal performance.

### Evaluation:
- Assessing model accuracy and other performance metrics.

## System Pipeline
1. Data Extraction
2. Preprocessing
3. Feature Extraction
4. Model Training
5. Evaluation


## Usage
Clone this repository and run the notebook to reproduce results. Ensure the required libraries are installed (refer to `requirements.txt`).

## Dependencies
- Python
- Pandas
- NumPy
- Scikit-learn
- NLTK

## Future Work
- Expanding the dataset for improved generalization.
- Exploring deep learning approaches for enhanced accuracy.

## Data set link: https://www.kaggle.com/datasets/mexwell/stress-detection-from-social-media-articles/data
