# Animal-Crossing-Sentiment-Analysis


A beloved exclusive of the Nintendo franchise, Animal Crossing: New Horizon, provides a unique escape from the hustle and bustle of modern day life, drawing gamers into the tranquil world of colorful characters and creative freedom to build their own civilisation.

In this report, I aim to gain insight into how the game was received by:

1. Professional critics
2. Casual gamers
   
during the initial few months, following Animal Crossings’ launch in 2020.

Specifically, I cover the time period from 2020-03-20 to 2020-05-03, where the game was released, closely following the COVID-19 pandemic.


## Methodology
To analyse the data, I employed a Bag of words-based approach.

- That is, I broke each review into individual words, and will remove the stop words.

- I would then determine the sentiment score of each word based on a lexicon and assign a sentiment score to each individual review. This is conducted through using left_joins and inner_joins to map particular words.
  
I used 2 lexicons for my analysis.

1. Afinn. This quantifies sentiments through a number, showing its intensity.
2. NRC, which categorises sentiments into moods like sad, joy, surprise ect.
