# Tokyo_AirBnB_Analysis

Looking for patterns of human behavior in Tokyo's AirBnB Data as part of a couple Master courses.

The RMDs uses 3 datasets from Inside AirBnB: Get the Data (http://insideairbnb.com/get-the-data.html)
  1) Tokyo, Kantō, Japan: calendar.csv.gz - Compiled on 29 February, 2020 (http://data.insideairbnb.com/japan/kant%C5%8D/tokyo/2020-02-29/data/calendar.csv.gz)
  2) Tokyo, Kantō, Japan: calendar.csv.gz - Compiled on 25 March, 2019 (http://data.insideairbnb.com/japan/kant%C5%8D/tokyo/2019-03-25/data/calendar.csv.gz)
  2) Paris, Île-de-France, France: calendar.csv.gz - Compiled on 15 March, 2020 (http://data.insideairbnb.com/france/ile-de-france/paris/2020-03-15/data/calendar.csv.gz)
The datasets are too large to be uploaded on GitHub.
  
*There is also an updated calandar compiled on 28 April, 2020*

Once you dowloaded the file, please set the working directory to the file locations and update the following lines accordingly:
  1) calendar2020 <- read.csv("datasets/tokyo_calendar.csv", stringsAsFactors = FALSE)
  2) calendar2019 <- read.csv("datasets/tokyo_calendar2019.csv", stringsAsFactors = FALSE)
  3) paris_calendar <- read.csv('datasets/paris_calendar.csv', stringsAsFactors = FALSE)

Cheers!