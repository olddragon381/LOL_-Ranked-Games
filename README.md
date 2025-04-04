﻿# LOL-Ranked-Games- Data Analysis on (LoL) League of Legends Ranked Games
📁 Dataset
Source: [[Provide source link if available]](https://www.kaggle.com/datasets/datasnaek/league-of-legends)

Description: Analyze LOL data to increase the winning probability of a ranked match

This is a collection of over 50,000 ranked EUW games from the game League of Legends, as well as json files containing a way to convert between champion and summoner spell IDs and their names. For each game, there are fields for:

Game ID
Creation Time (in Epoch format)
Game Duration (in seconds)
Season ID
Winner (1 = team1, 2 = team2)
First Baron, dragon, tower, blood, inhibitor and Rift Herald (1 = team1, 2 = team2, 0 = none)
Champions and summoner spells for each team (Stored as Riot's champion and summoner spell IDs)
The number of tower, inhibitor, Baron, dragon and Rift Herald kills each team has
The 5 bans of each team (Again, champion IDs are used)

Data Preprocessing: clean missing values, removing outliers, data normalization

🛠 Technologies Used
Programming Language: Python 

Tools: Google Colab / Power BI 

🔍 Data Analysis
Summary :
- The impact of First Blood on victory
- The impact of taking the first tower on victory
- The impact of match time vs win rate
- The 10 most banned positions in Team 1
- The 10 most banned positions in Team 2
- The 10 most choose positions in Team 1, 2
- Train model Win Prediction
  
📊 Results and Insights
![image](https://github.com/user-attachments/assets/ba51d1a4-7301-455e-a73b-4789cc2a8fa4)
![image](https://github.com/user-attachments/assets/5d9aa816-f6dd-474f-b0ed-27675093033e)
![image](https://github.com/user-attachments/assets/111a2d40-f4ae-4747-b442-cec9bd3bd5ce)
![image](https://github.com/user-attachments/assets/9fcd0fb0-11ad-499d-89a7-85cae9c1d386)
![image](https://github.com/user-attachments/assets/1089fbfd-5925-46c9-8101-c2109a8e78eb)
![image](https://github.com/user-attachments/assets/22add584-850a-4327-9803-447b14e17596)
![image](https://github.com/user-attachments/assets/76a4b1ce-432d-44d8-8d3a-943616ee27b0)
![image](https://github.com/user-attachments/assets/7e022fc6-5edc-4e65-b387-ed3af91fe0ea)
