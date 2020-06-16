# USQ CSC8004 Data Mining Major Project

This is the source code for my major project in data mining taken S1 2020


## Exoplanet Clustering
These notebooks extract the latest exoplanet data from the NASA exoplanet archive. The data that have missing values are discarded and the remaining are transformed with the log1p function to produce a more linear distribution to aid the clustering effort. 

Four clustering techniques were attempted, with the affinity propagation being the best.  The clustering was assessed by the silhouette coefficient and by comparing the planets within a cluster.


