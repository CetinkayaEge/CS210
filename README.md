# CS 210 Term Project: League of Legends Player Performance Analysis
## Introduction:
As a longtime League of Legends player I have always been interested in the factors that affect my performance in game. This project will explore my League of Legends performance using the data from my league of legends match history and my spotify listening activity. The goal is to identify patterns and insights that could improve my gameplay and overall experience.
## Data Sources:
### League of Legends:
#### Riot Api: I will use the riot api in order to retrieve my match history data and match details.
#### Web Scraping: The riot api supports matches till a certain point in time so  in order to get matches further back in time I will scrape third party websites that collect and store match history of players.
#### Key Data points to Include:
- Date and time of the match
- Match duration
- Outcome of the match
- Champion played
- Position/role played in the match

### Spotify:
I will use the spotify's get personal data feature to get detailed listening information.

#### Key Data Points to Include:
- Song name and artist
- Date and time
- Song duration
- Tempo

## Project Plan:

### 1)League of Legends Data
- I will retrieve data from riot api using and web scrapping for matches beyond api's limits.
- Remove irelevant matches such as for fun game modes that differ from normal gameplay
### 2)Spotify Data
- I will retrieve data from spotify using the spotifys get user data feature and format the data.
### 3)Integration of Data Sets
- According to the game date, time and duration of a match I will map the songs to the game matches.
- Calculate the duration of music listened through that game and the average tempo
### 4)Analyze and gather my winrate through the condition changes such as:
- time of day 
- day of the week
- tempo of the songs
- number of games played that day.
- duration of the game
- ratio of game duration and music listened duration
### 5)Create tables and plots to visualize the data.
### 6)Identify the patterns and relationships through these factors.
- My win rate drops as the game gets longer
- My win rate is positively correlated with my KDA ratio
- My asisst mostly contribute my KDA
- Reject null hypothesis that kda doesn't effect win rate since p value is smaller than 0.05


