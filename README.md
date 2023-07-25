# Author: Srinivas Rahul

## Questions
<br/>	Topic Modelling using LDA<br/>	

## Dataset
<br/>	Dataset we are using in this notebook: Here, I have used the open-source Twitter tweet dataset provided in Kaggle <br/>

## Problem Statement<br/>
Topic Modelling using Latent Dirichlet Allocation.<br/>

## Assumptions of LDA for Topic Modelling:<br/>

- Documents with similar topics use similar groups of words<br/>
- Latent topics can then be found by searching for groups of words that frequently occur together in documents across the corpus
Documents are probability distributions over latent topics, which signifies that a document will contain more words about a specific topic.<br/>
 
# Brief explanation here:<br/>
## Objective: <br/>
## Assignment: Reddit API<br/>
- Define your own topics and select a few popular threads from those topics on Reddit<br/>
- Retrieve the comment data using Praw API<br/>
- Group comments together as one corpus<br/>
- Perform Topic Modeling using LDA with various n topics.<br/>

## Data
Source data from public data set on the Twitter dataset.<br/>

## Approach 
- Imported Reddit data from 3 topics.<br/>
- Used tf-idf for LDA. It can be used to visualize topics or to choose the vocabulary. 
"It is often computationally expensive to use the entire vocabulary. Choosing the top V words by TFIDF is an effective way to prune the vocabulary
- After visualization, we can conclude that spam text has more words and characters than Ham text. <br/>
- pre-processed data using stemming and lemmatization before feeding data into LDA.


## Improvements
- Improved LDA, including stemming and lemmatization. Removed all the uncommon words after topic modeling using TF-IDF. <br/>
# Methods Used
- TF-IDF
- Latent Dirichlet Allocation

## Challenges
- Faced challenges while setting parameters of LDA. <br>

## Extension plan
- I would like to use LDA for data classification <br>

## Conclusion
- Latent Dirichlet Allocation (LDA) does two tasks: it finds the topics from the corpus and at the same time, 
assigns these topics to the document present within the same corpus. <br>

## Colab Files<br/>
https://colab.research.google.com/drive/1PcoBB4X2AV5GTHOU4T-7wOBayHZEwAnR?usp=sharing - LDA File.<br/>






