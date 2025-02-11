# Excel_DecisionTool_Managerzone

## What is this all about?

ManagerZone is a sports manager played in a web browser. The game was created by the Swedish studio Power Challenge in 2001. It focuses on two sports: football and ice hockey. The first football season started on September 26 2001, and the ice hockey season started on August 18 2003. It is the oldest multiplayer sports manager.
The purpose of the game is to develop your team through, for example, training and trading with other teams to move up in the divisions and finally win the league title. The match results are generated via match simulator, a program that calculates the match results taking into account the team's skills, tactics, etc. Since 2006, it has also been possible to watch the matches in 3D.


## Project Purpose

I was created three-module tool to help help beginner and advanced managers develop their team. Every manager need to make some strategic decision such as:
1. Which players should start in starting 11?
2. What position does a given player perform best / worse?
3. Is it worth investing in a given youngster?
4. Which position is optimal for a player?
5. How is the team doing compared to league rivals?

## Tools

This is my first project so i decided to use quite easy and accesible tool. All of work was made in Microsoft Excel with Power Query and Power Pivot with element of DAX expressions.

### Data Tables

All tables was stored in Excel Spreadsheets. There are **Players**, **Match_Players**, **Match_Info** and **Clubs**.


### Data Model

![power_pivot_datamodel](https://github.com/MaciejGulaj99/Excel_DecisionTool_Managerzone/assets/142632444/d1294056-fb0b-496b-86ad-60b9c95bc402)

There is a **Match_Players** table which collect data about match facts for every player, who took part in it.

**Players**, **Match_Info** and **Clubs** have different role. They are describing things in the model. A dimension table contains a key column (or columns) that acts as a unique identifier, and descriptive columns.

## First Module: Dashboard


![obraz](https://github.com/MaciejGulaj99/Excel_DecisionTool_Managerzone/assets/142632444/88eb09f6-2449-4383-8147-a2a57426eca7)

This is graphical representation of statistics from fact table. Every user can see how given player or whole team doing.

Slicers helps filter all of the data. I recommend start filtering with *Team_Name* slicer and go forward to next ones: *Player Name*, *Match Name*, *Match Type*



## Second Module: Comparison

This module help understand how good your players are compare to others from common league.

Select specific team, player, position and type of match to compare with other player.




## Third Module: YoungsterPotential
