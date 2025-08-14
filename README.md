This code uses the BeautifulSoup package in Python to scrape the descriptions of Rightmove property website listings for flats and apartments.
The code searches for the word 'balcony' in the description and returns a proportion of the total adverts in a given area which have a balcony.
The code for the given area can be found within the url of the rightmove website when you conduct a search by area.
For example 5E79192 is Greater Manchester, 5E94019 is Manchester City Centre.
The code searches each area code twice - for Sales, and Rents.

The proportion of flats with balconies is used to validate the balcony quantification work undertaken in the Journal Article "Sky gardens: The potential of urban balconies as sites for nature based solutions" (Speak et al., 2025)
