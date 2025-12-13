# Spotify Music Data Analysis (2009-2025)  
## Overview  
Going over the data I thought it would be interesting to uncover what kind of trends the dataset would reveal in music taste.
Over the course of time we're starting to see more artists come out and music streaming is the most popular way to listen to your favorite artist and songs.  
There's also been a wave of content that is becoming shorter as time goes on and wanted to see if that had any affects on song popularity.  
Questions I had when diving into the data was, Do famous artits always have popular songs? How has song duration changed over time? Does explicit content  
impact track popularity.  

## The Data  
The source of this data comes from a dataset on kaggle called ["Spotify Global Music Dataset (2009-2025)"](https://www.kaggle.com/datasets/wardabilal/spotify-global-music-dataset-20092025)  
There's around 8,500 tracks in the dataset.  

## Tools
**Language:** Python  
**Libraries:** Pandas, Numpy, Matplotlib.pyplot, Seaborn  
**IDE:** Jupyter Notebook  

## Key Insights and Visualizations  
**Insight 1:** Track durations are shortening while volumes of music content is increasing. (<img width="600" height="400" alt="Evolution of Music" src="https://github.com/user-attachments/assets/3faa27fc-cb5a-4c35-b74c-e867db5eedee"/>)  
Songs over the course of 15 years look to have dropped from an average of 3.75 to 3.08 minutes.  
While the volumne of music being released has increased over the course of 15 years.  
This could be with presence of streaming music now and how the pay structure is laid out, causing music to be shortend and the volumne of music to increase. More analysis would have to be done in order to come up with a concrete stance on that hypothesis.  

**Insight 2:** The more popular the artist the more popular the track. (<img width="640" height="480" alt="track vs artist popularity" src="https://github.com/user-attachments/assets/95eca996-e54d-4a4f-b848-f7ee9b03c8d6" />)  
Seeing what type of trends there were in what makes a track popular I used a heatmap visualization and used the spearman method to find out the correlation to what makes a track gain in popularity.  
Using those insights I was able to create a scatter plot visualization between track_popularity and artist_popularity as those two variable looked to be highly correlated with each other.  
The scatter plot revealed that the higher in popularity the artist is, the more likely the track with be high in popularity. It also revealed interested data on a number of artists that were considered  
popular, but still wasn't able to produce highly popular tracks of songs. It brings an interesting question of, what can cause popular artists to fail in creating a popular track?  

**Insight 3:** Popular Genres of music over the past 15 years. (<img width="1500" height="600" alt="Top 15 Genres" src="https://github.com/user-attachments/assets/c7324ee1-9ce8-4900-87dc-5bddf45e9e41" />)  
Looking at genres the data was messy in this matter. I used a couple of different functions to clean up the column and be able to pull results that wouldn't bias the data so much.  
I dropped rows that were missing data in this column and moved forward with aggregating the data I was successfully able to seperate into their own rows.  
Coming to the conclusion that pop music looked to be the most popular tracks to listen to while r&b was the least listen to over the past 15 years.  

**Conclusion:** With these insights I conclude that to have a higher probability in having a popular track, find a popular artist. This isn't a guarantee as the data does reveal that popular artists could still have trouble making their song popular to the masses.  
There are also outliers that show not so popular artists making popular tracks. Highests chances though of having a popular track is having a popular artist.  
Time duration on songs are also decreasing over the course of time, but the volume of music continues to rise. Whether that's good or bad is up for debate. What's causing this to happen though could be interesting to look into.  
The pop genre looks to top the charts in terms of popularity. If an artist is looking to become popular then creating a pop song will give you the best chances as most listeners tend to listen to pop.
