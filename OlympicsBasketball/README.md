# Basketball Olympics

In this little project I am exploring data about Men's Basketball at the 2020 Summer Olympics. When this project was written, only the First Round of the tournament had taken place.

## 1. Files

### 1.1. Jupyter notebooks

- **WSOlympicsBasketball.ipynb**: here I describe how I obtained **basketball_olympic_players_game_stats.csv** dataset with web scraping of [International Basketball Federation (FIBA)](https://www.fiba.basketball/).
- **DWOlympicsBasketball.ipynb**: transformations of **basketball_olympic_players_game_stats.csv** that led to **curated_basketball_olympic_players_game_stats.csv**.
- **EDAOlympicsBasketball.ipynb**: some exploratory data analysis of **curated_basketball_olympic_players_game_stats.csv**. TO BE UPLOADED.

### 1.2. Datasets

- **basketball_olympic_players_game_stats.csv**: the dataset generated in **WSOlympicsBasketball.ipynb**.
- **basketball_olympic_players_game_stats.csv**: curated dataset, produced with **DWOlympicsBasketball.ipynb**.

### 1.3. Dataset annotations

- **basketball_olympic_players_game_stats.json**: description and datatype of the columns in **basketball_olympic_players_game_stats.csv**.
- **curated_basketball_olympic_players_game_stats.json**: description and datatype of the columns in **curated_basketball_olympic_players_game_stats.csv**.

## 2. Usage

You can run this notebook in Google Colab. Find links in section 1.1 of this README file.

Also, after cloning this repository, you can run this notebook locally after running the following lines (Linux):

```
pip install -r requirements.txt
python -m ipykernel install --user --name=OlympicsBasketball
```

Then, open whichever notebook you want and select **OlympicsBasketball** kernel.
