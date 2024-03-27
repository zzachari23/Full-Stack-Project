# Developer Manual

## How to install application and all dependencies
1. First git clone the repository files to your local computer. This can be done by clicking the "Code" button on the repo page. Once you click the button, you can git clone by using either HTTPS, SSH or GitHub CLI. For Mac users, you can open up the terminal and type in 'git clone [Insrt SSH Link]' and it will download the repo files as one folder to your desired local computer directory.
2. Install Node Version Manager (nvm) to your local computer so that we can use nvm to install Node.js. Link to step-by-step guide on installing nvm: https://www.freecodecamp.org/news/node-version-manager-nvm-install-guide/
3. Open up terminal for Mac users and type 'npm -v' to check to see what version of npm you installed. npm stands for Node Package Manager which automatically comes with Node.js when you install node via nvm
4. Install Express by opening up terminal for MAC users and type 'npm install express'
5. Install nodemon by opening up terminal for MAC users and type 'npm install nodemon'
6. Make sure the Supabase package is installed in your local project directory to ensure that the code for using the Supabase database works. This can be done by opening up terminal for MAC users and typing 'npm install @supabase/supabase-js'
## How to run application on server and open up the application on the server port
1. To start running the application on a local server, for MAC users open up terminal and type in 'npm start'
2. Then go to your default web browser and type in http://localhost:4000 in the search bar to see the application 
3. To stop the application running on a server press CTRL + C in terminal for MAC users
## How to run any tests you have written for your software 
Most of the tests written are if the api is not responsive in getting data for the different pages, it will give you the error code. 

## The API for your server application - all GET, POST, PATCH, etc endpoints, and what they each do 
Get All Players: This endpoint retrieves all players from all seasons. You can use the following command to retrieve all players: "https://www.balldontlie.io/api/v1/players". You can also use the search parameter to filter players based on their name.

Get a Specific Player: This endpoint retrieves a specific player. You can use the following command to retrieve a specific player: "https://www.balldontlie.io/api/v1/players/<ID>". Replace <ID> with the ID of the player you want to retrieve.

Get All Teams: This endpoint retrieves all teams for the current season. You can use the following command to retrieve all teams: "https://www.balldontlie.io/api/v1/teams".

Get All Games: This endpoint retrieves all games. Seasons are represented by the year they began. For example, 2018 represents season 2018-2019. You can use the following command to retrieve all games: "https://www.balldontlie.io/api/v1/games".

Get a Specific Game: This endpoint retrieves a specific game. You can use the following command to retrieve a specific game: "https://www.balldontlie.io/api/v1/games/<ID>". Replace <ID> with the ID of the game you want to retrieve.

Get Stats for a Specific Player: This endpoint retrieves the stats for a specific player. You can use the following command to retrieve the stats for a specific player: "https://www.balldontlie.io/api/v1/stats?seasons[]=2018&player_ids[]=<ID>". Replace <ID> with the ID of the player you want to retrieve stats for.

Get Stats for a Specific Team: This endpoint retrieves the stats for a specific team. You can use the following command to retrieve the stats for a specific team: "https://www.balldontlie.io/api/v1/stats?seasons[]=2018&team_ids[]=<ID>". Replace <ID> with the ID of the team you want to retrieve stats for.


## A clear set of expectations around known bugs and a road-map for future development 
For each page, there is always room for improvement. For the team's page with the map, we would like to make the image adjustable so it would be usable on a phone or tablet screen, not just set for a computer screen. Also, make it more versatile and adjustable in general. 

We can adjust the CSS for the home page so that the div boxes are separate and uniform with the font other than the default fonts. When you search for a player, ensure that the box only extends the player box, not the team box. Also, make the result more aesthetically pleasing to the user so they aren't scrolling through a ton of information. Maybe put it in a more readable table. 

We can improve the players' page by displaying more than one graph at a time for the different statistic options so the user doesn't need to constantly flip back and forth if they want to compare something.

Regarding bugs, there is a slight issue with the players page not fetching and displaying the information of all 5 players on the graph from time to time. For example, sometimes only 4 out of the 5 players information will be displayed on the graph. We aim to fix this bug in a future update. 
