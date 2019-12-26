# News-Scrape

News Scrape is an app that scrapes current articles from for users to save and review. Users can post comments about articles they have saved for others to see.

## Tech Used
The main tech I used in creating this project.

* MongoDB - Database
* NodeJS - Server-Side Code
* EJS - HTML Templating
* Express - Server Routing and Managment
* Mongoose - MongoDB ORM
* Cheerio - Site Scraping
* Passport - User Auth and Login

## Dashboard
After a user signs up and logs in they will be directed to the dashboard page. As people use the app they can select which news source they want to populate the list of articles with in the main window. From there each user can save and remove articles for themselves to view later or simple click on an article link to view it. They can also navigate to the Saved Article Page to manage their saved articles further.

## Saved Articles
Saved Article lets users post comments and notes about what they have read to share with other users on the site or to keep for themselves. Only the creator of that note can actually edit or delete it.

## Start your own project
Feel free to clone this repo and build your own version of News Line!

## After you have cloned the repo simple run:

`npm install`

`npm start`

You will need to have a mongoDB server running to use the database. After you have installed mongo run this command in another terminal to run the mongoDB server.

`mongod`

