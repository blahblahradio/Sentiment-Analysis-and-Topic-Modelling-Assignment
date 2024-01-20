# Sentiment Analysis and Topic Modelling Report

## 1. Sentiment Analysis (3pts)

### Dataset Overview
For sentiment analysis, we utilized the IMDb dataset, consisting of movie reviews stored in a .csv file. The dataset includes two attributes:

- **review:** The text of specific movie reviews.
- **sentiment:** Categorized as either positive or negative.

IMDb, the Internet Movie Database, provided a comprehensive source of information on movies, television series, and more.

### Task Execution
Our team successfully completed the following tasks:

1. **Developed a Feedforward Neural Language Model:** We trained a feedforward neural language model from scratch, predicting sentiment scores (positive or negative) based on movie reviews. The dataset was split into an 80-20 train-validation dataset at random. The neural network was designed to accept inputs either as word embeddings (with a vector dimension of 100) or specific features, depending on preferences. Appropriate pre-processing steps were implemented.

2. **Evaluated Model Performance:** The trained model's performance was evaluated by calculating precision, recall, and F1-score measurements on the validation dataset.

## 2. Topic Modelling (3pts)

### Dataset Overview
Our topic modelling analysis focused on news headlines from the Australian news source ABC, stored as a .csv file. The dataset includes two attributes:

- **publish date:** Date of publishing in yyyyMMdd format.
- **headline text:** Text of the headline in ASCII, English, lowercase.

This corpus encompasses over one million news articles published by ABC over a nineteen-year period.

### Task Execution
Our team successfully accomplished the following tasks:

1. **Applied Latent Semantic Analysis (LSA) and Latent Dirichlet Allocation (LDA):** We applied LSA and LDA techniques to study the topic focus of ABC’s news headlines. This involved characterizing topics by exploring the most frequent words in each topic.

2. **Explored Topic Evolution Over Time:** We analyzed how topics evolved through time in ABC news headlines. Changes in the most frequent words associated with topics were examined to gain insights into the evolution of themes over the nineteen-year period.

Feel free to customize the report based on specific findings and nuances from your analysis.
