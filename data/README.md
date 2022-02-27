# Cleaned data sets
The structure of the cleaned data files is as follows:

    location location identifier (string)
    lat (approximate) latitude of the observation (double).
    long (approximate) longitude of the observation (double).
    alt (approximate) altitude of the observation (double).
    year year of the observation (integer).
    bloom_date date of peak bloom of the cherry trees (ISO 8601 date string). The "peak bloom date" may be defined differently for different locations.
    bloom_doy days since January 1st of the year until peak bloom (integer). January 1st is 1.
    
# Data source

## Washington, D.C. (USA)

The data in file washingntondc.csv has been obtained from https://www.epa.gov/climate-indicators/cherry-blossoms. 
The latitude and longitude correspond to the location of the Tidal Basin in Washington, DC and the cherry trees are approximately at sea level (altitude 0).

The peak bloom date is defined as the day when 70% of the Yoshino Cherry (Prunus x yedoensis) are in full bloom, as determined by the National Park Service.
Copyright notice

Sourced from EPA's Climate Change Indicators in the United States: https://www.epa.gov/climate-indicators/cherry-blossoms. See the source for copyright details.

## Liestal-Weideli (Switzerland)

The data in the file liestal.csv is The cherry trees in Liestal-Weideli are of species Prunus avium (wild cherry).

The peak bloom date is defined as the day when 25% of the blossoms are in full bloom. The date is determined by MeteoSwiss.
Copyright notice

Copyright by Landwirtschaftliches Zentrum Ebenrain, Sissach and MeteoSwiss.

    You may use this dataset for non-commercial purposes.
    You must provide the source ("Source: Landwirtschaftliches Zentrum Ebenrain, Sissach and MeteoSwiss")

## Kyoto (Japan)

The data has been obtained from http://atmenv.envi.osakafu-u.ac.jp/aono/kyophenotemp4/. The geographical location (longitude, latitude, altitude) roughly corresponds to the Nakanoshima area of the Arashiyama Park in Kyoto, Japan.

The peak bloom date of the Prunus jamasakura is determined by a local news paper in Arashiyama (Kyoto, JP). Data prior to 1888 is extracted from various descriptions or estimated. See the source for details.
Copyright notice

Copyright holder Yasuyuki AONO (aono(at)envi.osakafu-u.ac.jp). The data was obtained from http://atmenv.envi.osakafu-u.ac.jp/aono/kyophenotemp4/.

    Data from the 9th to the 14th centuries was acquired and analyzed by Aono and Saito (2010; International Journal of Biometeorology, 54, 211-219).
    Phenology for 15th to 21st centuries was acquired and analyzed by Aono and Kazui (2008; International Journal of Climatology, 28, 905-914).
    
## City_populations

It includes only the four cities, which is from UN World Urbanization Prospects (https://population.un.org/wup/Download/).
Four cities are Kyoto (Japan), Liestal-Weideli (Switzerland), Washington, D.C. (USA),  and Vancouver, BC (Canada).

