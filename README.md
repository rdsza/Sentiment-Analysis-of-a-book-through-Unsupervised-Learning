
# Sentiment analysis via Unsupervised LEarning

In this tutorial, I will  apply sentiment analysis to the text contained into a book through an Unsupervised Learning (UL) technique, based on the AFINN lexicon. 

This notebook exploits the afinn Python package, which is available only for English and Danish. If your text is written into a different language, you could translate it before in English and use the afinn package.

This notebook applies sentiment analysis the Saint Augustine Confessions, which can be downloaded from the Gutemberg Project Page. The masterpiece is split in 13 books (or chapters). We have stored each book into a different file, named number.text (e.g. 1.txt and 2.txt). Each line of every file contains just one sentence.
