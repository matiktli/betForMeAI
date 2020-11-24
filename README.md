# BetForMeAI - betting for lazy ppl

## Introduction
### Goal
I would like to earn some easy $$$ on betting while not knowing much about teams and their performance.  
We gonna focus on Premeir League 

### Data Sources
* Archive matches data - [FootballData](http://www.football-data.co.uk)
* Players statistics - [FifaIndex](https://www.fifaindex.com)
* Match stats/lineups - [FootballLineups](https://www.football-lineups.com)
* Sport news - [EyeFootball](https://www.eyefootball.com/archive)
* Weather - []()
* Social media - ?

## Data Modeling
### Input Data - general
1. Team Stats - very general, but worth including.
2. All Players Stats - FifaIndex stats of players, good estimator on their general skill.
3. Lineups - main team + subs.
4. Formation - vector (I need to find link to this guys github, he done it nicely).
5. Last N Matches Stats - ? Not sure how much include there.
6. Sport News - ?
7. Social Media Posts - ?

### Data Gathering - workflow
![BetForMeAI-workflow](https://github.com/matiktli/betForMeAI/examples/images/BetForMeAI_flow_v1.png?raw=true)

### Data Transformation
:construction:

## Reinforecement Learning
### Model Definition
:construction:

## Additional Things
### Useful Sources
* Low level YT video about ML and football - [link](https://www.youtube.com/watch?v=6tQhoUuQrOw). Some algorithms that might be worth looking at.
* Paper about ML and Cricket - [link](https://arxiv.org/pdf/1511.05837.pdf). Same concept as we doing described in more proffesional terms.
* Low level article about ML and football - [link](https://dashee87.github.io/football/python/predicting-football-results-with-statistical-modelling/). Nice concept on how to put it all together, using betfair.

### TODO List / Open Questions
* How to, in what format, include that the team is having some european league matches preceding or following the given match?
* How to, in what format, include team commitment to the match? For example it might be end of league and they are safe to lose + they might have matches in other leagues as well, so pointing up to point above.
* ...
