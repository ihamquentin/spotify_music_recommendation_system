# spotify_music_recommendation_system
recommending music based on spotify data set 

<h3>EDA</h3>
performed some EDA on the data vheckinng the relativity of each feature and their correlation with each other.
it was a large dataset that also alllowed me checkout the sound components and see hoe music changed over time 

<h3>Model building</h3>
i used a KNN model and also a pipefile to fine tune my parameters
firstly i worked on finding my best n_clusters using the elbow method to optimize my result 
then using pipeline ii added a standard scaler and my Knn model to perform my prediction.


<h3>My bias</h3>
1. music in same genre are often times recommended because they share 2 or more similar features 
2. similar genres tend to have data points that are located close to each other while similar types of songs are also clustered together.
