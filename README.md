# UFO Sightings

## Overview of Analysis
The purpose of this project was to provide the client with a functional table of data for UFO sightings based
on the users input of search criteria.  Using a date rannge, city, state, country and shape filters, the user
can get a report back of the UFO sightings matching that criteria.


## Results
We have designed a database filtering tool on this UFO Sightings webpage.  The previous website design included a filter button.  With the revison 
each box of the filter search is clearly identified with the criteria for the search field as well as an example of how to fill out the search box.
Once all the seach boxes are filled out you can select enter for the search results to appear. The table of data appears to the right of the filtered search with the date, city, state, country, shape, duration, and comment values filled out.  The user can continue to update the search fields to yield new results.


## Summary
This site does have a great source of data that pulls from a data.js file.  However the data only includes data from January 2010 and from the United States.  Due to this limitation the country field should be locked in as well as the month and year fields.  That way the user doesn't waste time trying to search outside the window of data.  To improve on this limitation, would be to pull link this site to pull data from another site, which would expand what the user can search.  At the very least their should be a disclaimer alerting the user that this data is only pulling from January 2010 and for sightings in the United States. Communication of the limitation could help the user better undestand the search as well as the results they recieve.  I would design this disclaimer as a pop up message to appear whenever the user inputs data that is outside the range of data in the data file.