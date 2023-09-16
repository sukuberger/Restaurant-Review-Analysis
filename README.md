# Restaurant-Review- Sentimental Analysis

Normally, a lot of businesses are remained as failures due to lack of profit, lack of proper improvement measures. Mostly, restaurant owners face a lot of difficulties to improve their productivity. This project really helps those who want to increase their productivity, which in turn increases their business profits. This is the main objective of this project.

What the project does is that the restaurant owner gets to know about drawbacks of his restaurant such as most disliked food items of his restaurant by customer’s text review as well as comes to know about the signature food items by positive reviews of his customers which is processed with ML classification algorithm and application of Artificial Intelligence(AI).
Technology Used: Python and Machine Learning.
 I will be using natural language processing to act. For this purpose, we need to gather lots of review data in paragraphs.
 I am importing the data set, which is in TSV format. There are many reviews, and their categories are mentioned as 0 or 1, separated by tab space. Here, zero signifies a bad review, and one represents a good review. I am importing the necessary modules to work on NumPy arrays and the data frame.

import numpy as np
import pandas as pd

I will convert the TSV format of data into CSV format. TSV stands for Tab-separated values while CSV stands for comma-separated values. 
dataset = pd.read_csv('Restaurant_Reviews.tsv',delimiter='\t')
I will clean the text because there are many unnecessary things, such as punctuation marks. They will increase the size of the words and decrease the algorithm's efficiency.

I will perform Stemming to reduce the word to its word stem and convert each word into lowercase. There might be a chance someone has written a comment in the capital letter, and someone has written the same word in the small letter. In Python, capital and small letters are treated differently, so we must convert similar words into lowercase letters.
I will perform Tokenization to split the sentences and words from the body of the text.

Then, I will make the back of words via sparse matrix taking all the different words reviewed in the data set without repeating terms.





