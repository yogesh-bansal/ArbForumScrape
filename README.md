# ArbForumScrape
Automated data pipeline to scrape all the Arbitrum Forum Data in nicely formatted Datasets


### Description

Our `ArbForumScrape` repo contains 2 R scripts which automatically pulls and parse the data in a nice structured CSV files for further analysis.


### Walkthrough

#### 1. Scrape all the governance forum data.

- `Rscript scrape.R`

#### 2. Parse all the data in nicely formatted CSV files.

- `Rscript parse.R`

<img src="www/UsersD.png" align="center"/>
<div align="center">User Statistics DataFrame in data/UsersDF.csv</div>
&nbsp;
&nbsp;
<img src="www/TopicsD.png" align="center"/>
<div align="center">Topics Statistics DataFrame in data/TopicsDF.csv</div>
&nbsp;
&nbsp;
<img src="www/RepliesD.png" align="center"/>
<div align="center">Replies/Comments Details DataFrame in data/RepliesDF.csv</div>
&nbsp;
&nbsp;
<img src="www/LikesD.png" align="center"/>
<div align="center">Likes on Comments/Replies Details DataFrame in data/LikesDF.csv</div>
