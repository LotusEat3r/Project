## Description

A dataset sourced from the CDC website containing information on deaths from pneumonia and influenza in the United States for the years 2009-2019. 

## Format

A dataframe with 32,605 observations on 10 variables.

### geo_level
Factor with three levels: state, region, and national.

### region
Numeric, each region contains the following:
1 - Connecticut, Maine, Massachusetts, New Hampshire, Rhode Island, Vermont
2 - New York, New Jersey, Puerto Rico, the Virgin Islands
3 - Delaware, District of Columbia, Maryland, Pennsylvania, Virginia, West Virginia
4 - Alabama, Florida, Georgia, Kentucky, Mississippi, North Carolina, South Carolina, Tennessee
5 - Illinois, Indiana, Minnesota, Michigan, Ohio, Wisconsin
6 - Arkansas, Louisiana, New Mexico, Oklahoma, Texas
7 - Iowa, Kansas, Missouri, Nebraska
8 - Colorado, Montana, North Dakota, South Dakota, Utah, Wyoming
9 - Arizona, California, Hawaii, Nevada, Guam, American Samoa
10 - Alaska, Idaho, Oregon, Washington

### state
US State. Also included in this column is New York City and Washington DC. 

### year
Year of observation, 2009-2019

### week
Week of the year, numeric, 1-52.

### age
Factor with 4 levels:
0-17 Years Old
18-64 Years Old
65+ Years Old
All ages

### flu_deaths
Recorded deaths due to influenza, numeric.

### pneu_deaths
Redorded deaths due to pneumonia, numeric.

### pneu_flu_deaths
Recorded deaths due to both influenza and pneumonia, numeric.

### all_deaths
All recorded deaths, numeric.