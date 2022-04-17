# DQ R-Project 6: Creating an MLB Database
This is my sixth project in Dataquest towards my journey in R Programming. This project aims to create a Major League Baseball Games database based on the gathered statistics from the year 1800 until today. In this project, the following concepts are used to achieve the given problem:
- SQL Fundamentals
- SQL Joining
- Querying from SQLite

# Data source

The source of the main dataset can be accessed here (currently not present in this branch due to large size): https://dsserver-prod-resources-1.s3.amazonaws.com/376/game_log.csv

This dataset contains 171,907 rows and 161 columns.

Other datasets that were used in this file are as follows:
- park_codes - 252 rows and 9 columns
- person_codes - 20,494 rows and 7 variables
- team_codes - 150 rows and 8 columns
- appearance_type - 31 rows and 3 columns

# Variables

Here are the some of the variables that were used in the main dataset:
- Putout - A fielder is credited with a putout when he is the fielder who physically records the act of completing an out -- whether it be by stepping on the base for a forceout, tagging a runner, catching a batted ball, or catching a third strike.
- Innings played - Innings played is a defensive statistic determined by counting the number of outs during which a player is in the field and dividing by three.
- Assist - An assist is awarded to a fielder who touches the ball before a putout is recorded by another fielder. Typically, assists are awarded to fielders when they throw the ball to another player -- but a fielder receives an assist as long as he touches the ball, even if the contact was unintentional.
- Error - A fielder is given an error if, in the judgment of the official scorer, he fails to convert an out on a play that an average fielder should have made.
- Passed ball - A catcher is given a passed ball if he cannot hold onto a pitch that -- in the official scorer's judgment -- he should have, and as a result at least one runner moves up on the bases.
- Double Play - A double play occurs when two offensive players are ruled out within the same play. It's often referred to as "a pitcher's best friend" because it's twice as helpful toward his cause as any given out.
- Triple Play - A triple play occurs when the defending team records three outs on a single defensive play.

Here is a summary of the nature of variables for the other datasets:
- park_codes - contains details of where precisely a game has occurred, how long did the game ended, and which league played the game.
- person_codes - contains the details of each player (when they started playing, coaching, or managing).
- team_codes - contains the details of the team participating in the game (what the team is, how long they have been playing)
