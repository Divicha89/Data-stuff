### History in Numbers: EDA of One Direction

This is a little EDA project that i have made to work with datasets as a practise. in this project we will see Data Cleaning,
dataprocessing.

I this blog, First and foremost, let us meet One Direction—Harry Styles, Niall Horan, Zayn Malik, Liam Payne, and Louis Tomlinson. It is a British-Irish boy band who recorded and toured pop music from 2010 to 2015. After an 18-month hiatus, none of the band members got back; they led on with their individual careers, giving fans the best music and memories.

For the whole discography of One Direction to make complete sense, let us consider three datasets.

1. Top songs and peak streams of the band throughout their journey (2010–2015) will be referred to as ‘Streams’ dataset through 
   the blog
2. Popularity range of music, compared to other artists. will be referred to as ‘popularity’ dataset through the blog
3. Sales per album and streams. will be referred to as ‘Sales’ dataset through the blog
 
So basically, EDA is a short form of Exploratory Data Analysis with which we can clean the data and visualize it so we can make assumptions based on it. EDA is one of the first steps in processes like Data science, bulding Machine learning algorithms.
## Dataset Details and cleaning:
![image](https://github.com/user-attachments/assets/220e242b-c652-43ca-85e7-f7c562540e2d)

  1. Songs and Peaks: Getting to know the data:The Streams dataset has columns like “"SONG"—title of the song, “Lyricis"—lyricist "of the song, “Album”- the song belongs to, “Year"—which "year did the album come out?"Peak_Streams"—peak number of streams of the particular song on Spotify.

  First, we have to check if this data contains null values and outliers before making assumptions. Though the data did not have any duplicates when checked, there were 4 null values. As per the data knowledge, I have observed those songs to be singles released by the band; hence, they do not belong to any mentioned albums. This data can be dropped. Final dataset after cleaning has 89 rows × 5 columns.
We were able to find out the below from the current dataset.
The highest and lowest streams in the dataset are 1480993263.0 and 7788.0
The total average streams on spotify are: 65138545.07777778










    

