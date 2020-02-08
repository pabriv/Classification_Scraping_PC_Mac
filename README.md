# Webscraping & Classification Model - PC vs Mac Gaming
#### February 2020

---


## Agenda
- [Key Objective](#Key-Objective)
- [Executive Summary](#Executive-Summary)
- [Model Overview and Evaluation](#Model-Overview-and-Evaluation)
- [Integrated Recommendations & Next Steps](#Integrated-Findings)
- [Sources](#Sources)


---

## Key objective

<B>Context:</B><br>
For too long, PC’s dominance in the Gaming, Enthusiast, and eSports space has gone unchecked.

Tim Cook, CEO of Apple is seeking to explore new market opportunities in order to reverse stagnant Apple unit sales.  Therefore Apple has recently hired a new executive to spearhead this initiative, named Cim Took.

Mr Took has scheduled time with you to discuss initial steps and analyses he will need.  In order to prepare for this meeting you turn to your favorite source of consumer sentiment: Reddit

Subreddits evaluated:
- PC Gaming Master Race
- MacGaming

<B>Key Objectives:</B>
- Pulse of the customer: Begin prototyping a Classification System for ongoing analysis of platform-agnostic gaming consumer comments.  Eventually this will expand to include sentiment analysis across various platforms (not just reddit) and customer targeting for ad campaigns
- Evaluate model – how accurately can it identify PC Gaming apart from Apple Gaming

---


## Executive Summary

- Key objectives: Prototype a Classification System for ongoing analysis of gaming consumer comments to track performance of Apple Gaming initiative.  Eventually model will expand to include sentiment analysis across various platforms (not just reddit) and customer targeting for ad campaigns

- PC Gaming Hardware Market is a large opportunity estimated to be over $23 Billion in 2017, shows strong growth and is dominated by PCs.  Apple does not currently have strong performing or price-effective solutions for this space

- PCs also dominate the Reddit gaming community as well as high visibility (60 million+ viewer) eSports events

- Over 3.5 Million records were scraped from Reddit however after duplicates and balancing classes 2100 per class were kept

- 7 distinct machine learning models were applied and SVC exhibited the highest accuracy and strongest ability to distinguish between PC & Apple Gaming with an R2 score of 0.8980 and ROC Curve with AUC 0.947 (showing strong performance with Sensitivity and Specificity)
Model Coefficients & Insights suggest gamers prefer custom builds with RGB, high performance and SSDs

- Recommendations:
    - Field survey to corroborate insights on customer gaming needs (e.g. FPS, CUDA cores, compatibility issues) to influence roadmap

    - Continue building out robustness of classification model:  additional feature reduction/refinement,  additional feature engineering, lemmatization, experiment with different platforms such as Amazon reviews, Newegg reviews, Twitter
    - Begin cultivating esports partnerships and cyberathlete sponsorships

---



## Model Overview and Evaluation


<img src=https://i.imgur.com/XzQijwC.png>


---


<img src=https://i.imgur.com/GAae6y6.png>


---


<img src=https://i.imgur.com/JGvHRnX.png>



---


## Integrated Recommendations & Next Steps

- Field survey to bring out insights on customer gaming needs (e.g. FPS, Cuda Cores, compatibility issues) to influence roadmap

- Customer segments to include:
        - Existing PC Gaming enthusiasts
        - Existing Apple fanboys
        - Esports athletes
        - Regular consumers (gauge gaming appeal)
        - Begin working on eSports partnerships and cyberathlete sponsorships
        
- Continue building out robustness of classification model:  additional feature reduction/refinement,  additional feature engineering, lemmatization, experiment with different platforms such as Amazon reviews, Newegg reviews, Twitter

- Apple to further evaluate addressing custom-builds either through easier installation of operating system or partnerships with component manufacturers (e.g. hardware + MacOS bundling), and RGBs

- Build financial multi-year projections to estimate Apple entry and cannibalization of PC Gaming market


---

## Sources

- https://www.idc.com/getdoc.jsp?containerId=prUS45584619  
- https://www.statista.com/statistics/507491/esports-tournaments-by-number-viewers-global/
- https://www.wepc.com/news/video-game-statistics/
- https://subredditstats.com/r/pcmasterrace
- https://subredditstats.com/r/macgaming
- https://www.reddit.com/r/pcmasterrace/
- https://www.reddit.com/r/macgaming/

---
