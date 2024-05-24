# Netflix
This project analyses Netflix TV Shows and Movies created between 1925 and 2021. The primary goal was to use raw data to identify trends in:
- Release Years,
- Popular Genres,
- Active Directors,
- % Independent, and
- % International.

![Netflix Dashboard Preview](https://github.com/ecommerce-by-alyson/netflix_analysis/blob/main/data/netflix-dashboard-view.png?raw=true)

#### -- Project Status: Completed

# Table of contents
1. [Methods](#methods)
2. [Technologies](#technology)
3. [Getting Started](#start)
4. [Analysis & Findings](#analysis)
5. [Next Steps](#next-steps)

### Methods Used <a name="methods"></a>
* Exploratory Data Analysis
* Data Cleaning
* Data Analysis
* Data Visualization

#### Data Cleaning:
Removed outlier data from the file using Power Query Editor. 


#### Data Transformation:
Used Power Query Editor to create new columns for structured analysis:
- Category lists were in the "listed_in" field. It was transformed into 3 simple columns: primary category, international movies, and independent content.
- Country lists were in the "country" field. It was transformed into a Primary Country field based on the first country in the list.

#### Data Visualization:
* A custom Theme was developed using [Adobe Color Wheel](https://color.adobe.com/create/color-wheel): "Netflix".
* The theme adheres to Netflix's Brand Guidelines at [brand.netflix.com/en/assets/](https://brand.netflix.com/en/assets/).


### Technologies  <a name="technology"></a>
* PowerBI
* - Power Query Editor


## Getting Started <a name="start"></a>
* **PowerBI notebook:** netflix-analysis.pbix
* **Data set:** data\netflix-titles.csv


* The analysis takes the form of a single PowerBI of filename given above.
* The data set for this analysis was provided by Kaggle (https://www.kaggle.com/datasets/shivamb/netflix-shows "Netflix Movies and Shows").

## Analysis & Findings <a name="analysis"></a>
* The most popular genres are Drama movies and Crime TV shows.
* The most movies were released in 2017 and 2018. The most TV Shows were released in 2020.
* From the US, Marcus Raboy, known for Adam Sandler's, Kevin Hart's, and many more comedy specials. As a popular Director, he has Directed 14 movies.
* Top countries generally produce more movies than TV shows, except in Japan and South Korea.

### Next Steps <a name="next-steps"></a>
With additional data, it would be interesting to answer:

* What % did the COVID-19 pandemic impact the release of new movies and TV shows?
* Which genre(s) have the longest watch time lengths?
* Do some countries show a demand or trend for longer TV show seasons or movie lengths?