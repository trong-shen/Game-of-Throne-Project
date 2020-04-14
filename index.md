# Project Title: Whose line is it for Game of Thrones?
## Team 6 members:
* Zhen Wang (Brandon)
* Tyler Mccluskey
* Jonathan Tang
* Rosanna Zhang
* Trong Shen

### Introduction:
Team 6 consists of a group of Game of Thrones (GOT) fanatics who want to join their passion in data science with GOT. We decided to pull an existing GOT script on Kaggle and perform data analysis, natural langauge processing, and machine learning to gain insights on this GOT script. 

### Source Data Set: 
* Game_of_Thrones_Script.csv* saved in this repository from [Kaggle](https://www.kaggle.com/dasbootstrapping/game-of-thrones-episode-data)
* We cleaned up the above csv from Kaggle and saved a clean version in our repository named "Game_of_Thrones_Clean.csv"
- Use all of season 1 data and some of season 2 data

#### Research Questions:
1. What insights can we draw from Game of Throne characters' script?
2. Can we predict with our model which house the speaker of a given line belongs to?

#### Our work are summarized in two Jupyter Notebooks stored in this repository:
* For data analyis:
  - GOT_analytics_part_1.ipynb
* For Machine Learning/ Predictive Model:
  - GOT_predictive_model_part_2.ipynb 

#### Data Analysis
##### We performed data anlytics on all the season, and obtained some interesting findings:
* We found that speaking lines in the show remain somewhat consistent but dropped in the last season because the last season is more action-filled rather than dialogue-filled.
* House Stark had more speaking lines in the show in the first season, but then surrendered more lines to House Lannister and Targaryen as the show progresses.
* We found that majority of the speaking lines for every season are spoken by dead characters. Perhaps not dead in the season, but dead at some point in the show
* We showed a positive correlation between total salary paid to an actor/ actress vs number of words spoken by his/her character 
* Daenerys get paid the most dollar per word, while Tyrrion having spoken the most number of words.
* We created word cloud showing what words were most widely spoken based by each cahracter and each house
- Lannsiter's top words are father, king, and good
- Stark's top words are lord, father, and never
- Targaryen's tops words are dragon, take, and men

#### Predictive Model
#### To limit the scope of our predicitive model we decided to use only Season 1 and part of Season 2 data for our model. We tried to predicit, given a line, which house is the speaker from? 
#### Key findings:
* Machine Learning Model to determine whose line it is:
  - Use Season 1 data set as a training set to predict whose line it is from season 2.
