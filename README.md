# UFO Sightings Analysis

## Overview of Project:
Dana, a journalist is seeking to write a story about her hometown of McMinnville, Oregon. Her main goals is writing about a sense of place reminiscent of her upbringing centered around the numerous UFO sightings in the area. There is a javascript file at her disposal with a dictionary packed with pertinent UFO sighting information. She has decided to display the information (the date, city, state, country, shape, duration, and comments) in a table format. For convenience to the user, she has concluded that it was best to allow for filtering based on these criteria and to deploy it all on a webpage. To this end, she will need the following files: the data.js containing the relative list of dictionaries, the app.js file to create the table and filter from the data, and the index.html file to display the results. For styling purposes she has included a style.css file as well. 

## Results: 
The page is set up so that automatically the results are displayed in chronological order beginning with the first of January 2010 and ending on the 13th of that month (see image below). Initially, a filter button was written into the index.html file to filter based on date. Upon further assessment, it seemed better to filter based on a broader array of search criteria. With this in mind, I chose to use the key-value pairs of each object in the dictionary as a basis for search specifications. As the search engine is designed in such a way that only exact matches will display, the narrower categories (such as date) are less likely to turn up results. In the app.js file I wrote in a template for a model search. Such a template is show in the image below. The suggested search is so targeted that if entered in and processed, one single result is generated.  


![image](https://github.com/mcpoley/UFOS/blob/main/static/images/search%20template.png)








## Summary: 

One drawback of this web design is that the search engine only registers exact matches. This is particularly true when it comes to the “date” criteria, as the only findings listed in the data are in the month of January 2010. Viewers are more than likely going to be interested in more recent dates and more comprehensive timeframes. Two recommendations for further site development are to gather more expansive data (both in terms of geography and chronology) and to filter out the data that is insignificant. Besides the limited date range, the geographical reach of sightings seems unsubstantial (the majority seem to come from California). I would also filter out the sightings that only lasted a couple seconds or had no recorded description. For future display, the findings need to appear as convincing as possible to spark interest.        
