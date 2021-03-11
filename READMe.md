**EAT DA BURGER** - Node Express Handlebars

**Deployed Application:** 
- Heroku link https://leslieburgerapp.herokuapp.com/ 
- Github Repository https://github.com/leskbook/burger
- Updated Portfolio https://leskbook.github.io/homework2Portfolio/portfolio.html

**Project Objectives**

Eat-Da-Burger! is a restaurant app that lets users input the names of burgers they'd like to eat. Whenever a user submits a burger's name, the app will display the burger on the left side of the page waiting to be devoured. Each burger in the waiting area also has a Devour it! button. When the user clicks it, the burger will move to the right side of the page.

<image src = "/public/assets/images/proscreenshot.png">

**Technologies Used**
- node.js
- mysql
- express
- express handlebars

**Structure**

.
├── config
│   ├── connection.js
│   └── orm.js
│ 
├── controllers
│   └── burgers_controller.js
│
├── db
│   ├── schema.sql
│   └── seeds.sql
│
├── models
│   └── burger.js
│ 
├── node_modules
│ 
├── package.json
│
├── public
│   └── assets
│       ├── css
│       │   └── burger_style.css
│       └── img
│           └── burger.png
│   
│
├── server.js
│
└── views
    ├── index.handlebars
    └── layouts
        └── main.handlebars