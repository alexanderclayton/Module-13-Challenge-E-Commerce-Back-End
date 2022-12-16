# Alex Clayton's e-Commerce Back End

## Introduction
This project was developed by Alex Clayton as part of the KU Coding Bootcamp 13-ORM Challenge.  This is an e-Commerce website backend that utilizes SQL to work with the database we're creating, the Express.js api package, the Sequelize package to link the database to our application, and the dotenv package to keep our unique user information a SECRET!

## What's in the project?
The acceptance criteria for this project are as follows:

1.  WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
    THEN I am able to connect to a database using Sequelize

    We utilized the .env file for this as well as the sequelize and dotenv packages to get our database up and running in a safe and secure manner.

2.  WHEN I enter schema and seed commands
    THEN a development database is created and is seeded with test data

    The schema.sql file simply removes an old database and creates a new one.  The seed command was included in the starter code and runs the index.js file in the seeds folder, populating our database with the information we included in the various models.

3.  WHEN I enter the command to invoke the application
    THEN my server is started and the Sequelize models are synced to the MySQL database

    Running nmp start starts the server.  Most of this code was already included in the starter code but we did have to sync up sequelize.

4.  WHEN I open API GET routes in Insomnia for categories, products, or tags
    THEN the data for each of these routes is displayed in a formatted JSON

    We created these routes in the api folder under each routes js file.

5.  WHEN I test API POST, PUT, and DELETE routes in Insomnia
    THEN I am able to successfully create, update, and delete data in my database

    These functions were also created in the api folder for each of the different routes.


## The completed project resembles the following image when deployed:

There was no desktop view for this application, so instead we used insomnia to demonstrate the applications functionality:

![Insomnia view](/assets/insomnia-view-challenge-13.PNG)

![link to walkthrough video](https://drive.google.com/file/d/1x7TPndx-HyUIYTGdyIwV_htXcg5n0tzw/view)
