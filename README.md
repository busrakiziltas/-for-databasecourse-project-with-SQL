# -for-databasecourse-project-with-SQL
//SENARIO//
CookBook Database-This database can be used for a website where users can add recipes, search recipes of other users, save their favorite recipes, sort recipes by categories and make comments. 
Users table: User ID (primary key), Username, E-mail address, Password, Registration date, Author.A user can have multiple recipes, favorites, and reviews.
Table of recipes: Recipe ID (primary key), Recipe name, Recipe description, Preparation time, Cooking time, Recipe category ID, Recipe image, Creation date, User ID (author) A recipe can have multiple ingredients, and one ingredient can be associated with many recipes.
Ingredients table: Material ID (primary key), Material name A recipe can have multiple ingredients, and one ingredient can be associated with many recipes.
Table of recipe categories: Category ID (primary key), Category name, Parent category ID Categories can have a hierarchical structure.
Comments table: Comment ID (primary key), Comment text, Comment date, Recipe ID, User ID A recipe can have multiple comments, and a user can have multiple comments.
Votes table: Vote ID (primary key), Voting user ID, Recipe ID, Vote value A user can vote for a recipe only once.
Favorite recipes table: Favorite ID (primary key), User ID, Recipe ID A user can add a recipe to their favorites only once.
According to this senario;
 Writing SQL DDL statements for implementing ERD (create table, constraints,
defining keys: pks and fks)
 Making Physical Database using APEX
 Entering data to the Database
 Writing SQL DML Statements to reach information
 One statement including subquery
 One statement including join
 One statement including group by
 One statement including date function
 One statement including character function
 One statement including update
 One statement including alter table
these have been made.
