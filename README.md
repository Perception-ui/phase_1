# Lights, Data, Strategy: Informing Microsoft's Movie Studio with Box Office Analytics

## 1. Business Understanding
### a) Introduction.

In an effort to tap into the growing trend of original video content and expand its footprint in the entertainment industry, Microsoft has made the strategic decision to establish its own movie studio. However, being new, Microsoft faces the challenge of understanding which types of films perform exceptionally well. To address this challenge, a data driven analysis is necessary to uncover valuable insights that can guide the decision making process regarding the types of films to start working on. 

The primary objective of this analysis is to identify attributes successful films at the box office share, using comprehensive data sets spanning various aspects of the film industry.By examining historical records, genre trends, and audience preferences, we aim to provide actionable insights to the leadership of Microsoft's new movie studio. 
These insights will guide Microsoft in determining the types of films that are competitive and likely to thrive in this evolving market. 

### b) Defining the metric for success. / Problem statement. 

Microsoft's new movie studio lacks domain expertise in filmmaking and needs guidance on which film genres to focus on to maximize box office success. Leveraging historical box office data and exploring genre trends, this investigation will guide the choice of films they should produce. Box office revenues, ROI and ratings data will serve as indicators of financial viability and audience reception across different film genres.

The success of our analysis will be measured by the following metrics:

1. Our analysis should accurately identify the film genres that have historically performed well at the box office.
2. Revenue increase: We try to predict the profitability of a movie based on the features of the dataset. A movie is profitable if it makes more than at least 2.5x the budget.

### c) Main objectives and understaning the context 
Main Objective of the Study:
The main objective of this study is to analyze historical film data and identify features top movies share. Outcomes will determine the types of films to create, maximizing the chances of success.

Specific Objectives:
1. To determine the genres with the highest potential for success in the market in terms of revenue and audience reception.

2. To investigate additional factors such as budget, studio, and target audience demographics, to determine their impact on a film's success. 

3. Based on the analysis, derive actionable insights and recommendations that align the studio's content strategy with audience preferences and market trends to increase the probability of producing commercially successful films.

### d) Experimental Design
- Data Collection
- Read and check the data
- Cleaning the data, type casting
- Exploratory Data Analysis
- feature modelling and evaluation
- draw conclusion based on evaluation

### e) Data relevance, data understanding. 
The dataset comprisea historical data from Imdb and box office with information on genre, title, budget, gross profits and other features we can analyse to find out more about performance of movies. 
According to imdb pro, a film has to make around double its cost to break even. Distributions receive money known as rentals that is nearly 50% of gross earning. Some movies spend more on advertising but this is covered by ancilliary streaming and tv revenue whose data we do not have access to. A film of 100m budget needs to make at least 255m to break even. https://pro.imdb.com/content/article/entertainment-industry-resources/featured-articles/how-is-the-success-of-films-and-tv-shows-measured/GLFTC8ZLBBUSNTM3

### Analysis 
`Total_gross` and `Profitability`: There is a strong positive correlation of 0.941 between the total gross and profitability of movies. This indicates that as the total gross increases, the profitability tends to increase as well. This suggests that movies with higher box office earnings are more likely to be profitable.

`Production Budget` and `Profitability`: The correlation between production budget and profitability is relatively weak, with a value of 0.172. There is limited association between the production budget of a movie and its profitability. A higher production budget does not necessarily guarantee higher profitability. Other factors, such as marketing, distribution, and audience reception, may play significant roles in determining a movie's profitability.

The link to presentation of findings. https://docs.google.com/presentation/d/1-STVA_1KYjX_UMhoOe1hw6DfreCVZAArZXS-kufmtbg/edit?usp=sharing

`Rating` and `Profitability`: The correlation between the movie rating and profitability is negative, with a value of -0.235. This suggests that there is a weak inverse relationship between the rating of a movie and its profitability. It implies that movies with higher ratings are not necessarily more profitable. 
