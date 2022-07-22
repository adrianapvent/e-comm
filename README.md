![MIT](https://img.shields.io/badge/License-MIT-blue)
# Employee Tracker

## Description

Welcome to the E-Comm project!

Object-Relational Mapping (ORM) Challenge: A interactive E-Commerce back end utlizing Object-Relational Mapping as power be Sequelize

## Table of Contents

- [E-Comm](#)
  - [Description](#description)
  - [Table of Contents](#table-of-contents)
  - [User Story](#user-story)
  - [Acceptance Criteria](#acceptance-criteria)
  - [Mock-up](#mock-up)
  - [Technologies](#technologies)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Contributing](#contributing)
  - [Tests](#tests)
  - [Questions](#questions)
  - [License](#license)
  - [BONUS](#bonus)

## User Story

~~~
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
~~~

## Acceptance Criteria

~~~
GIVEN a functional Express.js API
~~~

- [x] WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
~~~
THEN I am able to connect to a database using Sequelize
~~~

- [x] WHEN I enter schema and seed commands
~~~
THEN a development database is created and is seeded with test data
~~~

- [x] WHEN I enter the command to invoke the application
~~~
THEN my server is started and the Sequelize models are synced to the MySQL database
~~~

- [x] WHEN I open API GET routes in Insomnia for categories, products, or tags
~~~
THEN the data for each of these routes is displayed in a formatted JSON
~~~

- [x] WHEN I test API POST, PUT, and DELETE routes in Insomnia
~~~
THEN I am prompted to enter the name of the department and that department is added to the database
~~~

- [x] WHEN I choose to add a role
~~~
THEN I am able to successfully create, update, and delete data in my database
~~~

## Mock-up

The first animation shows GET routes to return all categories, all products, and all tags being tested in Insomnia:
![mockup](./public/assets/images/get-routes.gif)

The second animation shows GET routes to return a single category, a single product, and a single tag being tested in Insomnia:
![mockup](./public/assets/images/get-id-routes.gif)

The final animation shows the POST, PUT, and DELETE routes for categories being tested in Insomnia:
![mockup](./public/assets/images/post-put-delete-routes.gif)

Your walkthrough video should also show the POST, PUT, and DELETE routes for products and tags being tested in Insomnia.

## Technologies
| ID # | Technologies |
| --- | --- |
| 1 | Markdown |
| 2 | JavaScript |
| 3 | Node.js |
| 4 | express package |
| 6 | mysql2 package |
| 7 | sequelize package |
| 8 | dotenv package |
| 9 | nodemon package |

## Installation

VSCode

Please ensure you have the required NPM modules and MySQL installed installed locally clone this repo and install npm modules using following commands. Ensure your SQL Database is running

via commandline: mysql -u root -p when prompted enter your password then exit by typing quit

to run the application we need to first seed the database use the following command via gitbash Commandline: npm run seed this will build the databases we will be manipulating.

once database is built start your server using the following command npm start

once the server is live then you can Cycle through CRUD options via Insomnia Core / postman.

## Usage

Usage

## Contributing

Contribute

## Tests

Test

## Questions

If you have any questions, you may direct them to AdrianaPVent using the following links:

| | Description |
| --- | --- |
| Name | Adriana |
| Occupation | Developer |
| E-mail | <adriana.e.pena@gmail.com> |
| GitHub | <https://github.com/adrianapvent> |

## License

MIT License

Copyright (c) 2022 AdrianaPVent

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
