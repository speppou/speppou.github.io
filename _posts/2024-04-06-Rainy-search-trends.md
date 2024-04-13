---
layout: post
title: Rainy search trends
categories: [Data Science]
---


It has been ridiculously rainy in Sydney in the last 24 hours with most of the city receiving over 100 mm of rain. 

This reminded me of an old pre-blog mini-project I did which is a sort of inspired by [this xkcd](https://xkcd.com/1876/) and this [article](https://www.washingtonpost.com/news/wonk/wp/2017/08/01/the-path-of-the-solar-eclipse-is-already-altering-real-world-behavior/) which uses Google search trends to predict the path of a solar eclipse. 

My idea is to use Google search trends for 'bom radar' as a predictor of how much rain is actually falling and see if you can see the difference between when NSW was in drought (El Nino) vs a period of back-to-back-to-back years of heavy rainfall (La Nina). 

Below is a plot of Google search trend data for 'bom radar' with the extended drought period from 2015-2019 highlighted in orange and the La Nina period highlighted in blue. The dotted horizontal lines are the minimum and maximum interest during the drought period.

<img src="{{ site.baseurl }}/images/2024-04-06-Rainy-search-trends/Bom_radar_trends_annotated.png" alt="Google search trends for 'bom radar' annotated with drought and non-drought times" width="500"/>

We can see that once the drought broke there is an increase in both the baseline and peak interest in 'bom radar' clearly showing that search activity can predict (or at least descibe) the weather. 