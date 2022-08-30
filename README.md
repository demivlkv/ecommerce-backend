# Project 13: Object-Relational Mapping (ORM) Challenge
## E-commerce Back End

Object-relational mapping (ORM), is a technique that allows developers to convert data between incompatible type systems using object-oriented programming principles. The goal for this project was to build the back end for an e-commerce website. By taking a working Express.js API to configure with Sequelize enables this application to interact with a MySQL database.

![screenshot.png](/../main/assets/images/screenshot.png)

### Built With:
- [Node.js](https://nodejs.org/en/)
- [Express.js](https://expressjs.com/)
- [Node MySQL2](https://github.com/sidorares/node-mysql2#readme)
- [Sequelize](https://sequelize.org/)
- [dotenv](https://github.com/motdotla/dotenv#readme)

## Installation
1. To install this application, `git clone` this repository, or download the `.zip` file in the dropdown after clicking the green ‘Code’ button at the top of this repository—as long as it is in your local branch.
2. Ensure Node.js is installed in the code editor of your choice.
3. Install all of the dependencies by entering the following command in terminal:
```
npm install sequelize mysql2 dotenv
```

## Usage
1. Make sure that you are in the root directory in order for this application to run successfully. Then start up MySQL by entering the following:
```
mysql -u root -p
```
2. Enter your MySQL password, and then run `SOURCE db/schema.sql;` to create the database. Then exit MySQL by entering `quit;` into the command line.
3. Initialize the application by running this command in terminal:
```
node server.js
```
4. Upon a successful connection, run `npm run seed` to seed data to your database.
5. Open an API Client of your choice to create, read, update, & delete data in the database! (i.e. [Insomnia](https://insomnia.rest/), [Postman](https://www.postman.com/))

### Video Walkthrough
[https://youtu.be/0hGVxvQcD_c](https://youtu.be/0hGVxvQcD_c).

![demo.gif](/../main/assets/images/demo.gif)

## Questions
For any questions about this repository, please contact me at [demi.h@me.com](mailto:demi.h@me.com).

To view more of my works, please visit my GitHub: [demivlkv](https://github.com/demivlkv).