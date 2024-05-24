# PGA Championship Project

[Summary](#Summary)
[Observations](#Observations)
[Conclusions](#Conclusions)
[Expansion](#Expansion)
[Slides](#Slides)
[Install](#Install)
[Development](#Development)
[Contributors](#Contributors)


## Summary

This project is an exploration of scoring data from the 2024 PGA Championship held at Valhalla Golf Club in Louisville, Kentucky from 16-19 May 2024. The Championship was won by Xander Schauffele with 263 strokes, 21 under par for the 4 rounds played.

The project seeks to dig further into the scoring data from the competition to uncover the areas that enabled the top 10 players to outperform the field and Schauffele himself to win the title. The insights gleaned from the data could then be used to inform future player training plans and prepare them for similar low-scoring events similar to the conditions found at Valhalla. 

The presentation of the data also includes a brief primer on certain technical terms used in golf for an audience unfamiliar with the terminology.

## Observations

The following trends were observed in the data:
* While players towards the lower end of the top 10 performed well in two areas of strokes gained (SG), often recording 75% of their SG in 2/4 areas, the top two players (Schauffele and De Chambeau) had SG of 4 or above in 3 distinct categories.
* Schauffele's winning formula included 3rd place for SG off the tee, 2nd for SG approach to green and 1st for Greens In Regulation (GIR). 
* The 6th hole was the hardest hole on the course, playing 0.228 over par.
* The Top 10 players recorded 3/111 bogeys on 6th hole and 5/38 birdies on the 6th hole. 

## Conclusions

Based on the above observations, the following can be concluded in relation to this edition of the PGA Championships:
* The low-scoring environment at Valhalla demanded top players to perform well regarding SG in **more than two** areas. In situations where low-scoring is prized, a complete game is more of an advantage than specific areas of strength.
* While low-scoring was a priority throughout the course, hole 6 was a particular challenge that rewarded consistency as shown by the results of the top 10. Accounting for a small number of the non-par scores recorded on the hole, the top 10 demonstrated that getting through such holes in par was preferable to attempting to score on this hardest of holes.

## Expansion

Additional areas to explore in the data might include:
* **Consistency**: What was the ratio of birdies : pars : bogeys for the top players and how did it compare to the rest of the field?
* **Bounceback score**: For players carding bogeys, how often did they manage to "bounceback" with an under par score on the following hole, did players that successfully did this perform better in the Championships overall?
* **Overnight momentum**: Did players that carded a low round for one round successfully continue that momentum into the following round? 

## Slides

The slides presenting the analysis can be found at: https://docs.google.com/presentation/d/1NpPlTPxL_l2qf8_l02UDo5ZwHR8cHBUiDGCgKO-D6ZE/edit?usp=sharing

## Install

The data cleaning and visualisations used the following packages:
* numpy
* pandas
* beautifulsoup4
* json5
* requests
* selenium
* PyYAML

The versions for the above packages can be found in the requirements.txt file.

## Development

Data was scraped from the PGA Tour website on the championships page using Selenium and BeautifulSoup packages and parsed using the json package.

The code was developed in Jupyter Notebook with supporting markdown and YAML documents in SublimeText.

## Contributors

mhga94