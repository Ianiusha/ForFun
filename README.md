# ForFun

This is a toy example of a recommender system for wines based on their description.

To run the notebook, you need to download the following files into the same directories:
 - my_functions.ipybn
 - wine_tasting.ipybn
 - winemag-data-130k-v2.csv.zip (unzip before running)
 
 You also need to have the following libraries loaded in your conda environment:
 - sklearn  (for clustering)
 - nltk (for text processing)
 - pandas (for csv file manipulation)
 - seaborn (for plotting)
 - matplotlib (for plotting)
 - wordcloud (for creating wordcloud graphics)
 
 The recommender system as it is implemented right now will search for the keyword provided in the title of the wines and output the FIRST hit. You can easy change the code to output all hits ;)
