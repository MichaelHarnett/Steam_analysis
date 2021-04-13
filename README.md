# Regression_Metis

## Description of included Jupyter notebooks

scraping_page - work for finding all desired information from individual game pages <br>
scraping_list - work for finding list of all games from Steam's list of games <br>
final_scraping_pipeline - putting previous together to scrape both the list of games, as well as the information from each game in the list, and merging together<br>
df_editing - used for creating and saving dataframes from totaldf filtered on desired rows/columns<br>
modeling_work - used to begin to make linear regression models



## data included in data folder

gamesdf1 - list of games, and their page links,  from scraping the list from steam's site<br>
games_joined - final concat list of all scraped pages<br.
totaldf - gamesdf1 and games_joined into to final df with all desierd features<br>
prelimdf - totaldf filtered to only inlcude rows that have total reviews, and only include numerical features, to create a base model for MVP<br>

