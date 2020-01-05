# NTDS_final
The following GitHub contains our final project for the Network Tour of Data Science course. You can find here two notebooks; one used to query the data for our dataframe and one to do the study of the data. You can also find our written report. Note that the data being to big to be put in the GitHub, we can give it to you directly so that you dont have to repull everything from Genius

## The project: starting point

During this project, we wanted to tackle the relationships between the multiple actors of the musical industry. This means we are not oly interested in the well known interprets but also the producers and the song writers. Using graph theory, we tried our best to discover important features of this world based on a database of around 70 000 songs containing, for each song, the collaborations that lead to its existence.
    
From this basic idea of studying working relationships between multiple actors, we thinked about the following questions and tried to answer them in the best way possible:

First we are interested to know if the musical industry is a really connected world or not. If the answer is yes, we would like to know if we are able, studying the working relationships, to discern a mixing of the musical genres or not (does actors work only on one genre our multiple, do they either have preference for a specific genre of music, can we make the same conclusion for each group of actors). On the same note we are also interested in looking at possible subgenre division using the collaborations data cause sugenres are not defined in the data recovered from Spotify. Finally, we will study if relationship with big name are needed to create yourself a place in the musical world or not.

## What did we used to answer these questions

During this project, we used, as said above, a graph theory approach to answer the questions above. We created a matrix representation (adjacency matrix) of our data. We used plotting tools to look at the result in a nice and interactive way. We used clustering/community detection algorithm to look into the graph with more depths (Spectral clusering, DBSCAN, Louvain method).
We also did ourself the pulling of the data using both an existing dataset from Spotify from Kaggle (https://www.kaggle.com/zaheenhamidani/ultimate-spotify-tracks-db) and the Genius API.

## Tool needed to run the project

To run this project you will need the following python libraries installed:
    1. **pandas** \\
    2. **numpy** \\
    3. **re** \\
    4. **netwrokx** \\
    5. **random**\\
    6. **seaborn** \\
    7. **collection** \\
    8. **matplotlib** \\
    9. **sklearn** \\
    10. **community** \\
    11. **bokeh** \\
    12. **requests**\\
    13. **BeautifulSoup**\\
    
If you want to pull the data yourself, you'll had to create yourself an account on the Genius API to have your own token for pulling data.
    
Note: some algorithm, when rerun, will not necessarily output the same result that the one present in the notebook cause they are solving optimization problem (Louvain method).

