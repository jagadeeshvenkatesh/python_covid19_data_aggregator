I've not been successful at finding any sort of easily digestable data regarding the coronavirus outbreak on the web so far.  Avi Schiffmann's [nCov2019.live](https://ncov2019.live/data) appears to be the best out there at this point.  This notebook scrapes his site and timestamps that data into a Pandas dataframe.  The idea here is to periodically scrape the site and use the trend data to understand how infection rates are trending regionally.