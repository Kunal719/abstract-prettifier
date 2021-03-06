# abstract-prettifier

The Abstract Prettifier is a model which can help the user read the medical abstracts easier and in a well written form. It is a Natural Language Processing (NLP) Model.
We usually see a medical study will begin with a large abstract, which tells us about the introduction to results achieved in the paper. This model can make that abstract easier for the user to read by differentiating the different parts of abstracts such as Objective, Methods, Conclusions, etc. 

The paper used for reference was - https://arxiv.org/abs/1710.06071

We can get the data on github at - https://github.com/Franck-Dernoncourt/pubmed-rct

Results Achieved :

The different scores of our model : (on 20k example dataset)

1. On Training Set - The accuracy achieved was `89.41 %` with a loss of `0.2898`
2. On Validation Set - The accuracy achieved was `90.28 %` with a loss of `0.2604`
3. On Test Set - The accuracy achieved was `89.95 %` with a loss of `0.2758`

**The wrong predictions file has the top 100 wrong predictions our model has made on the test dataset**
