# E-commerce-ORM

## Description
    
This project is specifically targetting the back end of an e-commerce website. While working on this, I really gathered a targetted understanding of models and routes working together. With this application a user will be able to source and seed a database, along with starting up the server. They will also be able to make CRUD requests to the database for the category, product, and tag/product tag. The organization of this application will make the user experience very simple.
## Table of Contents
[Title](#-e-commerce-orm)

[Description](##-description)

[Visuals](##-visuals)
  
[Installation Instructions](##-installation)

[Usage Information](##-usage)

[License](##-license)

[Contribution](##-contribution)

[Test Instructions](##-tests)

[Questions](##-questions)

## Visuals

Here is a demo video walking a user through the application.

<iframe src="https://drive.google.com/file/d/13-DOinJPvS8l3yOmcQkl0Zs7xVvAyqCl/preview" width="640" height="480"></iframe>
    
## Installation
    
To use this application, you will need to have Node.js installed on your desktop. Once in your code editor of choice, you will need to open your terminal and initialize npm with the command: npm init. Once you have npm initialized, you will install npm with the command: npm install. You will need to ensure that you have mysql2, sequelize, express, and dotenv installed. You may also install nodemon into the dev dependencies for making adjustments to your server with ease. That is all that you will need to start this project.
            
## Usage
    
To use the back end of this application, a user will need to initalize and install npm. Make sure that your personal mysql username and password are in the .env file. After doing so you will be able to run the command "mysql -u root -p" and you will then be prompted to enter your password. Once you have entered the mysql terminal, you will then source your schema file with the command "source ./db/schema.sql", and you should then have the number of queries in that table displayed. You may then type "quit" to exit the mysql terminal. Once you do so you will then seed your database with the command "npm run seeds," and you should get confirmation that your database has been successfully seeded. Lastly, you will need to run the command "npm start" to get your server running. From here you will be able to go to Insomnia to test CRUD requests, or you can access the site in the browser and attempt to make requests there.
    
## License 

This application is covered under the MIT License. For further explanation of what this license does please visit this provided link:  https://opensource.org/licenses/MIT
    
## Contribution
    
I am the sole contributor for this project aside from starter code I received from the Vanderbilt Full Stack Flex Bootcamp.
  
## Tests
  
You can run the command "npm run watch" to use nodemon so you can keep the server running while you continue making changes without having to restart the server. Other than that there are no other tests for you to run. 
  
## Questions

Here is a link to my Github: [Olivia Gilbert](https://github.com/umhello2020)
If you have any additional questions, you may reach me at my personal email umhello2020@gmail.com.
  