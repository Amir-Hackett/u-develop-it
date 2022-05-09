# U-Develop-it

[![Issues](https://img.shields.io/github/issues/amir-hackett/u-develop-it)](https://github.com/amir-hackett/u-develop-it/issues) [![Issues](https://img.shields.io/github/contributors/amir-hackett/u-develop-it)](https://github.com/amir-hackett/u-develop-it/graphs/contributors) 

## Description
A Node.js application using Express and MySql to manage candidates, parties, and votes for the company "U Develop It".

## Contents
* [Installation](#Installation)
* [Questions](#Questions)
* [Credits](#Credits)
    
## Installation
Clone down the repository and run `npm i` in the command line.  

## Usage
In the command line, run `mysql -u root -p`, `USE election` then `source db/db.sql`. Run the schema from the command line with `source db/schema.sql`.  The tables can also be seeded by running `source db/seeds.sql`.  Queries to the database can then be conducted through the terminal with MySql. Quit the terminal by running `quit`.
