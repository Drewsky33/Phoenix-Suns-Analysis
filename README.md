# Phoenix-Suns-Analysis

## Introduction

The Phoenix Suns had a fantastic regular season that saw them enter the playoffs as the team to beat from the Western Conference and arguably the team to beat in the overall playoffs. They had the best record in basketball at 64(wins) - 18(losses). They boasted one of the better offensive ratings in the NBA with an offensive efficiency of 1.115 according to [Team Rankings](https://www.teamrankings.com/nba/stat/offensive-efficiency). However, the Phoenix Suns were beaten in the second round by the Dallas Mavericks in a major upset. What I'm going to do in this project is look at the playoff performances vs. their regular seasons for both sides of the ball. I want to try and see if there were any trends in their respective regular and playoff seasons and see if there were any things that they could have done differently on either side of the ball.

The first part of this project will be looking at field goal attempt heatmaps for the Suns and comparing the types of shots, the field goal percentage on those shots, the minutes played, and the number of points scored per game for each player. I'm hoping to see if there were any differences in the types of shot each player took from their regular season shot selections and if that had an impact on their offensive effiency in the playoffs.

### Project Workflow
- Scrape data from basketball reference. 
- Regular vs. Postseason shot analysis
- Defensive Analysis for the playoffs player by player
- Team Defensive Analysis
- What types of players should the Suns target in the offseason?
- Cluster Analysis of player types in the NBA

### Data
The data for this project was scraped using the nbaStatR package from [Basketball Reference](https://www.basketball-reference.com/). I took data related to the players shots, their x-y coordinates when taking those shots, and their general stats as well. 

### Code
- The heatmaps section of the code can be found [here](https://github.com/Drewsky33/Phoenix-Suns-Analysis/blob/main/ShotHeatmaps/PHXHeatmaps.Rmd) and was inspired by Dominic Samangy, his twitter username is: [@DSamangy](https://twitter.com/DSamangy).

### Project Questions
- Did players change the types of shots they were taking during the playoffs? If so, did that result in a lower effiency for that player?
- What was the overall performance of the Suns on the offensive side of the ball in the playoffs?
- Did the Suns struggle on defense? If so, who struggled?
- What was the Suns defensive rating compared to their regular season defensive rating?
- Should the Suns target a certain type of player in the offseason?

## Highlights

### Player Shot Analysis

![CP3_Heatmap](https://user-images.githubusercontent.com/77873198/172489831-1c2711de-7d9e-4540-85b2-02edd525634c.png)
