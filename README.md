# Language Recognition Project

This project implements a machine learning model to detect the language of a given text. It uses Natural Language Processing (NLP) techniques and the Multinomial Naive Bayes algorithm to classify text into one of 22 different languages.

## Features

- Supports 22 different languages including:
  - English, Spanish, French, German, Chinese, Japanese, Korean
  - Hindi, Arabic, Russian, Thai, Tamil, and more
- High accuracy rate (95.78%)
- Simple text input interface
- Fast prediction

## Requirements

- Python 3.x
- pandas
- numpy
- scikit-learn

## Usage

1. Run the Jupyter notebook:
```bash
jupyter notebook Language_Recognition.ipynb
```

2. Follow the notebook cells to:
   - Load and preprocess the data
   - Train the model
   - Make predictions on new text

## Dataset

The project uses a dataset containing text samples from 22 different languages, with 1000 samples per language. The dataset is stored in `language.csv`.

## Model

The model uses:
- CountVectorizer for text feature extraction
- Multinomial Naive Bayes for classification
- Train-test split ratio of 67:33

## License

This project is licensed under the MIT License - see the LICENSE file for details. 