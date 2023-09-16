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
I will perform Tokenization to split the sentences and words from the body of the text and create a sparse matrix to get the final output.
Here are some snapshots of my project.

MAIN CODE: 

![Screenshot 1](https://github.com/sukuberger/Restaurant-Review-Analysis/assets/109449780/d4a9bb09-7747-4621-8ca2-08018c3385bb)

![Screenshot 2](https://github.com/sukuberger/Restaurant-Review-Analysis/assets/109449780/d5ae965a-73cf-4ab5-9b35-d232cbe69736)


![Screenshot 3](https://github.com/sukuberger/Restaurant-Review-Analysis/assets/109449780/4d19f13a-4768-46c0-a81b-64262547be41)


![Screenshot 4](https://github.com/sukuberger/Restaurant-Review-Analysis/assets/109449780/163cecf3-6ffc-4b5f-a968-7ba226726d76)



![Screenshot 5](https://github.com/sukuberger/Restaurant-Review-Analysis/assets/109449780/668fc06d-d2e0-4d06-808e-64ccd9b9d017)

OUTPUT:


![Screenshot 6](https://github.com/sukuberger/Restaurant-Review-Analysis/assets/109449780/64edab7d-1588-4778-a52c-19edc121be39)


![Screenshot 7](https://github.com/sukuberger/Restaurant-Review-Analysis/assets/109449780/ca686ed4-9593-4695-a8b7-6a8bd16e5ce4)


![Screenshot 8](https://github.com/sukuberger/Restaurant-Review-Analysis/assets/109449780/2ba3ee34-c2f9-48a8-b8f6-6e07a40485c6)



















