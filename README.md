# E-Commerce ORM


Video Link: 
  - Adding seed data: https://drive.google.com/file/d/1XQDbjaYqrqjC_2BEMIYf4DUJhA_OsWaZ/view?usp=sharing
  - Insomnia testing Products: https://drive.google.com/file/d/1tIwG0k4NcQyU5m8SbaZ4sq-In8X8Lkt8/view?usp=sharing
  - Insomnia testing Categories: https://drive.google.com/file/d/1i0NUfrNyI2nvhoiSen6q9UPGeCWFeBxO/view?usp=sharing
  - Insomnia testing Tags: https://drive.google.com/file/d/1RurdcS-Kyp15B_hlxjlmMnSPQmlqxXKK/view?usp=sharing

## Table of Contents
- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)
- [Contributing](#contributing)

## Description

This application is the backend for an e-commerce website. It provides a database for clothing products that could be used to track inventory, price, available options and styles.

## Installation

  - First clone this repository to your local device and use VS code or another code editor for the next steps. 
  - Once you have opened the cloned folder in your code editer, make sure that you have node.js and My SQL installed on your computer. 
  - You may also want to install insomnia or postman to test your server connections to the database. 
  - You will also need to create a ".env" file in VS Code or your choice of code editor that includes the link to your My SQL. Copy the following and paste in the .env file and enter your user and password information that you created when you installed My SQL: "DB_NAME=employee_trackerDB DB_USER= ???? DB_PASS= ?????"
  - You will then need to load the database into My SQL to initiate the connection. 
  - In VS Code or your choice of code editor, run "npm i" in the terminal to load the correct packages included from the cloned repository.

## Usage

  - Provided that you followed the steps in the installation process you will then open terminal in your code editor and enter "node seeds". This will load the seed products, categories, and tags into the database for testing purposes. You can then run "Node Server" the test the connection. It should tell you what port the app is listening to on your local device. You can then use insomnia or postman to test the database. 

## Credits

- Technologies used:
    - Sequelize
    - Routes
    - Express
    - Insomnia
    - Node.js
    - My SQL
    - My SQL Workbench
    - NPM
    - JavaScript
    - .env
    - Console Table NPM

## License

MIT License

Copyright (c) [2021] [Chris Beard]

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

## Contributing

- Please message me on GitHub with any contributions you think might improve this application. 
