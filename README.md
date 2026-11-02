# Lifestyle-Based Weight Loss Prediction Using ANN

An Artificial Neural Network (ANN) project that predicts whether a person is likely to achieve their weight loss goal based on lifestyle habits.

## Overview

Lifestyle habits such as diet, exercise, sleep and stress can influence weight management. This project uses an Artificial Neural Network to analyze these factors and predict weight loss outcomes.

## Features Used

| Feature | Type | Description |
|---|---|---|
| `Diet Score` | Numeric | Diet habit score |
| `Exercise Hours` | Numeric | Daily exercise hours |
| `Sleep Hours` | Numeric | Daily sleep hours |
| `Stress Level` | Numeric | User's stress level |

**Target:** Weight Loss Outcome (Likely / Unlikely)

## How It Works

1. Create a lifestyle-based dataset using Pandas and NumPy.
2. Preprocess the dataset.
3. Build an Artificial Neural Network (ANN).
4. Use a Step Activation Function.
5. Train the model using a learning algorithm.
6. Evaluate the model's prediction accuracy.
7. Predict weight loss outcomes based on user inputs.

## Results

The model predicts two possible outcomes:

- Likely to Achieve Weight Loss
- Unlikely to Achieve Weight Loss

## Getting Started

**1. Install Dependencies**

```bash
pip install numpy pandas matplotlib scikit-learn tensorflow
```

**2. Run the Model**

Open the Python file or Google Colab notebook and execute the code cells.

## Predict Your Own Result

Enter the following lifestyle details:

- Diet Score
- Exercise Hours
- Sleep Hours
- Stress Level

The trained ANN model predicts whether the person is likely or unlikely to achieve their weight loss goal.

## Tech Stack

Python · Pandas · NumPy · TensorFlow · Keras · ANN

## Real-World Applications

- Fitness Tracking Apps
- Wellness Platforms
- AI Health Assistants
- Personalized Diet Recommendations

## Future Improvements

- Use a larger real-world dataset.
- Upgrade the Perceptron to a Multi-Layer Neural Network.
- Improve model performance.
- Develop a user-friendly prediction interface.
