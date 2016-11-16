**Titanic: 1d-convolution on learned character embeddings**

The main idea is to use no hand crafted features at all. Let the model do it itself.

We'll be applying 1d convolution on learned character embeddings of raw passenger text data (names, tickets, etc.). 

This, combined with numeric raw features should probably give around 0.8 accuracy (currently got 0.80861 at the leaderboard but this is subject to some randomness :).

[A kernel at Kaggle](https://www.kaggle.com/chisquared/titanic/titanic-1d-convolution-on-symbols-embeddings)

Any feedback is welcome.
