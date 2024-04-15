# Twitter Sentiment Analysis

## Overview
Twitter Sentiment Analysis is a project that aims to classify tweets as either positive or negative based on their content. It utilizes natural language processing (NLP) techniques and a logistic regression model for classification. The project includes data processing, model training, evaluation, and future predictions.

## Installation
To run this project, you need to have Python installed on your system along with the following dependencies:

- numpy
- pandas
- nltk
- scikit-learn

You can install these dependencies via pip:

```bash
pip install numpy pandas nltk scikit-learn
```

Additionally, you need to download the NLTK stopwords corpus by running the following command:

```bash
python -m nltk.downloader stopwords
```

## Usage
1. Clone the repository:

```bash
git clone https://github.com/your_username/twitter-sentiment-analysis.git
```

2. Navigate to the project directory:

```bash
cd twitter-sentiment-analysis
```

3. Run the main Python script:

```bash
python main.py
```

## Data Processing
- The project loads Twitter data from a CSV file into a pandas DataFrame.
- Basic exploratory data analysis is conducted to check for missing values and understand the distribution of target values.
- Text data is preprocessed, including stemming to reduce words to their root form.

## Model Training
- The dataset is split into training and testing sets using train_test_split from scikit-learn.
- Text data is converted into numerical form using TF-IDF vectorization.
- A logistic regression model is trained on the training data.

## Model Evaluation
- The accuracy of the trained model is evaluated using both training and testing data.
- The trained model achieves an accuracy score of approximately 81% on the training data and 78% on the testing data.

## Saving the Model
- The trained logistic regression model is saved using pickle for future use.

## Future Predictions
- The saved model can be loaded and used to make predictions on new data.
- An example of using the model to classify a new tweet is provided.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contribution
Contributions are welcome! Please create a new issue or submit a pull request for any enhancements or bug fixes.

## Support
For any questions or support, please contact [asrajendrayadav@gmail.com].

## Acknowledgements
We would like to thank the open-source community for their valuable contributions and the developers of the libraries used in this project.
