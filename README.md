# Learning Disability Detector Using ML

This project aims to develop a machine learning model to detect learning disabilities in students based on various academic and behavioral features.

## Overview
Learning disabilities can significantly impact a student's academic performance and overall well-being. Early detection and intervention are crucial to providing appropriate support and accommodations. This project utilizes machine learning techniques to analyze student data and identify patterns indicative of learning disabilities.

## Features
The model considers the following features for prediction:
- Age
- Grade level
- Gender
- Reading age assessment
- Math score
- Reading fluency (WPM)
- Completion rate (average)
- Time per task (average)
- Distraction count (average)

## Data
The dataset used for training and testing the model contains anonymized student records with features mentioned above. The dataset is preprocessed to handle missing values, encode categorical variables, and split into training and testing sets.

## Models
Three machine learning models are implemented for learning disability detection:
- Logistic Regression
- Support Vector Machine (SVM)
- Random Forest

## Evaluation
The performance of each model is evaluated using metrics such as accuracy, precision, recall, and F1-score. Cross-validation techniques are employed to ensure robustness and reliability of the results.

## Usage
To use the learning disability detector:
1. Clone this repository to your local machine.
2. Install the required dependencies listed in the `requirements.txt` file.
3. Run the provided Python scripts or notebooks to train and test the models.
4. Evaluate the model performance and adjust parameters as needed.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
