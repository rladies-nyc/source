---
title: 'Benjana Guraziu: An RLady’s First R Conference'
author: Benjana Guraziu
date: '2018-06-27'
categories:
  - blog
tags:
  - blog
slug: an-rladys-first-r-conference
header:
  caption: ''
  image: ''
---

The 2018 [New York R Conference](https://www.rstats.nyc/) was my first ever R conference, and it was great. I’ll write here about my experience, with links to resources from the widely varying talks. 

First and foremost, I want to thank RLadiesNYC for the scholarship which allowed me to attend the conference. As a self-taught R newbie and incoming grad student, I greatly benefitted from attending this conference, and I so appreciate the opportunity from this great group! I would also like to thank [Jared Lander](https://www.jaredlander.com/) for his continued support of RLadies, and generosity in making opportunities like this possible. (Jared not only organizes this event, but also hosts regular meet-ups through the [New York Open Statistical Programming Meetup](https://www.meetup.com/nyhackr/) with presentations of past talks often available on [their website](https://nyhackr.org/presentations.html)–definitely check them out!)

# The Conference

![](/img/2018-06-27-an-rladys-first-r-conference/Hex Stickers.jpg)
NYR is a two-day conference that was held at [Work-Bench](https://www.work-bench.com/). A few hundred people attended the sold-out conference, and they came from as far as San Francisco and London. It was great to meet the fellow attendees and to learn about the different fields that they worked in. I was initially nervous going into the conference and wondered if I could possibly keep up with the conversations. But I was pleasantly surprised at how easy and fun it was to chat with everyone. Everyone was very friendly and open: we were all there to hear about R and to meet and get to know other R users. So even if we shared very little in subject area, geography, or career path, I still had a great time talking to attendees about their work, my work, the talks, and what types of pizzas might be available for lunch. It was amazing to meet and interact with the speakers also - the people building the tools that we use every day and #rstats Twitter celebrities were not only giving talks, but also hanging out and trying to eat humongous ice cream sandwiches tidily like the rest of us. This interaction was facilitated by the great planning by Jared and team, from the casual attire to the frequent breaks with caffeine, snacks, and drinks always available. This opened up so many opportunities to meet and chat with new people.

# The Talks

![](/img/2018-06-27-an-rladys-first-r-conference/Screen Shot 2018-05-20 at 12.23.59 PM.png)

NYR had a very large range of talks: from R tips to statistics, from machine learning to implementing R in an organization, and so much more. For a quick overview of the talks, check out Daniel Chen’s compilation of notes from Brooke Watson and Mara Averick: [https://chendaniely.github.io/r/2018/04/22/rstatsnyc/](https://chendaniely.github.io/r/2018/04/22/rstatsnyc/). Videos of all of the talks will be available on the [NYR website](https://www.rstats.nyc/), and past talks are already posted on the site so be sure to check it out. 

The most immediately applicable talk is probably [Emily Robinson’s](https://twitter.com/robinson_esv) the Lesser Known Stars of the Tidyverse. Emily’s talk was chock-full of tips and functions from Tidyverse tools that can be useful to your workflow. For example, if you print a large dataset it can take over your console. By using as_tibble() from the Tibble package, the first ten rows and only the columns that fit on your screen will print, making it much more manageable and still informative. For all of the tips, check out her [slides](https://www.slideshare.net/secret/sMVjYvcd7yh16z), and her [in-depth document](https://github.com/robinsones/Data-Day-Talk/blob/master/data_day_script_accompanying.md) from an earlier talk. 

One of the most fun talks was [Evelina Gabasova’s](https://twitter.com/evelgab) analysis of the Star Wars social network. Her [blog post](http://evelinag.com/blog/2015/12-15-star-wars-social-network/index.html) does an amazing job of analyzing the connectedness and centrality of characters from the movies, and suggests a hypothesis for why the prequels are just not as compelling as the original trilogy. 

RLadiesNYC had great representation at the conference. [Brooke Watson](https://twitter.com/brookLYNevery1) gave another super fun and informative talk about her package-development journey. In her [presentation](https://github.com/Brooke-watson/nyr) and [blog post](https://blog.brooke.science/posts/scraping-javascript-websites-in-r/) Brooke details how she first became inspired by the beepr package, which allows you to play a sound when a script is finished running. She built upon this idea with the BRRR package, which plays rap snippets. Two Emily’s represented, with aforementioned Emily Robinson and [Emily Zabor](https://twitter.com/zabormetrics). Emily Zabor [taught us](https://github.com/zabore/slidedecks/blob/master/nyr2018_zabor.pdf) about survivor analysis in cancer research and how these prognoses are determined. As an incoming biostatistics student, I was very gratified to learn from Emily about this incredibly important topic in health research. Survival analysis is a complicated process, and has huge impacts on patients and families. But, Emily pointed out that this type of analysis is actually quite common: we are often curious about time-to-event endpoints in many contexts, like time to heart attack, time to onset of substance abuse, or time to machine malfunction. In all of these contexts it is important and difficult to get it right. 

These are just a sampling of the talks at NYR. From [Minecraft](http://blog.revolutionanalytics.com/2018/04/minecraft-robot-in-r.html) to Machine Learning, it seemed like if there was any topic you were curious about it would be covered, and then some. 

# RLadies

![](/img/2018-06-27-an-rladys-first-r-conference/IMG_5347.JPG)

This post would be sorely incomplete if I didn’t talk about the huge impact that RLadies has had on me. I learned about RLadies a little while ago, and initially wondered if it would be appropriate for me to go to an event. Did I know enough R? Would I be totally out of place? Then I went to a book club, where the conversation was interesting and the people were friendly and warm. I was hooked. I went to every event I could after that, and developed some kind and awesome new friendships. It made all the difference at my first R conference to already have friends from RLadiesNYC at the conference, and to have familiar faces to gravitate towards whenever I needed. To go along with my gratitude to RLadiesNYC, the most important thing to impart about this conference is how friendly it was. The R community in general is very friendly, with lots of encouragement and support available on [Twitter](https://twitter.com/hashtag/rstats?src=hash), the [community pages](https://community.rstudio.com/), and wherever else a learner might encounter fellow R users. This absolutely carries through in real life. I can't emphasize enough how nice everyone was at NYR. Everyone was super approachable, from attendees to speakers, and this made the learning a lot more fun. 

R is an awesome language, but I wouldn’t be this excited about it if I weren’t so excited about the people that are in this community. NYR was a great conference that really highlighted the strength of the R community. A telling example of this is the community's constant drive to improve. As Brooke Watson commented, it was very exciting that there was now a line for the women's bathroom! Indeed, gender diversity among speakers was better than many other technical conferences I’ve seen. However, as was highlighted by Emily Robinson, diversity is a big ongoing effort and the community is trying to improve it in the coming years. RLadies in particular is committed to increasing diversity in general in the R community, and welcome any ideas to this end. This conscientiousness and the general warmth of the R community give me full confidence that great strides will be made, and I can’t wait to attend NYR again in the coming years. 


