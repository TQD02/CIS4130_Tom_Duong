**Overview:**
An interest in games lies in many of us—including myself—but only a few have found significance in the data behind those games. I grew up playing Clash Royale, and encountering a large dataset from the game’s top players sparked a deep curiosity in me. As described on the Clash Royale Wiki, the game is “a fast-paced brawler where you collect cards and duel players in real time. Destroy your opponent's Crown Towers, but be sure to defend your own.” Each match features two players, each with a deck of eight character cards that can be deployed using a finite elixir resource.

**Dataset:**
The dataset I’m using is publicly available on Kaggle:
https://www.kaggle.com/datasets/s1m0n38/clash-royale-games/data

It consists of match statistics from top-ranked players spanning 15 seasons—from September 2022 to December 2023. Each row in the dataset represents a match and includes 23 columns, covering:
Match Details: Date, game mode, and other contextual info
Player Data (2 Players per Match):
Unique IDs
Trophy count before the match
Number of crowns left (the target variable)
8 cards used in the deck (represented as unit IDs)

**Objective:**
The goal of this project is to predict the number of crowns left in a match using the average elixir cost of each player’s deck, employing supervised learning techniques.

