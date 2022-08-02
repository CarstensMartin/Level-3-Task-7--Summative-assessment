# Poised - Construction company

## Description:
* This project is part of a student project to demonstrate the newly learned skills with mySQL databases in Java.
* Databases are used to track the projects and store information about different aspects of a building project.

## Table of content methods inside the project:
* main(String[])
* enterNewProject(Statement)
* enterNewArchitect(Statement, String)
* enterNewContractor(Statement, String)
* enterNewCustomer(Statement, String)
* updateData(Statement)
* updateProjectNumber(Statement)
* updateProjectName(Statement)
* updateArchitect(Statement)
* updateContractor(Statement)
* updateCustomer(Statement)
* deleteInformation(Statement)
* deleteProject(Statement)
* deleteArchitect(Statement)
* deleteContractor(Statement)
* deleteCustomer(Statement)
* searchInformation(Statement)
* displayProjectResults(ResultSet)
* displayFullProjectResults(ResultSet)
* displayContactDetailsResults(ResultSet)

## What the project does:
* Capture information about new projects. If a project name is not provided
when the information is captured, name the project using the surname of
the customer. For example, a house being built by Mike Tyson would be
called “House Tyson” and an apartment block owned by Jared Goldman
would be called “Apartment Goldman”.
* Update information about existing projects. Information may need to be
adjusted at different stages throughout the lifecycle of a project. For
example, the deadline might change after a meeting with various
stakeholders.
* Finalise existing projects. When a project is finalised, the following should
happen:
1. The project should be marked as “finalised” in some way and the
completion date should be added.
2. See a list of projects that still need to be completed (have not been
finalised).
3. See a list of projects that are past the due date.
4. Find and select a project by entering either the project number or project
name.

## Why the project is useful:
* It keeps a database of all the current and future project, the information partaining the project and the status of payment and completion.

## Installation
* Download the repository
* Install mySQL with port 3306
* Create a user and in mySQL, in this case "otheruser" and password "swordfish".
* Alternatively, ammend the Main.java file with the correct port, username and password as created.
 

## How to use the project
* Open the repository in the preferend EDI (My case Eclipse) and run.
* The functions are self explanatory once running.

## Author of this project
https://github.com/CarstensMartin