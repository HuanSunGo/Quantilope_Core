# Quantilope_Core

## Statement of Problem 
Typically, Quantilope clients seek an unambiguous picture of brand health, which is difficult to achieve if different data sources provide differing or contradicting insights. 

As each platform provides different non-representative samples of the clients’ audience of interest, it is important to know how to interpret samples with a benchmark rooted in representative sampling properly. 

_**Challenge**_
Current approach haven’t incorporated the voices of social media
Cannot compare the brand KPIs between survey data and social media platforms 

## Approach 
_**Twitter & Reddit Data**_
- Make inference about Twitter user’s demographic information,  quantitatively analysis Tweets sentiment, calculate brand health KPIs to prepare for the MRP(below) regression.

_**Survey Data**_
- Subsampling survey that  contains only active Twitter users to make comparisons, process data to prepare for the MRP regression.  

## Data Description
- Time Window:  August 1th to Oct 6th, 2022
- Social Media Data:  
    - Tweets in English within the US containing keywords which are brands mentioned in survey(“brands”)
    - Reddit comments containing keywords which are brands 
- Survey Data: 
    - Content: Two sets of the survey data use, original survey by Quantilope and the filtered sample (“subsample”) , subsample contains surveys from twitter-active users①.  


