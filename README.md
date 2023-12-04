<div align="center">
  <h1>Gender Prediction from Text</h1>
  <p>Predicting gender based on text using machine learning models.</p>
</div>

## About Us
👨🏽‍💻 Omer Tzroya,
Third year Computer Science students at H.I.T.
I really like Python, I have a passion for experimenting with new things and interesting technologies.
This is our final project in the machine learning course.

## Description
📚 This project focuses on predicting the gender of the author based on textual content. The task involves training machine learning models to classify whether a given text is written by a male or female author. The primary metric used to evaluate the model's performance is the F1-score, taking into account both precision and recall.

## Tools and Features
🛠️ This project is built using the following materials and tools:
- Python
- Libraries: NumPy, Pandas, scikit-learn, and re (for regular expressions)
- Text analysis techniques integrated with machine learning models
- Tokenized the text to vectors
- Implementing a correct machine learning flow according to the steps.
    
<p align="left"> <a href="https://pandas.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="pandas" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> <a href="https://scikit-learn.org/" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" alt="scikit_learn" width="40" height="40"/> </a> </p>


🔍 The project adheres to certain restrictions:
- Limited to the mentioned libraries, no external modules
- No external files or lists of words
- The data is provided in CSV format for training and testing

## Results
📊 The model's performance is evaluated using the F1-score.<br/>
The F1-score is calculated for both male and female classes, and the average F1-score is computed to<br/>
provide an overall assessment of the model's effectiveness.<br/>
The best model we tested is the Perceptron , with F1 score of 0.73


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

Feel free to contribute to the project by opening issues or creating pull requests. 

## License

![GitHub](https://img.shields.io/github/license/ItsAlexanderPopov/Simon-game)


---
