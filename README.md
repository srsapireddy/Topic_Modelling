# icp-6-srsapireddy
icp-6-srsapireddy created by GitHub Classroom

# ICP-6

#### Complete the following:
```
Name: Srinivas Rahul Sapireddy 
Email: ssdx5@umsystem.edu
```
---
```
Individual Submission
```

## Questions
<br/>	Topic Modelling using LDA<br/>	

## Dataset
<br/>	Dataset we are using in this notebook: Here I have used the open-source twitter tweet dataset provided in kaggle<br/>

## Problem Statement<br/>
Topic Modelling using Latent Dirichlet Allocation.<br/>

## Assumptions of LDA for Topic Modelling:<br/>

- Documents with similar topics use similar groups of words<br/>
- Latent topics can then be found by searching for groups of words that frequently occur together in documents across the corpus
Documents are probability distributions over latent topics which signifies certain document will contain more words of a specific topic.<br/>

### SUBMIT PYTHON NOTEBOOK FILE (ipynb files)
<br/>
 
# Write brief explanation here:<br/>
## Objective: <br/>
## Assignment: Reddit API<br/>
- Define your own topics and select a few popular threads from those topics on Reddit<br/>
- Retrieve the comment data using Praw API<br/>
- Group comments together as one corpus<br/>
- Perform Topic Modeling using LDA with various n topics.<br/>

## Data
Source data from public data set on twitter dataset.<br/>

## Approach 
- Imported reddit data from 3 topics.<br/>
- Used tf-idf for LDA. It can be used to visualize topics or to chose the vocabulary. 
"It is often computationally expensive to use the entire vocabulary. Choosing the top V words by TFIDF is an effective way to prune the vocabulary
- After visualize we can conclude that spam text has more words and characters as compare to Ham text. <br/>
- pre-preocessed data using stemming and lemmatization before feeding data into LDA.


## Achievement 
- Improved LDA including stemming and lemmatization. Removed all the uncommon words after topic modelling using TF-IDF. <br/>
# Methods Used
- TF-IDF
- Latent Dirichlet Allocation

## Challenges
- Faced challenges while setting parameters of LDA. <br>

## Extension plan
- I would like to use LDA for data classification <br>

## Conclusion
- Latent Dirichlet Allocation (LDA) does two tasks: it finds the topics from the corpus, and at the same time, 
assigns these topics to the document present within the same corpus. <br>

## Individual Submission 
- Srinivas Rahul Sapireddy<br/>

## ICP-6 Colab Files<br/>
https://colab.research.google.com/drive/1PcoBB4X2AV5GTHOU4T-7wOBayHZEwAnR?usp=sharing - LDA File.<br/>






