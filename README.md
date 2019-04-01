# Music-Recommendation-System
This Project is based on ACM RecSys Challenge 2018 organized by Spotify, The University of Massachusetts, Amherst, and Johannes Kepler University, Linz.  
We have used Million Playlist Dataset(MPD) provided in Challenge which contains 1 Million Playlist created by users on the spotify platform.  
Each playlist in the MPD contains a playlist title, the track list (including track metadata) editing information (last edit time, 
number of playlist edits) and other miscellaneous information about the playlist.
# Preprocessing
1.Run jsontocsv_restruct.py to convert json data to csv format.
# Algorithm Files
1. Apache Spark MLlib's ALS(Alternating Least Squares) Model 
2. ALS model using Implicit API 
# Evaluation Metric
1.R-precision   
2.NDCG 
# Requirements
Python>=3.6
Dask  
gcsfs  
Implicit-0.3.8  
Anaconda Distribution
Scikit-learn    
SciPy  
