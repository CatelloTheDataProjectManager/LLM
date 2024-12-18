# Large Language Models with SageMaker

<img src="https://github.com/CatelloTheDataProjectManager/NLP-with-SageMaker/blob/main/Amazon%20SageMaker.jpg" alt="Amazon SageMaker" width="500"/>
 
## Natural Language Processing

[View the Jupyter Notebook: Applying ML to an NLP](https://github.com/CatelloTheDataProjectManager/LLM-NLP-SageMaker/blob/main/Applying%20ML%20to%20an%20NLP.ipynb)


### Overview
This notebook guides you through applying machine learning (ML) to a natural language processing (NLP) problem using Amazon SageMaker's built-in `LinearLearner` algorithm. The goal is to predict the sentiment (positive or negative) of product reviews for an online retail store.

### Business Scenario
You work for an online retail store aiming to improve customer engagement by detecting negative reviews and assigning them to customer service agents. Your task is to use ML to detect negative reviews using a labeled dataset of product reviews.

### Dataset
The `AMAZON-REVIEW-DATA-CLASSIFICATION.csv` file contains actual product reviews with text and numeric data. Each review is labeled as positive (1) or negative (0). The dataset includes features such as `reviewText`, `summary`, `verified`, `time`, `log_votes`, and `isPositive`.

### Lab Steps
1. **Reading the dataset**: Load the dataset using the `pandas` library.
2. **Performing exploratory data analysis**: Analyze the target distribution and handle missing values.
3. **Text processing**: Remove stopwords and perform stemming using the `nltk` library.
4. **Splitting data**: Divide the dataset into training, validation, and test sets.
5. **Processing data**: Use pipelines and a `ColumnTransformer` to preprocess numerical and text features.
6. **Training a classifier**: Train a binary classifier using SageMaker's `LinearLearner` algorithm.
7. **Evaluating the model**: Assess the model's performance using metrics like binary classification accuracy.
8. **Deploying the model**: Deploy the trained model to an endpoint for real-time predictions.
9. **Testing the endpoint**: Send test data to the deployed endpoint and retrieve predictions.
10. **Cleaning up**: Delete the endpoint to avoid unnecessary charges.

## Extracting Text from Webpages and Images

[View the Jupyter Notebook: Extracting Text from Webpages and Images](https://github.com/CatelloTheDataProjectManager/LLM-SageMaker/blob/main/Extracting%20Text%20from%20Webpages%20and%20Images.ipynb)


### Overview
This lab guides you through extracting text from webpages using Beautiful Soup and from images using Amazon Textract. The extracted text will be organized into a pandas dataframe for further analysis.

### Lab Steps

1. **Extracting information from a webpage**: Use Beautiful Soup to scrape titles, authors, summaries, published dates, and hyperlinks from blog posts.
2. **Extracting text from images**: Utilize Amazon Textract to extract text from images, including those with tabular data.


