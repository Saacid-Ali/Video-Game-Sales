# Video-Game-Sales
* Visualised the sales of video games on PS4 and Xbox One
* Wrote a report that analyses the sales of video games on PS4 and Xbox One.


## Code and Resources Used 
**Python Version:** 3.7.6  
**Packages:** pandas, numpy, matplotlib, plotly    
**Data Collection Source:** https://www.kaggle.com/gregorut/videogamesales      
**View Code Files In Interactive Mode:** https://nbviewer.jupyter.org/


## Data Collection
The data was collected from https://www.kaggle.com/gregorut/videogamesales. The data came with 1 dataset which was 'vgsales.csv'.

This dataset contains data on video game sales dating back to 1980 on various platforms and includes some of the following data:
*	Rank
* Year
*	Genre
* Publisher
*	Platform
*	Global Sales

## Data Cleaning
Once the data was collected from Kaggle, the data needed to be cleaned prior to being visualised. I made the following changes:

* Removed thhe video games which were on platforms other than PS4 or Xbox One.
* Removed the Rows with null data.
* Renamed some of the categorical variables that were characterised in a single group in numerous ways to one consistent representation.

## EDA and Data Analysis
I looked at the distributions of the data and the value counts for the various categorical variables and also analysed the data to identify key trend. Below are a few highlights.

![alt text](https://github.com/Saacid-Ali/Video-Game-Sales/blob/master/fig1.png)
![alt text](https://github.com/Saacid-Ali/Video-Game-Sales/blob/master/Genre_Sales.png)
![alt text](https://github.com/Saacid-Ali/Video-Game-Sales/blob/master/Pub_Sales1RB.png)
![alt text](https://github.com/Saacid-Ali/Video-Game-Sales/blob/master/fig2.png)
![alt text](https://github.com/Saacid-Ali/Video-Game-Sales/blob/master/fig3.png)
![alt text](https://github.com/Saacid-Ali/Video-Game-Sales/blob/master/fig4.png)
![alt text](https://github.com/Saacid-Ali/Video-Game-Sales/blob/master/fig5.png)
![alt text](https://github.com/Saacid-Ali/Video-Game-Sales/blob/master/fig6.png)
