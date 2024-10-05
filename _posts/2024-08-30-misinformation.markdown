---
layout: post
title:  paper published in Scientific Reports
description: Early morning hour and evening usage habits increase misinformation-spread
date:   2024-08-30 15:01:35 +0300
image:  '/images/misinformation.png'
tags:   [paper]
---

Social media manipulation poses a significant threat to cognitive autonomy and unbiased opinion formation. 
Prior literature explored the relationship between online activity and emotional state, cognitive resources, sunlight and weather. 

However, a limited understanding exists regarding the role of time of day in content spread and the impact of user activity patterns on susceptibility to mis- and disinformation. 

> Our paper uncovers a strong correlation between user activity time patterns and the tendency to spread potentially disinformative content. 

Through quantitative analysis of Twitter (now X) data, we examine how user activity throughout the day aligns with diurnal behavioural archetypes. 
Evening types exhibit a significantly higher inclination towards spreading potentially disinformative content, which is more likely at night-time. 
This knowledge can become crucial for developing targeted interventions and strategies that mitigate misinformation spread by addressing vulnerable periods and user groups more susceptible to manipulation.


![bird]({{site.baseurl}}/images/misinformation2.png)
*Factors influencing the spread of mis- and disinformation, containing daylight, time of day, human diurnal activity, (pseudo) chronotype, and the COVID-19 pandemic. We use the term (pseudo) chronotype to refer to user archetypes based on diurnal tweeting activity.*


### Four archetypical activity patterns
Our analysis focuses on the individual usage patterns on Twitter and their daily fluctuations. 
To that end, we first compute the average posting activity of each user over the day, including Tweets, Retweets, and Replies. 
We then use k-means clustering to group the average posting activity curves. 
The analysis reveals the presence of three distinct clusters with unique patterns of posting activity. 


![smoothed]({{site.baseurl}}/images/misinformation3.png)
*Smoothed diurnal activity ((a) and (b), see “Diurnal cluster activity”) as well as the ratio of potentially disinformative content posted per cluster ((c) and (d), see “Content type ratios”). For each cluster, the one (or two) highest peaks of activity and ratio are annotated with their time of occurrence. The shaded area in panel (b) stresses the closeness of peak activity after inferred awakening across the clusters.*

> Evening types spread most potentially disinformative content, infrequent posters the least

The clusters show distinct features beyond their typical activity patterns. 
In particular, we find a significant association between potentially disinformative content type and cluster affiliation.


### Potentially disinformative content spreads at night
While the total number of posts per user is positively correlated with an increased ratio of potentially disinformative content, heightened activity at a given time of day is negatively correlated with spreading potentially disinformative content at that time. 
This correlation is significant for all clusters except for evening types, and significant for all clusters when considering smoothed content type ratios only.


![clocks]({{site.baseurl}}/images/misinformation4.png)
*Each panel displays per cluster: the cumulative number of posts with known reliability classification throughout the day (coloured areas), the cumulative ratios of potentially disinformative content types (red lines), the user’s 8 least active hours (inferred prolonged wakefulness, grey inner arc), and the times with the highest quartile of potentially disinformative posts (red outer arcs). The axis scales are shared between panels.*


## Citation

Link to our paper: [Scientific Reports](https://www.nature.com/articles/s41598-024-20233-4)
Stockinger E, Gallotti R, Hausladen CI. Early morning hour and evening usage habits increase misinformation-spread. Scientific Reports. 2024 Aug 30;14(1):20233.
