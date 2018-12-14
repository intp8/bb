

#### Project undertaken while studying Data Science at General Assembly, London.

### Primary notebooks

Summary of the notebooks in the root directory:

##### Long-term London transport trends
- Exploratory analysis of the growth in use of various modes of transport since 2000
- Overview of changes to the population, fuel prices and air pollution

##### Detailed cycle count analysis
- Comparison of the use patterns of hire and other bicycles throughout the day
- Overview of the impact of factors such as day of the week and weather on each group

##### Cycle hire and tube use maps
- Visualisation of the increase in hire bike availability over time
- Hire bikes docking stations mapped together with tube stations and their level of use

#### These notebooks can be viewed and run via Binder:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/intp8/bb/master)

It may take a minute or so to build the repo for interactivity.

All of the collated data required for the primary notebooks is in the **[data](https://github.com/intp8/boris-bikes/tree/master/data)** directory. 

### Data search and collation

The original datasets came from various sources found online, including:

[London Datastore](https://data.london.gov.uk/)  
[TfL API](https://api.tfl.gov.uk/)

[RP5 Weather](https://rp5.ru/)

['What Do They Know' FOI Requests](https://www.whatdotheyknow.com/)

[Her Majesty's Nautical Almanac Office](http://astro.ukho.gov.uk/)

[Holiday Calendars](https://www.feiertagskalender.ch/)

Some cleaning and basic editing of a few of the files was carried out in spreadsheets. Subsequently the notebooks in the **[data-prep](https://github.com/intp8/boris-bikes/tree/master/data-prep)** directory have been run to produce the collated output in the **[data](https://github.com/intp8/boris-bikes/tree/master/data)** directory used by the primary notebooks. 

I hope to automate the collection and cleaning of the raw data or provide instructions so that the process can be reproduced in full and updated periodically.
