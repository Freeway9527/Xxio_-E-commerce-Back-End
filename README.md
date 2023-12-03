# Module 13 Challenge Object-Relational Mapping (ORM): E-Commerce Back End

<p align="center">
  <img src="https://img.shields.io/badge/License-MIT-blue" alt="License: MIT">
</p>

## Description
The objective was to establish an Express.js API and configure Sequelize to effectively communicate with a MySQL database.

![Alt text](<Assets/images/MVC-Get Category.png>)
![Alt text](<Assets/images/MVC-Get Product.png>)
![Alt text](<Assets/images/MVC-Get Tag.png>)

 Click on the link to watch a video demonstration:
[(ORM): E-Commerce Back End Video Demo](https://drive.google.com/file/d/1Y7S_TaEZq8gIxApf62iHraNshHgt40Nq/view)


## Table of Contents
1. [Installation](#installation)
2. [Technologies](#technologies)
3. [Usage](#usage)
4. [Tests](#tests)
5. [Credit](#credit)
6. [Contribution](#contribution)
7. [License](#license)
8. [Contact](#contact)

## Installation
Make sure that you have Node.js install, if you do not have node.js, you can visit [Node.js website](https://nodejs.org/en).

You will also need to add dependencies, in your terminal type in:

```
npm init
```
```
npm i express
```
```
npm install mysql2
```
```
npm install sequelize
```
```
npm install dotenv
```


## Technologies

<p align="center">
  <img src="https://img.shields.io/badge/-JavaScript-blue?logo=JavaScript&logoColor=white" alt="JavaScript">
  <img src="https://img.shields.io/badge/-MySQL-red?logo=MySQL&logoColor=white" alt="MySQL">
  <img src="https://img.shields.io/badge/-Node.js-purple?logo=Node.js&logoColor=white" alt="Node.js">
  <img src="https://img.shields.io/badge/-npm-CB3837?logo=npm&logoColor=white" alt="npm">
  <img src="https://img.shields.io/badge/-Git-orange?logo=Git&logoColor=white" alt="Git">
  <img src="https://img.shields.io/badge/-Insomnia-purple?logo=Git&logoColor=white" alt="Git">
</p>

## Usage

Make sure you rename the `.env.EXAMPLE` file to `.env` Copy and paste the following lines of codes. 

```
DB_NAME=''
DB_USER=''
DB_PASSWORD=''
```
Than enter your information according to the data base and your information.


To run the program, in your teminal type in:
```
mysql -u root -p
```
Enter your password when you are prompt, if you do not have a password just hit enter.
```
source db/schema.sql
```
```
Exit
```

```
npm run seed
```
```
npm start
```


## Tests

All testing was done through Insomnia using HTTP methods OF GET, POST, PUT, AND DELETE


## Credit

Starter code provided by the U of M fullstack boot camp.

## Contribution

Created for Module 13 Challege of the U of M full stack boot camp. Contact me with ideas and request for changes.

## License

This project is licensed under the MIT License.

## Contact

 * Email: xiongxeng@gmail.com
 * Github: http://github.com/freeway9527

