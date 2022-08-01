# TopicModelling
Trying Topic Modelling (LDAvis) of 100k news

This is a script for LDAvis topic modelling applied to a corpus of (100k) news (400 words each) collected from Newspapers.
The first script imports a .csv file and applies LDAvis topic modelling and generates an interactive visual diagram (html format - "7Allnews.png") and an image (png) format.
This scripts also assigns a topic to each of the pieces of news and saves the new dataframe as a .csv file
(for more on the LDAvis package, please, follow: XXXX) 
Examples of these outputs are shared. 

The second script imports the saved .csv 
And suggests some analysis: 
1) importing the texts of all news belonging to one topic (for finer analysis)
2) creating a new dataframe from the news filtered as belonging to a topic
It generates then a chart (bar-stacked) by number of news by country- by topic (7LDAvidTopicscountpercountry.png)
