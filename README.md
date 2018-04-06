# DSI-Capstone

This is the initial repository for my Data Science Immersive Capstone.  I will continually add to it as my project work is turned into my instructors at General Assembly.

## Table of Contents
- [Introduction](#introduction)
- [Part One: Capstone Topic + Data Validation](#part-one)
- [Part Two: Problem Statement + EDA](#part-two)
- [Part Three:  Progress Report + Preliminary Findings](#part-three)
- [Part Four: Report Writeup + Technical Analysis](#part-four)
- [Part Five: Presentation + Recommendations](#part-five)
- [Resources](#resources)

## Introduction

I have long since been a huge fan of College Basketball.  It's been a part of my family for nearly 30 years as well.  I don't really watch much NBA (if any), but I definitely tune in to college basketball games throughout the winter. I often try and get out to a basketball game as often as I am able throughout the regular season that normally runs from November to the second week in March.  While I was living in Upstate New York I attended the MAAC Tournament in Albany in 2014, and made my way to either Syracuse or Connecticut to see their Men's teams play.  I also would go down to Madison Square Garden in New York City to the Jimmy V Classic which featured two marquee games in one night.

In addition to that, I've been extremely fortunate to have been to over 10 Final Four games in my life.  My very first Final Four was in San Antonio in 1998.  After that I went to Final Fours in 2000 (Indianapolis), 2002 (Atlanta), 2004 (San Antonio), 2005 (St. Louis), 2006 (Indianapolis), 2007 (Atlanta), 2008 (San Antonio), 2010 (Indianapolis), 2011 (Houston), and finally 2018 (San Antonio).

I've also attended several tournament games from the initial 64 to the Sweet 16 games.

## Part One:  Capstone Topic + Dataset Validation  

It made sense to me to use what I've learned these past few weeks to develop a model to predict the games in this year's tournament.  Granted the tournament will have just been completed when this project will be presented, I feel that it will make a great exercise to flex my Python and Machine Learning muscles to do something I truly enjoy doing.

## Part Two:  Problem Statement + EDA

The problem is fairly easy to define.  What does it take to make a Champion for the NCAA Men's College Basketball Tournament?  Is it the seedings?  Is it the fan engagement (does the team travel well)?  Does it involve some kind of intricate basketball analytics?  Or is it pure heart and maybe a little bit of luck?

The data for this project is a combination of data provided by the [Kaggle Competition](https://www.kaggle.com/c/mens-machine-learning-competition-2018) sponsored by the NCAA and Google Cloud.  I've also added data from the first page of [Ken Pomeroy's Website](https://kenpom.com/) which is provided free of charge. Ken also provides much more in-depth analytics but is not readily available free so was not used for submission to Kaggle but may be used later in my model as I go along to the final presentation.

Here is a quick description of the data that I will be using for this project:

- Cities - List of cities and states that have Division I teams
- Conferences - List of all the Division I conferences across the country since 1985.
- ConferenceTourneyGames - Conference Tournament Games (ACC Tournament/SEC Tournament, etc.)
- Events 2010-2017 - Play by play for all games from 2010 to 2017
- GameCities - Cities where games have been played since 2010
- MasseyOrdinals - Weekly team rankings from various sources such as Pomeroy, Sagarin, ESPN, RI, etc. 
- NCAA Tourney Compact and Detailed Results - The primary Test set for the model
- NCAA Tourney Seed Round Slots - represents bracket structure of the Tournament
- NCAA Tourney Seeds - Seeds for all teams in every tournament since 1985
- NCAA Tourney Slots - Mechanism by which teams are paired against each other
- Players 2010-2017 - Data on all the players that have played in Division I college basketball games
- Regular Season Compact and Detailed Results - Stats on every game played in the regular season
- Seasons - Identifies the different college basketball seasons
- Secondary Tourney Compact Results - Results from NIT or other post season tournaments
- Secondary Tourney Teams - Teams that have played in these secondary tournaments
- Team Coaches - All coaches and the teams they've coached
- Team Conferences - All the conferences in Division I
- Teams - List of teams
- Team Spellings - Long form spellings of each Team

Initial EDA of the datasets provided is centered around making sure to create columns and/or rows for each team whether they won or lost a game.  EDA will also include a great deal of feature engineering using different sets of analytics freely found around the Internet.  Each source will be referenced below.

## Part Three: Progress Report + Preliminary Findings

The original submission to Kaggle was done on March 14th, the day of the deadline.  Subsequent model evaluation was done after the tournament already started but not using any of the results from the actual tourney as it was going on.  The final Kaggle score after the tournament end was 0.698145 and ranking of 736.  That was definitely not very good.

## Part Four:  Report Writeup + Technical Analysis

Technical report has been uploaded as a PDF and details the background, the models, and the results found in the project.

## Part Five:  Presentation + Recommendations (due 4/10/2018)

## Resources

[NCAA Men's Tournament Kaggle Competition](https://www.kaggle.com/c/mens-machine-learning-competition-2018)  
[2018 Pomeroy College Basketball Ratings](https://kenpom.com/)  
[NBA Analytics 101 Primer by NBAStuffer](https://www.nbastuffer.com/analytics-101/)  
[Rusty LaRue: Player Efficiency Stats](http://www.rustylarue.com/more-than-94/player-efficiency-stats)  
[FiveThirtyEight: Calculating NBA Elo Ratings](https://fivethirtyeight.com/features/how-we-calculate-nba-elo-ratings/)  
