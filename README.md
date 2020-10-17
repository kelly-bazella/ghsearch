# ghsearch

## How to Use
To use the GitHub finder, the user must fork this repository on their local machine. Then, they will need to register on the GitHub API an OAuth account in order to get the ID and Secret. Input both in the github.js file in the GitHub class constructor. The user will then open the HTML file in their browser and the application should work from there. 

Go to https://www.github.com, log in, go to Settings > Developerr Settings > OAuth Apps and register a new app. Once created copy and past the client ID and client Secret into the github.js file.  

## Features
This application includes the following features:
- When  there is nothing in the search field, no profile is shown.
- If a user is not found an alert will appear for 3 seconds letting the user know that username does not exist. 
- All information pulled from the GitHub API, including the most recent 5 repos the user created. 

## GIF
![](demo.gif)