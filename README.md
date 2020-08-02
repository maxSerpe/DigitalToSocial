# DigitalToSocial
Designed to measure the impact of digital media on social media platforms.

First Iteration: 

Collect ranges of information from Google News API and Twitter API. Feed these into PySpark, develop a set of adjustable parameters to allow the user to search for desired keywords. 

Example usage: 

User sets a date of interest, the keywords as ["COVID", "Covid-19"] for Google News, and ["masks"] for twitter. The project will then return usage metrics from both platforms for the occurence of the search terms, as well as the change in occurrence from the N weeks.    

Sources: 

From the examination of Pew Research Center's article [1], we can infer that most interactions with the article will happen within the first week. Thus, if there is any correlation between what is seen in the news media to mentions on twitter, we can assume it will appear on the time scale of hours to days. 


1: https://www.journalism.org/2016/05/05/6-most-interactions-begin-within-one-week-of-publication/
