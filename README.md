# Tech-Blog Application

![MIT License](https://img.shields.io/badge/license-MIT-green)

# Table of Contents

* [Description](#description)
* [Demo](#demo)
* [Technology](#technology)
* [Usage](#usage)
* [License](#license)

# Description :

This application is build a CMS-style blog site similar to a Wordpress site, where developers can publish their blog posts and comment on other developers’ posts as well. 

# User Story  

```
AS A developer who writes about tech
I WANT a CMS-style blog site
SO THAT I can publish articles, blog posts, and my thoughts and opinions
```

# Demo  
https://www.screencast.com/t/iZv94pWahN

# Link
https://fullstack-mvc-tech-blog.herokuapp.com/

# Technology 

[MySQL](https://www.npmjs.com/package/mysql) 

[Node.js](https://nodejs.org/en/)

[Handlerbats](https://www.npmjs.com/package/handlebars)

[dotenv](https://www.npmjs.com/package/dotenv)

[express](https://www.npmjs.com/package/express)

[Model-View-Controller]


# Usage 

# Initial setup

Create a '.env' file in the main directory path and include the following data:

```
DB_NAME='your_database_name'
DB_USER='your_mysql_username'
DB_PW='your_mysql_password'
```

Once your '.env' has been created with the corresponding data, open up the schema ('db/schema.sql') and update the database label to match with the database you included in your '.env' file.

# Schema setup

If you'd like to build the schema, you can enter the MySQL shell by typing in terminal:

```
mysql -u root -p
```

After entering your password followed the following command:

```
source db/schema.sql
```

To start the server, type in terminal:

```
npm start
```

# License

This project is licensed under MIT license.
