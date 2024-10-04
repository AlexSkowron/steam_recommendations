# Recommendation system for Steam Games

In this project I try to build an effective recommendation system for the online video game store [Steam](https://store.steampowered.com/).

The project comprises 3 sub-projects:
1. Building a database with relevant information using web apis and scraping methods. This sub-project is documented in the build_steam_database.ipynb notebook. This part is work-in-progress since retrieving the information (especially user data) is quite difficult and time consuming. In the meantime I am working with available [kaggle](https://www.kaggle.com/) datasets.
2. Implementing and testing collaborative-filtering (CF) recommender systems that rely on implicit user interactions (mainly game purchases and playtime). This sub-project is the most developed and the code is cleanly documented in the jupyter notebook CF_steam_recommender.ipynb. For noe, this sub-project uses the [steam 200k dataset](https://www.kaggle.com/datasets/tamber/steam-video-games) from kaggle for training and testing.
3. Implementing and testing of a content-based/hybrid recommender system (also) drawing on game meta-data (including ustructured data like game descriptions). This project is documented in CB_steam_recommender.ipynb and is work in progress.