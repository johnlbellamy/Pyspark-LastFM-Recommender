# LastFm_Recommender
A recommender made in PySpark, using LastFM 360k User Dataset
Assumes you have sources the LastFM 360k User datset and have a PySpark cluster running. For this notebook, you could get away with 
one machine. See the lastFM.pdf for slides.

You will need to provide your own 360k User LastFM dataset (Should be able to find in a web search) and run a Spark cluster in distributed or standalone mode. 

# Jupyter Notebook Usage:
# Download data from: http://mtg.upf.edu/static/datasets/last.fm/lastfm-dataset-360K.tar.gz
# tar -xf lastfm-dataset-360K.tar.gz
1) LastFM-Munging cleans and structures the data. 
2) LastFM-Descriptive is for summary stats and some additional munging. 
3) LastFM-Model is the model notebook.

Note: For the model, you do not have to run the grid search  (large hyper-parameter selection loop), as it does take some time and really not necessary.
