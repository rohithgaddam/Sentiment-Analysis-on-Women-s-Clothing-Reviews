# Sentiment-Analysis-on-Women-s-Clothing-Reviews

This project aims to analyze customer reviews of women's clothing products using various Natural Language Processing (NLP) techniques and machine learning models. We utilize VADER, RoBERTa, and a custom transform pipeline to classify the sentiment of the reviews.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Customer reviews provide valuable insights into product performance and customer satisfaction. This project leverages sentiment analysis to understand the opinions, emotions, and attitudes expressed in reviews of women's clothing products. By using VADER for rule-based sentiment analysis, RoBERTa for transformer-based sentiment classification, and a custom transform pipeline, we aim to provide accurate and nuanced sentiment insights.

## Features

- **VADER Sentiment Analysis:** Fast and efficient rule-based sentiment analysis.
- **RoBERTa Sentiment Classification:** Advanced transformer-based model for deeper sentiment understanding.
- **Custom Transform Pipeline:** Combines preprocessing steps and model predictions for robust sentiment analysis.
- **Data Visualization:** Graphical representation of sentiment distribution and key insights.

## Technologies Used

- **Python:** Main programming language.
- **NLTK:** Natural Language Toolkit for text processing.
- **VADER:** Rule-based sentiment analysis tool.
- **Transformers:** Hugging Face library for RoBERTa model.
- **Scikit-learn:** Machine learning library for building the custom transform pipeline.
- **Pandas:** Data manipulation and analysis.
- **Matplotlib/Seaborn:** Data visualization libraries.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/womens-clothing-sentiment-analysis.git
   cd womens-clothing-sentiment-analysis
   ```

2. Create a virtual environment and activate it:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Prepare the data:
   - Ensure your dataset of women's clothing reviews is in CSV format with at least one column for the review text.

2. Run the analysis:
   ```bash
   python sentiment_analysis.py --input_path path/to/your/reviews.csv --output_path path/to/save/results.csv
   ```

3. Visualize the results:
   ```bash
   python visualize_results.py --input_path path/to/save/results.csv
   ```


## Results

The project yields a detailed sentiment analysis of the reviews, including the proportion of positive, negative, and neutral sentiments. Visualizations help in understanding the distribution and intensity of sentiments across different products.

## Contributing

We welcome contributions to enhance the project. Please fork the repository and create a pull request with your changes. Ensure your code follows the existing style and include tests for new features.
