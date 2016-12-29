# Remis
project in second semester of masters
The project is based on MVC.net and .net framework for DB operations
The goal of the project is to send reminders to the staff of Politechnika about their task..
The project used webserveices to send emails.

## Installation Requirments
1. Microsoft SqlServer 2012
2. Visual studio 2013 with Entity framework 4.5 

### How to run 
import the database files from Database directory
change the connection string in class OwinContext.cs  Database.Connection.ConnectionString = @"Data Source=HASSAN;Initial Catalog=Remis;Integrated Security=True";
to and run the solution.
