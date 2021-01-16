# store-it

  ## Description

 A back-end application to create, update, and maintain a database of products, categories, and tags for an e-commerce site.
  
To view a walkthrough, [Click Here](https://drive.google.com/file/d/1UDQmfLQG4CP5Pzqe7s9Gp6ENQgPQMbJJ/view)
  
  ## Table of Contents
  
  * [Installation](#installation)
  * [Usage](#usage)
  * [Contributing](#contributing)
  * [Testing](#testing)
  * [License](#license)
  * [Questions](#questions)
  
  ## Installation

  You will need Node.js to run this program.  After cloning the code to your local device, be sure to run "node npm install" to include essential npm packages.
  
  ## Usage 
  
You will first need to set up your e-commerce.db database.  This program comes with the schema.sql and seeds.sql file to do so.  Feel free to update the seeds file to fit your store's needs.

Open the SQL CLI by running "mysql -u root -p" and entering your password
Then run these two commands to create and fill the database:
"source db/schema.sql"
then
"source db/seeds.sql"
(you can also run "npm run seeds" form the command line to seed your database once created)

Once your database is created and seeded, exit the SQL CLI by typing "quit".

Run "node server" or "npm start" to start the program.  You will need to run the api routes via Insomnia in order to update the database.
  
  ## Contributing

 Please reach out via email if you wish to contribute (see questions section below)
  
  ## Testing

  No testing currently.
  
  ## License

  [![License: WTFPL](https://img.shields.io/badge/License-WTFPL-brightgreen.svg)](http://www.wtfpl.net/about/)
  
  ## Questions
  
  * GitHub: [@fancibleunicorn](https://github.com/fancibleunicorn)
  * Email: adamcrandall91@gmail.com
