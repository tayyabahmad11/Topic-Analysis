# Topic-Analysis

Given a dataset containing news articles, I implemented a Latent Dirichlet allocation model to analyze their topics and themes. 

The process started with cleaning the text data; this involved word stemming and removal of stop words, as well as the removal of certain nouns, such as New, York, Donald, Trump, Clinton, etc. These nouns tended to overpower the overall sentiment of the articles and gave poor results. I also experimented with word lemmatization, but this produced poorer results than with just word stemming, so I ommitted it. 

Next, I created a "bag-of-words" representation of the articles, which is necessary to implement the LDA (Latent Dirichlet Allocation model). After the implementation of the LDA we are able to see the topics of the news articles, as shown in the Jupyter Notebook.
