# E-Commerce Back End

The back end for an e-commerce business site that would facilitate the buying and selling of products online.

## User Story

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Acceptance Criteria

```md
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database
```
## Installation and Use

This application is not deployed, so its functionality is not easily accessible without some coding know-how and an API development platform:  
1. Download or clone the repository from GitHub with the link below.
2. In the terminal, install the necessary packages. Such as:
```bash
  npm install
```
3. Launch MySQL:
```bash
  mysql -u root -p
```
4. When prompted, enter your password.
5. Create the database:
```bash
  source db/schema.sql
```
6. Exit MySQL:
```bash
  quit;
```
7. Seed the data:
```bash
  npm run seed
```
8. Then, start the server up:
```bash
  npm start
```
9. Open your API development platform of choice, such as Insomnia, Postman, etc. and test the functionality of the routes.

## Links

* GitHub: https://github.com/IvanDirigible/e-commerce

The following link demonstrates the E-Commerce Back End routes being tested with Insomnia:

* Screencastify: https://app.screencastify.com/v3/watch/22KXGGGDpqRkrZ26BJQ3

## License
This project is licensed under the MIT license.  
License Link  
https://opensource.org/licenses/MIT   
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)]