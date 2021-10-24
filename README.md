# 13-E-Commerce-Back-End

 ## Description

  Internet retail, otherwise known as e-commerce, is the largest sector of the electronics industry; thus, understanding its fundamental architecture is imperative in the web development industry. The purpose of this project was to build the back end of an e-commerce site, utilizing a working Express.js API in conjunction with Sequelize to interact with a MySQL database.
  
  In order to meet the Acceptance Criteria of the project:

  * Express.js API, Sequelize, and MySQL database/username/password values are used to connect to a database
  * Schema and seed commands creates a development database with test data
  * The server is started and the Sequelize models are synced to the database via a command
  * API GET routes for categories, products, and tags in Insomnia Core displays data in formatted JSON
  * API POST/PUT/DELETE routes in Insomnia Core creates, updates, and removes data in the database

  ## Table of Contents

  * [Installation](#installation)

  * [Usage](#usage)

  * [License](#license)

  * [Contributing](#contributing)

  * [Tests](#tests)

  * [Questions](#questions)

  ## Installation

  To install necessary dependencies, run the following command:

  ```
  npm i
  ```

  ## Usage

  Please use the following link to see a video on how to create the database with MySQL shell commands, how to seed data to the database, and how to start the application:

  [E-Commerce Back End Start Video](https://watch.screencastify.com/v/wEUL2TH35viAZkkYwDbw)

  Please use the following link to see a video on how the GET/POST/PUT/DELETE routes can be opened in Insomnia Core:

  [E-Commerce Back End Example Video](https://watch.screencastify.com/v/gmIh1Bt29I0Swra0mYCc)

  For security purposes, the dotenv package was used to conceal the database credentials of the user. In order to connect to the database, a `.env` file must be created containing populated `DB_USER=`, `DB_PW=` and `DB_NAME=` entries appropriate for the user.

  ## License

  This project is not licensed.

  ## Contributing

  Please contact me using the options provided in the Questions section. Thank you!

  ## Tests

  This project does not contain any tests.

  ## Questions

  If you have any questions about the repo, open an issue or contact me directly at abrahamin.html@gmail.com. You can find more of my work at [https://github.com/abrahamin/](https://github.com/abrahamin/).