# Django
Django is a high-level web framework for Python. It is designed for rapid development and follows the model-template-view architectural pattern. Django provides a full-featured and scalable framework for building web applications, with a focus on minimizing the amount of code needed to be written and maximizing the reuse of existing code.

#   key features of Django 
-An ORM (Object-Relational Mapping) that allows you to interact with  databases using Python code instead of SQL.
-A powerful URL routing system that makes it easy to build clean and maintainable URLs.
-A built-in administrative interface for managing your application's data.
-A robust and secure authentication and authorization system.
-Built-in support for user-uploaded files.
-Django has been used to build many high-traffic websites, including Instagram, Pintrest, Mozilla, and NASA. It's known for its batteries-included approach, meaning that it comes with a lot of pre-built functionality, which makes it a popular choice for building web applications quickly and efficiently

# This series of steps explains how to create and manage a database in Django using the PostgreSQL database management system.

-Connect to PostgreSQL: The first step is to connect to PostgreSQL using the psql command in the terminal.

Create a database: The next step is to create a database by running the CREATE DATABASE command. In this case, the database is called "showcollector".

Connect to the newly created database: After creating the database, the user connects to it by running the \c showcollector command.

List tables in the database: The user then lists all the tables in the database by running the \dt command. The output shows a list of tables present in the public schema, such as auth_group, auth_user, and main_app_show.

Query data in a table: The user then runs a SELECT statement to query data from a table in the database, in this case the table "main_app_show". The SELECT statement retrieves data from the table based on the specified columns and conditions.

Drop the database: The user then drops the database by running the DROP DATABASE showcollector command.

Note: The specific steps in this example might vary depending on the version of PostgreSQL and the specific configurations used.

