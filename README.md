# Sentiment Analysis on Amazon's Fine Food Reviews Dataset

This repository contains code and data for performing sentiment analysis on Amazon's Food Reviews Dataset using a RoBERTa-based model. The project is divided into two main parts: Exploratory Data Analysis (EDA) and Data Cleaning in `DataAnalyzer.ipynb`, and Sentiment Analysis Model Training and Inference in `SentimentAnalysisModel.ipynb`.

[**Click here to download the dataset:**](https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews)

## Project Structure

The project is organized as follows:

- `DataAnalyzer.ipynb`: Jupyter Notebook containing Exploratory Data Analysis (EDA) and Data Cleaning steps for the Amazon's Food Reviews Dataset. This notebook explores the dataset, handles missing values, and prepares the data for sentiment analysis.

- `SentimentAnalysisModel.ipynb`: Jupyter Notebook that focuses on sentiment analysis using pre-trained models from Hugging Face's Transformers library. It loads the cleaned dataset from `DataAnalyzer.ipynb` and performs sentiment predictions using RoBERTa-based models.

- `Data_for_model` directory consists of training and testing data after running `DataAnalyzer.ipynb`.  

## Usage

1. Clone this repository to your local machine:

2. Install the required dependencies. You can use `conda`:

3. Place the Amazon's Food Reviews Dataset CSV file (e.g., `Reviews.csv`) in the directory of the repo (download it from the link given above).

4. Open and run `DataAnalyzer.ipynb` to perform EDA and data cleaning. This will prepare the dataset for sentiment analysis.

5. Open and run `SentimentAnalysisModel.ipynb` to load the pre-trained RoBERTa-based model and perform sentiment predictions on the cleaned dataset.

6. `Cleaned_Data.csv` (exported after running `DataAnalyzer.ipynb`) contains the cleaned processed data. 


## Acknowledgments

- [Hugging Face Transformers](https://github.com/huggingface/transformers): For providing pre-trained language models and a convenient library for Natural Language Processing (NLP) tasks.

