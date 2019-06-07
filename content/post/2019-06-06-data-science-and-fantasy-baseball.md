---
title: Data Science and Fantasy Baseball?
author: Ludmila Janda
date: '2019-06-06'
slug: data-science-and-fantasy-baseball
categories:
  - blog
tags:
  - blog
header:
  caption: ''
  image: ''
---

*Thank you so much to Anisha BharathSingh, who originally wrote this post for her blog, found [here](https://journeytodatascientist.blog/2019/05/24/data-science-and-fantasy-baseball/). We are reposting her post with her consent. If you are an R-Lady interested in writing a blog post or cross-posting a blog post on your own blog, please let us know (via email nyc@rladies.org or via DM on twitter @RLadiesNYC)!*

On Thursday, May 23, I attended my first R-Ladies NYC meetup! R-Ladies NYC is an organization that promotes gender diversity amongst the R community by organizing a series of events (including this meetup) to support women who want to learn R or want to share their experiences as R programmers.

### Drafting a Fantasy Baseball Team with R

This meetup included an interesting take on data science – using R to draft a fantasy baseball team! This was presented by Angeline Protacio, a self-employed data scientist at Protacio Analytics LLC.

Outside of work, Angeline spends her time playing fantasy baseball. For those not familiar with fantasy baseball, as Angeline explained, you create your own fantasy baseball team with real players from any existing team. Each day, you decide what your lineup will be, and how well your team does depends on each players actual performance that day.

Angeline wanted to use her data science skills to draft a competitive fantasy baseball team. To do so, Angeline used a series of [player scoring categories](http://m.mlb.com/glossary/standard-stats) including: R, HR, RBI, SO, SB, OPS, WAR. She first took a look at how a player’s position affected their scoring categories with ggplot visualizations. From this, she found that outfielders had better offensive stats and suggests to draft your outfielders first.

**Create a Metric Comparing Overall Performance for Players**

Next, in order to determine which specific players to draft, Angeline tried looking for a summary statistic of all scoring categories to compare all players to each other, but could not find any. While there is the WAR (Wins Above Replacement) scoring category that summarizes a players contribution to their team, this only does so with respect to being substituted by a replacement player.

This led her to creating her own metric. With the help of the tidyverse package she: 1) filtered for players who had an average plate appearance above 300; 2) selected player id, position, Name, Team and all scoring categories; and 3) mutated her data frame with the players information to include a z-score for each scoring category.

This z-score is used to determine how much better a player performed than the mean for that category. Summing these z-scores provided an overall performance metric for each player in comparison to all other players.

**Top MLB Players of 2018**

Using her new metric, Angeline arranged her new data frame in a descending order to find the Top 5 MLB players for 2018:

1. Mike Trout (Angels) – total z-score: 11.889
2. Giancarlo Stanton (Yankees) – total z-score: 11.869
3. Nolan Arenado (Rockies) – total z-score: 8.766
4. Bryce Harper (Phillies) – total z-score: 8.646
5. Anthony Rizzo (Cubs) – total z-score: 8.343

[Click Here](https://github.com/angelinepro/rladiesnyc_may2019) for the repository with all of Angeline’s code.

While this only accounts for one part of drafting a fantasy baseball team, this just goes to show that you can use data science for pretty much anything!