# Project1-Group6-Chicago Crime Rates 


# Project Description/Outline
Our group conducted Chicago property crime analysis from 2018 to present to answer the following questions: 
1. Does crime rate go up when property value is in the lower range?
2. Does the time of day have an effect when property crime take place?
3. Does COVID19 ‘Stay-At-Home’ order in April 2020 influence crime rate? 
4. In what zip code, there is the most crimes reported?


# Data Collection
Chicago Property Data: https://www.zillow.com/research/data/
Chicago Crime Data: https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-Present/ijzp-q8t2  
Chicago Income Data: https://data.census.gov/cedsci/profile?g=0500000US17031

# Data cleaning and preparation methods:
Reverse Geocoding API call: Using (Latitue, Longitude) to get ‘zipcode’
DataFrame.Merge (on ‘zipcode’) : Merge data sets from Crime data, Property data, Income data
DataFrame.dropna(how=‘any’) : Remove ‘NaN’
DataFrame.fillna(0)
Binnings


