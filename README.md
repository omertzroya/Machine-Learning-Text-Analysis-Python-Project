<div align="center">
 
  <h1>🌟 Gender Prediction from Text🌟<br/> 🕵️‍♀️🕵️‍♂️</h1>
  <p>Predicting gender based on text using machine learning models.</p>
</div>

## Table of Contents
- [Description](#description)
- [Tools and Features](#tools-and-features)
- [Results](#results)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Description
📚 This project focuses on predicting the gender of the author based on textual content. The task involves training machine learning models to classify whether a given text is written by a male or female author. The primary metric used to evaluate the model's performance is the F1-score, taking into account both precision and recall.

## Tools and Features
🛠️ This project is built using the following materials and tools:
- Python
- Libraries: NumPy, Pandas, scikit-learn, and re (for regular expressions)
- Text analysis techniques integrated with machine learning models
- Tokenized the text to vectors

🔍 The project adheres to certain restrictions:
- Limited to the mentioned libraries, no external modules
- No external files or lists of words
- The data is provided in CSV format for training and testing

## Results
📊 The model's performance is evaluated using the F1-score. The F1-score is calculated for both male and female classes, and the average F1-score is computed to provide an overall assessment of the model's effectiveness.

## Getting Started
To get started with the project, follow these steps:
1. Clone this repository to your local machine.
2. Navigate to the project directory.
3. Open the provided Jupyter Notebook (`Assignment3-text-analysis.ipynb`) to see the code and explanations.

## Usage
1. Load the training data from `annotated_corpus_for_train.csv`.
2. Preprocess the text data using various techniques.
3. Train machine learning models (such as Perceptron, LinearSVC, DecisionTreeClassifier, etc.).
4. Evaluate the models using cross-validation and calculate the average F1-score.
5. Use the trained model to predict the gender of test examples from `corpus_for_test.csv`.

## Contributing
🤝 Contributions are welcome! If you'd like to contribute to this project, follow these steps:
1. Fork this repository.
2. Create a new branch for your feature (`git checkout -b feature/YourFeatureName`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push the changes to your branch (`git push origin feature/YourFeatureName`).
5. Open a pull request.

## License
📝 This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
