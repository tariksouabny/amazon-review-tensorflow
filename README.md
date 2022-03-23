# Amazon Rating Predictor Based on Written Review
## Made with Python, SciKit-Learn, Keras, and TensorFlow
<img src="https://images.unsplash.com/photo-1557899563-1940fc95709c?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=871&q=80" alt="Picture of Amazon Boxes">

## Summary
This is a model based using Python and the machine learning libraries above to predict the rating of an Amazon review based on a written review. The data came in the form of CSV data with various data features related to Amazon products.

Using a SciKit-Learn based model, a **mean accuracy of 77%** was reached. With a deep Recurrent model, however, only got **about 55%** on a test. Nonetheless, the machine learning models were able to take in a sequence of data and learn patterns to classify the text into categories.

## Attached Files
The files attatched are the `requirements.txt`, `amazon_reviews_notebook.ipynb`, which is the main notebook used to analyze and clean the data as well as create and train the models. Also, `amazon_reviews_data.zip` is attached. This file is the zip encoded form of the CSV data. In the notebook, the zip data was unpacked and subsequently analyzed with Pandas and Numpy and Plotly.

## Preview
To preview the Python code, open the main notebook file (`amazon_reviews_notebook.ipynb`)

## Key Insights
In making this project over the course of a few weeks, there were a few key insights that I gained:
 * Use data in any format, including zip encoded
 * How to use Pandas to manipulate and analyze tabular data
 * Using Plotly to use plots to notice any bias in the data
 * How to use documentation efficiently. Throughout this project, I learned that I didn't have to code every single line of code from scratch, but could rely on other sources to learn how to use new tools.

Overall, this project helped teach me learn how to independently pursue a project and build a full application for machine learning; I learned how to engineer my way through a project even when I didn't know everything at the moment, as well as building self-discipline to keep working when motivation ran low. Overall, this helped me grow as a developer! 

## Installation
To install the attahed files, run  
```bash
git clone https://github.com/tariksouabny/amazon-review-tensorflow.git
```

