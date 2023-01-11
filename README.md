# Mission-To-Mars

## Overview
In this analysis, the data from two websites are used and analyzed. First, a website containing news about Mars is scraped. Second, data taken from a Mars mission is extracted and analyzed to find the following:
1. How many months are there on Mars?
2. How many Martian days' worth of data are there?
3. Average temperature by month.
4. Average pressure by month.
5. How many terrestrial days exist in a Martian year?

## Resources
- Data Sources: "https://redplanetscience.com/" (Mars news site), "https://data-class-mars-challenge.s3.amazonaws.com/Mars/index.html" (Mars data site)
- Software: Python 3.7, Jupyter notebooks, matplotlib

## Mission-To-Mars Results
In the first analysis, the Martian news was scraped and further put into a Python dictionary. A portion of the results are shown below:
![title-preview](https://github.com/bchillman/Mission-To-Mars/blob/main/Data/title-preview.png)
This result was then saved as a json file and can be viewed in the Data folder in "elements.json".

In the second analysis, data from a martian mission was scraped and transformed into a pandas DataFrame. With these data, we then found the following results:
1. There are 12 Martian months.
2. There are 1867 martian days worth of data from the mission.
3. The average monthly temperature looks as follows:
  a. ![month_temp](https://github.com/bchillman/Mission-To-Mars/blob/main/Data/average_month_temp.png)
  
  b. When sorted from lowest temperature to highest (as seen below), we can see that the third month is the coldest and the eighth month is the warmest
  ![sorted_temp](https://github.com/bchillman/Mission-To-Mars/blob/main/Data/sorted_month_temp.png)
