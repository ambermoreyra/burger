#  Burger MVC

This CRUD application allows the user to chose from the available burgers to "eat." After the "eating time!" button is clicked, the burger moves to the "Out of stock" section. The user may also add a burger by entering a burger name in the input field and click the "add burger" button.

## Custom ORM

A custom ORM is used in order to interact with the database. Functions are created in order to create/add, read, update, and delete from the database. It is through the `burgerControllers.js` file that these functions are used to add burgers to the databse, get all of the burger info to display, update the database when the burger has been eaten, and remove a burger.

## Handlebars

Content through routes. When the burger data is received from the database, handlebars then renders the `index.handlebars` to dynamically display the data.

## Technologies Used

* JavaScript
* JQuery
* Node.js
* Express
* MySQL Database
* Handlebars
* HTML5
* Bootstrap 4

### Created by Amber Moreyra

[Demo App on Heroku](https://whispering-savannah-53079.herokuapp.com/)