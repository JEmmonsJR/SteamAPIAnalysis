# Steam Analyst project for Nashville Software School DA10

## Executive Summary

I love games and I love gaming. That's why my project will revolve around the gaming platform, Steam. The goal for this project is to use the Steam API and a website called SteamSpy to gain insight into game popularity and trends within Steam. By extracting and analyzing the relevant data, this project aims to answer ‘What is a good game?’ The assumptions are that fps(first person shooters) and other fast-paced games that have short match style game play will be the most popular, but games with a story that lasts 15-20 hours will have a higher average rating. Major challenges are definitely around gathering and cleaning the data.

## Data Question

My question is ‘What makes a good game?’ Specifically comparing user ratings and reviews, concurrent players, and pricing across different genres and individual games.

## Data Collection

The Steam API is kind of notorius for being a hard API to use to gain insights on all games on the platform. To assist with the gathering of data I used inspiration from a blog by Nik Davis [here](https://nik-davis.github.io/posts/2019/steam-data-collection/). The code for the SteamSpy API used in the blog was for an older version of the API. So I turned to the GitHub account [Duerkos](https://github.com/Duerkos/steam_analysis/blob/main/notebooks/1-data-collection-I01.ipynb) for and updated version of the code. I then updated the code from each source to be compatible with Python for 2024.

## Data Sources

[Steam API](https://developer.valvesoftware.com/wiki/Steam_Web_API)

[SteamSpy API](https://steamspy.com/about)

[Nik Davis's Blog](https://nik-davis.github.io/posts/2019/steam-data-collection/)

[Duerkos GitHub](https://github.com/Duerkos/steam_analysis/blob/main/notebooks/1-data-collection-I01.ipynb)
