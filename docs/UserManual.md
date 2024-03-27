# User Manual

## Quick Tips

* You can go to the welcome page by clicking on the rotating image of the basektball next to the title header of every page

* On the welcome page at the bottom there is a tiny box with the picture of a speaker, that can be clicked to turn off and on the sound that is being played when the welcome page boots up

## Home Page
This is the homepage where you can search for a specific players, teams, game dates and game stats. In addition, we also implemented database to help us track user's favorites searches, such as searched players and teams; this give us an idea of the popular players/teams user are interested.

* Search players:
You can search a specific player by their first or last name! After a successful search, it will display information about the player's Name, Team, Position, Height and Weight, etc.
* Search Teams:
This option allows you to search for a team that you are interested in; you can search by the team's city or nickname, whichever you like, and it will display that team's information such as their full name, abbreviation,, their city, conference and their division,
* Search Date:
This option allows you to search for games on a specific date! Either in the past or in the future. For example, if you search for a date in the past, it will display information about what teams were played on that day and their scores; if you search for a future date, it will show the upcoming games to watch!
* Search Stats:
This option allows you to look into the statistics of games played on a specific date! If you search for a date, it will display information such as the final score, the home/visitor's team stats, including each player's gameplay (Number of Points, Assists, Rebounds, Blocks, and Steals)


## Players Page
On this page you can compare the different stats of up to five NBA players. Here the stats are illustrated through the users choice of a bar graph or line graph. When the user first comes acrross the page, a default chart of the Top NBA Players of 2023 by Total Career Points will be displayed. When a user decides to type in a player's name in the "Search Player" text boxes, and the the user does not know the complete spelling of a NBA player's full name, don't worry as the text boxes have a autocomplete feature. The the different stat options will be located in the "Select Statistics Options" box where users can chose options from comparing weight to the average points per game for a given season of the selected players. The "Pick A Graph To Display" and "Select Statistics Options" boxes both have a dropdown menu designed to make selecting options more convenient for the user. Lastly, if the user does not want the graphs to show, the user can click the label title of the graph and the graph will disappear. This is a key feature of the Chart.js library. Below will be a sample step by step guide on how to use the features of the page.

Step 1: Pick a graph to display

* Go to the "Pick A Graph To Display" box and click on the white box with text "Select graph"
* Once you click the white box, a drop down menu appears with two graph options of "Bar Chart" and "Line Chart"
* Click on one of the graph options to display the desired graph
  
Step 2: Select 5 NBA players to compare stats

* Go to the boxes with the labels "Search Player" followed by a number indicating the number of the player and then click on the white box text box
* Once you click the white box, type in the player you wish to use and a dropdown menu will apear with the player's name along with other players
* Click on the player you want from the dropdown menu
* Repeat steps a to c, for all remaining players

Step 3: Chose a statistics option

* Go to the box with the label "Select Statistics Options" and click on the white box with the text "Select statistics"
* Once you click the white box, a drop down menu appears with six statistics options such as "Weight[Pounds]" or "Season 2023 [Avg Points Scored Per Game]"
* Click on one of the statistics options to display the graph with the player statistics based on the selected stats option

## Teams Page 
On this page you can search for different teams and their information by clicking the map. 

* You can hover over the map and the different team names will come up over the area.
* Once you click them the information for the team will come up:
    * Abbreviation
    * City they are from
    * What conference they are in
    * What division they are in
    * Full name of the team
    * General name of the team
