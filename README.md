# Ecom back-end Challenge
 
  ## Description
  This is a back end setup for an ecommerce company. The database is setup along with tables. The seed files are setup and ready for deployment. The API routes are setup and ready for use. I used command line to source the database. I used npm to seed the database and npm to start the server. Then I used insomnia to test the routes.

  ## Table of Contents
  [Installation](#Installation)  
  [Usage](#Usage)  
  [Contributing](#Contributing)   
  [Testing](#Testing)  
  [Questions](#Questions)  
  [License](#License) 
  
  ## Installation
  1. See Contributing for forking the repo
  2. Once these files are local on your machine
  3. Run 'npm install mysql2 sequelize dotenv' in the terminal to install npm to create the necessary dependencies
  
  ## Usage

  1. Open command line and type 'mysql -u root -p' to login to MYSQL
  2. Enter password (found in the .env file)
  3. type 'source db/schema.sql'
  4. Open bash terminal and type 'npm run seed' to seed the database
  5. type 'npm start' to connect to the server
  5. Open Insomnia to test routes
  6. Setup GET, POST, PUT and DELETE routes for the following connections:
        *   http://localhost:3001/api/categories
        *   http://localhost:3001/api/products
        *   http://localhost:3001/api/tags
  7. Test the routes
  8. When satisified with testing, disconnect from server using control + C in the bash terminal
  9. Disconnect from MYSQL by typing 'quit' in the command line that you have open for MYSQL

  [Click here to see a walk-thru video](https://watch.screencastify.com/v/711mA9TFJq8YJwkhME1t)

  ## Contributing  
  
  ### Add to Project  
  To work on or add to this project follow these steps  
  1. Fork the repository  
  2. Add you changes  
  3. Submit a pull request for approval  
  
  ### Issues
  To add issues in GitHub follow these steps
  1. Click on the issues tab
  2. Click 'New issue' button
  3. Give the issue a title and comments
  4. Click 'Submit new issue' button

  [Click here to view current GitHub Issues](https://github.com/kimberlyamaya/ecom-challenge/issues)   

  ## Testing

  ### Test Using Insomnia
  1. Open Insomnia and set up GET, POST, PUT and DELETE routes to the following connections
        *   http://localhost:3001/api/categories
        *   http://localhost:3001/api/products
        *   http://localhost:3001/api/tags
  2. Use JSON in the POST and PUT routes, here is an example for each one:
        *   POST route for categories  
            ![POST-route-for-categories](./assets/images/POST-route-category.png)
        *   PUT route for categories  
            ![PUT-route-for-categories](./assets/images/PUT-route-category.png)  
        
        *   POST route for products  
            ![POST-route-for-products](./assets/images/POST-route-product.png)
        *   PUT route for products  
            ![PUT-route-for-categories](./assets/images/PUT-route-product.png)  

        *   POST route for tags  
            ![POST-route-for-tags](./assets/images/POST-route-tag.png)
        *   PUT route for tags  
            ![PUT-route-for-tags](./assets/images/PUT-route-tag.png)  
  3. Test each route by running and view results

  ## Questions

  ### Contact
  For any questions please contact Kimberly Amaya 
  
  Email: [Link to Email](mailto:kimberly_kimbell@yahoo.com)  
  GitHub: [Link to GitHub Account](https://github.com/kimberlyamaya)  
  
  ## License
  This project contains a license from MIT 
  [Click here to see the license](license.md)
  [![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)](https://mit-license.org/) 