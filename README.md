
# E-Commerce (Back-End)
## Description
This is the back-end programming for a e-commerce application environment. There is no front-end code nor a deployed site as this is only the database and routes logic. See the [Installation](#installation) and [Usage](#usage) sections to see how to install and use this application locally. 

## Table of Contents
* [Usage](#usage)
* [Questions](#questions)

      
* [Installation](#installation)
        
* [Credits](#credits)
        
* [License](#license)
        
* [Features](#features)
        
* [Contributing](#contributing)
        
* [Tests](#tests)
        
    
  

## Installation
This is a `node` based application. To use this application, you must clone it locally to your machine and have node installed to use it. See [Credits](#credits) for more information. <br><br> Follow these steps to install this application locally: <br>1: Clone the repository locally to your machine.<br>2: In the terminal, run `npm i` to install the required dependencies (see Credits for more information on these). <br><br> The application is now installed locally on your machine. See [Usage](#usage) for instructions on how to use this application. <br> Installation Video Here
    
## Usage
This is a `node` application. Node must be installed to use this application. See [Credits](#credits) for more information. Please see the [Installation](#installation) section to install this application before use. <br><br>Here is how to use this application: <br> In the terminal, run `npm start` to start the express server. <br> Visit http://localhost:3001/api/categories to make your first api call (you may also visit this url via Insomnia if installed, see [Credits](#credits) for more information. <br> See [Features](#features) for a full list of api endpoints. <br> To re-seed the database, in the terminal run `npm run seed` to use the provided seed data for the database. Consider this the ultimate 'reset' for the live database. <br><br> See the below videos for demonstration on the different API Route Endpoints seen via Insomnia
<br><br>WALK THROUGH VIDEOS HERE

### Screenshot
![Project Screenshot](./assets/images/screenshot.PNG)


## Credits
THIRD-PARTY ASSETS<br>Starter code provided by https://github.com/coding-boot-camp/fantastic-umbrella <br><br> RESOURCES <br> [Node.js](https://nodejs.org/en/) <br> [dotenv](https://www.npmjs.com/package/dotenv) <br> [Express.js](https://expressjs.com/) <br> [MySQL2](https://www.npmjs.com/package/mysql2) <br> [Sequelize](https://www.npmjs.com/package/sequelize) <br> [Insomnia](https://insomnia.rest/)
    

## License
[![MIT License](https://img.shields.io/badge/License-MIT%20License-informational)](https://choosealicense.com/licenses/mit/)
    

## Features
Here are all the available API Route Endpoints:<br><br>CATEGORIES <br> ![GET All Categories](https://img.shields.io/badge/All%20Categories-GET-blueviolet) http://localhost:3001/api/categories <br> ![GET Single Category](https://img.shields.io/badge/Single%20Category-GET-blueviolet) http://localhost:3001/api/categories/`id number here` <br> ![POST Create A Category](https://img.shields.io/badge/Create%20A%20Category-POST-brightgreen) http://localhost:3001/api/categories <br>`You must use an environment like Insomnia to POST to the database. It is expecting a JSON body object with category_name`.  <br> ![PUT UPDATE A Category](https://img.shields.io/badge/Update%20A%20Category-PUT-orange) http://localhost:3001/api/categories/`id number here` <br>`You must use an environment like Insomnia to PUT to the database. It is expecting a JSON body object with category_name to update`.  <br> ![DELETE A Category](https://img.shields.io/badge/Delete%20A%20Category-DELETE-red) http://localhost:3001/api/categories/`id number here` <br><br>PRODUCTS <br> ![GET All Products](https://img.shields.io/badge/All%20Products-GET-blueviolet) http://localhost:3001/api/procuts <br> ![GET Single Product](https://img.shields.io/badge/Single%20Product-GET-blueviolet) http://localhost:3001/api/products/`id number here` <br> ![POST Create A Product](https://img.shields.io/badge/Create%20A%20Product-POST-brightgreen) http://localhost:3001/api/products <br>`You must use an environment like Insomnia to POST to the database. It is expecting a JSON body object with product_name, price, stock, and category_id`.  <br> ![PUT UPDATE A Product](https://img.shields.io/badge/Update%20A%20Product-PUT-orange) http://localhost:3001/api/products/`id number here` <br>`You must use an environment like Insomnia to PUT to the database. It is expecting a JSON body object with updated parameters. The tagIds should be an array of the numbers referring to the appropriate tags`.  <br> ![DELETE A Product](https://img.shields.io/badge/Delete%20A%20Product-DELETE-red) http://localhost:3001/api/categories/`id number here` <br><br>TAGS <br> ![GET All Tags](https://img.shields.io/badge/All%20Tags-GET-blueviolet) http://localhost:3001/api/tags <br> ![GET Single Tag](https://img.shields.io/badge/Single%20Tag-GET-blueviolet) http://localhost:3001/api/tags/`id number here` <br> ![POST Create A Tag](https://img.shields.io/badge/Create%20A%20Tag-POST-brightgreen) http://localhost:3001/api/tags <br>`You must use an environment like Insomnia to POST to the database. It is expecting a JSON body object with tag_name`.  <br> ![PUT UPDATE A Tag](https://img.shields.io/badge/Update%20A%20Tag-PUT-orange) http://localhost:3001/api/tags/`id number here` <br>`You must use an environment like Insomnia to PUT to the database. It is expecting a JSON body object with tag_name to update`.  <br> ![DELETE A Tag](https://img.shields.io/badge/Delete%20A%20Tag-DELETE-red) http://localhost:3001/api/tags/`id number here` 
    

## Contributing
This application is not open to outside contribution.


## Tests
There are no tests for this application.
    
## Questions
For all questions regarding this project, feel free to contact me at:

GitHub: [SirUbu](https://github.com/SirUbu)

Email: thesirubu@gmail.com
