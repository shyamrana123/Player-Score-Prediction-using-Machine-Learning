![image](https://github.com/user-attachments/assets/91f11918-bf22-4db3-9d68-493c67750d13)
# Player-Score-Prediction-using-Machine-Learning

## Background

### Online Betting in Portugal:
Revenue in the Online Sports Betting market is projected to reach US$45.18bn in 2024. Revenue is expected to show an annual growth rate (CAGR 2024-2029) of 7.49%, resulting in a projected market volume of US$64.82bn by 2029. In the Online Sports Betting market, the number of users is expected to amount to 181.3m users by 2029. User penetration will be 3.8% in 2024 and is expected to hit 4.8% by 2029.
Popularised by gambling houses in the Middle Ages, King Alfonso IV banned gambling in 1350 – a policy that lasted until around 1927. Nevertheless, lotteries were introduced in the 17th century and made permanent in 1946. Gambling remained prohibited by the government until 1927 –  The gambling industry then became a state-owned monopoly until 2015 when online gambling was legalised and bookmakers could start operating in Portugal. With Portugal boasting such a successful history in football, it comes as no surprise that betting on this sport is extremely popular.

### Business Case:
The proposed project aims to develop a predictive analytics tool that forecasts soccer match outcomes based on player ratings from the last year. By leveraging historical data, machine learning algorithms, and player performance metrics, this tool will offer valuable insights to stakeholders in sports betting, fantasy football, team management, and media analytics. The tool is expected to improve decision-making, optimize resource allocation, and enhance fan engagement.


## Web Scraping and Data wrangling
Webscraping tools **beautifulsoup** and **Selenium** were utilized for extracting data from the website "www.fotmob.com". Relevant updated data for machine learning models were selected and scraped from the website. 

## Data Cleaning and Transformation
The process involved taking care of missing values, separation of attributes, merging dataframes, and modifying datatypes to name a few.


## KPIs
For the sake of the size of the project and the available timeframe, the following KPIs were selected and analyzed for building the machine learning models.
-Goals Scored
-Player Ratings
-Player Market Value
-Player Age
-Opposition Teams

## Hypothesis Testing 

1. Higher player ratings lead to more goals
H₀: There is no relationship between player ratings and goals scored.
H₁: There is a positive relationship between player ratings and goals scored.
        
   Pearson correlation coefficient: 0.4652110616102631
   P-value: 2.4203862908908257e-229

2. Players tend to score more against certain opposition teams
H₀: There is no significant difference in the number of goals a player scores against different opposition teams.
H₁: There is a significant difference in the number of goals a player scores against certain opposition teams.
    
   Pearson correlation coefficient: 0.4652110616102631
   P-value: 2.4203862908908257e-229





## Data Preparation for Machine Learning:
Feature Selection
Feature engineering
One-hot encoding


## Machine Learning Models used:
  KNN 
  Linear Regression
  Decision Tree
  Random Forest

## RESOURCES:

Presentation slides link: https://www.canva.com/design/DAGP6oPLBz8/EKd0cotLCzDX4BbMIKxc6w/edit?utm_content=DAGP6oPLBz8&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton

Tableau link: https://public.tableau.com/views/ProBet/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link


## Planned development:
There is still room for improvement which with availability of time and resources will be implemented.
1. Make the project modular.
2. Implementation of .py file.
3. Explore more data points for machine learning.
4. Improve the machine learning models
5. Improve Tableau dashboard to provide better insights
