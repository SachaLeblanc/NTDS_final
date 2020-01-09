# A dive into the music industry
The following GitHub contains our final project for the Network Tour of Data Science course. You can find here two notebooks; one used to query the data for our dataframe and one to do the study of the data. You can also find our written report. Note that the data being too big to be uploaded on GitHub, we can give it to you directly so that you don't have to re-pull everything from Genius

## The project: starting point

During this project, we wanted to tackle the relationships between the multiple actors of the music industry. This means we are not only interested in the well known interprets but also the producers and the songwriters. Using graph theory, we tried our best to discover important features of this world based on a database of around 70 000 songs containing, for each song, the collaborations that lead to its existence.
    
From this basic idea of studying working relationships between multiple actors, we thought about the following questions and tried to answer them in the best way possible:

First, we are interested to know if the music industry is a connected world or not. If the answer is yes, we would like to know if we are able, by studying the working relationships, to discern a mixing of the musical genres or not (does actors work only on one genre our multiple, do they either have preference for a specific genre of music, can we make the same conclusion for each group of actors). On the same note, we are also interested in looking at possible sub-genre division using the collaborations data cause sub-genres are not defined in the data recovered from Spotify. Finally, we will study if a relationship with a big name is needed to create  a place in the musical world or not.

## What did we used to answer these questions

During this project, we used a graph theory approach to answer the questions above. We created a matrix representation (adjacency matrix) of our data. We used plotting tools to look at the result nicely and interactively. We used clustering/community detection algorithms to look into the graph with more depths (Spectral clustering, DBSCAN, Louvain method).
We also did ourselves the pulling of the data using both an existing dataset from Spotify from Kaggle (https://www.kaggle.com/zaheenhamidani/ultimate-spotify-tracks-db) and the Genius API.

## Tool needed to run the project

To run this project you will need the following python libraries installed:
- **pandas** 
- **numpy** 
- **re** 
- **networkx** 
- **random**
- **seaborn** 
- **collection** 
- **matplotlib**
- **sklearn** 
- **community** 
- **bokeh** 
- **requests**
- **BeautifulSoup**

You can send us a message if you want the data we pulled to rerun the notebook. If you want to pull the data yourself, you'll have to create yourself an account on the Genius API to have your token for pulling data.
    
> **Note:** some algorithm, when rerun, will not necessarily output the same result that the one present in the notebook cause they are solving optimization problem (Louvain method).

> **Note:** Since Bokeh is not always cached in Jupyter notebooks, you'll probably have to rerun all the notebook (**approx:** 1h40) to be able to navigate through the graph. Otherwise, you can find the pictures corresponding to each graph in the folder picture of this repository. To go quicker set the sample size of the test dataset to 0.1 instead of 0.2 (the observations will not be necessarily right but at least you will see the graphs.

## Authors

Sacha Leblanc, Etienne Caquot, Grégoire Mayrhefer, Alexis Mermet
