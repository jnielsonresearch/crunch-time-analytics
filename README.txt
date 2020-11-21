DESCRIPTION
  This is a group project within the course "Data & Visual Analytics" Fall 2020 at 
  the Georgia Institute of Technology. During a global pandemic, the National Basketball Association
  (NBA) finished the rest of the season in Walt Disney World, Florida in a first of its kind isolated 
  ‘Bubble’. We explore the effect on the NBA playoffs. We analyze how the factors that determine player
  and game outcome have changed without travel or fans at games. Explored data from the past 5 NBA
  Seasons.
  
INSTALLATION
  1) Clone or download repo
  2) Pip install requirements.txt ($ pip install -r requirements.txt)
  3) Install Tableau (not included in this repo)
  
EXECUTION
  1) Each folder performs an in-depth analysis
  2) Please follow instructions below for each

  Game Rotation Research
  1) Includes two jupyter notebooks data_gathering.ipynb for the data gathering, cleaning, and data merges 
     and Analysis.ipynb for data exploration, analysis and classification modeling of game rotation metrics 
     to predict expected outcomes (win/loss).
  2) Tableau dashboard file Dashboard - Game Roatation.twbx includes dashboards for player and team rotation 
     stats for the NBA playoff seasons 2015-2020. 
  3) Data sub folder hosts datasets created by jupyter notebook data_gathering.ipynb from nba_api feed.

  Hustle Stats Research:
  1) Includes two jupyter notebooks NBAHustleStats.ipynb for the data gathering, cleaning, and data merges 
     and Classification_models.ipynb for data exploration, analysis, data visualization, and classification 
     modeling of hustle stats to predict expected outcomes (win/loss). These jupyter notebooks can been run 
     on a local server or through Google Colab through the included link at the top of the notebook. 
  2) Tableau dashboard file Hustle Stats Analytics.twb includes dashboards for player and team hustle stats 
     for the NBA playoff seasons 2015-2020. 
  3) Data sub folder hosts datasets created by jupyter notebook NBAHustleStats.ipynb from nba_api feed.
  4) Charts sub folder png exports of Tableau dashboards used in final report and poster. 

  Shot Selection Research
  1) Includes two jupyter notebooks ShotSelectionStats.ipynb for the data gathering, cleaning, and data merges 
     and ShotSelectionAnalysis.ipynb for data exploration, analysis, data visualization, and classification 
     modeling of hustle stats to predict expected outcomes (win/loss). These jupyter notebooks can been run 
     on a local server. 
  2) Tableau dashboard file ShotSelectionVisualization.twb includes a shot chart interactive visualization for 
     the NBA playoff seasons 2015-2020. 
  3) Data sub folder hosts datasets created by jupyter notebook ShotSelectionStats.ipynb from nba_api feed.
  4) Charts sub folder png exports of Tableau visualization used in final report and poster.

  Team Composition Research
  1) Contains accumulated data from https://www.basketball-reference.com/ on team age, team continuity, 
  top players in the NBA Bubble, and results from difference in difference analysis performed in Excel.
