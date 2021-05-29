# U Develop It

## Description

The back-end of a voting application called U Vote It, connected to a relational database using MySQL.

## How to Install
** This app uses MySQL and you will need to have MySQL installed to operate this application.**

* Clone the repository onto your local machine ([How to Clone a repository](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository-from-github/cloning-a-repository)).
* In your terminal `cd` into the root folder of the u-develop-it.
* While in the root folder, you must first run `npm install` to load all the dependancies needed for the app run.
* Next you should open the connection.js file and edit it to contain your MySQL username and password.
* In your terminal while still in the root folder of u-develop-it run `mysql -u root -p` then enter your MySQL password when prompted.
* Now in the MySQL shell run `source db/db.sql` to create the election database.
* Next run `source db/schema.sql` to create the parties, voters, votes, and candidates tables.
* Run `source db/seeds.sql` to populate the four tables with data.
* Type `quit;` to exit the MySQL shell.

## How to Use
* After following the installation instructions you are able to use the application. Run `npm start` to do so. 
* Since the application is only the backend use an API client like [Insomnia](https://insomnia.rest/) or [Postman](https://www.postman.com/) to see the routes at work.
* Study the code and API routes to see which routes and methods are available. You can you your API client to test them out.

![500-get-voters-sorted](https://user-images.githubusercontent.com/77217156/118424398-2a3daf00-b695-11eb-8964-3224974e7a34.jpeg)

* In this application you can perform the following :
  * Get all candidates
  * Get candidates by ID
  * Add/delete/update candidates.
  * Get all parties
  * Get parties by Id
  * Delete parties
  * Add votes
  * Get all votes
  * Get all voters
  * Get voters by ID
  * Add/delete/update voters.
 
* To exit the application use CTL + C

## Built With
* Express.js
* Node.js
* MySQL

## Contributors
Michelle Asuamah

## Contact
If you would like to contact me you can reach me at michey.asmah21@gmail.com.
