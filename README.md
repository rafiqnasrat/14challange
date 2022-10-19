
# My Tech Blog
![screnshot](https://github.com/rafiqnasrat/14challange/blob/main/14challange.png)

## Description
Hello, This is a CMS blog site developed with node js, express js and MVC Paradigm, In the blog site you can post posts and can update your post, delete your post and other visitors can leave comments, and everyone can signup, create account and post a blog using the dashboard.

## Installition
Run the following command, To install the necessary dependencies:

npm i


## MySQL Database Setup

To set up the database, run the following command:

mysql -u root -p

Then, source the schema.sql file:

source db/schema.sql

Finally, seed the database:

source db/seeds.sql

## Create a .env file

Create a .env file in the root directory of the project and add the following:

DB_NAME='tech_blog'
DB_USER='root'
DB_PW='your password'
