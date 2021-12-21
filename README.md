# movietheatreapp

Movie Theater Ticket Reservation App
Term project for ENSF 614 - Fall 2021

Objectives
Please refer to the project description document.

Project Structure
dir tree

config - contains the config files containing important settings for the project to work

docs - various documents, including system diagrams, of the project

docs/javadoc.zip - javadoc as zip archive
lib - contains the JARs used by the project

src - contains all the source code as .java files

How to run
Clone the repository to your local machine.

Start the MySQL server on your local machine.

Open the file config/db_details.properties and enter your Db server details. For db.user and db.password, enter your DB user login details. Please use a user that has all the CRUD access, like root.

Connect to your MySQL server using an user used in step 3.

Run this script on the MySQL server. This script will create a schema ENSF614PROJECT, create all necessary tables, and load them with some dummy data.

To compile the source code, run the below command

$ javac -cp ".;lib/*" -sourcepath "src" -d "bin" src/movieTicketSystem/*java src/movieTicketSystem/controller/*java src/movieTicketSystem/model/*java src/movieTicketSystem/view/*java
To run the source code, run the below command

$ java -cp ".;lib/*;bin" movieTicketSystem.movieApp


Contributors
Giese, Calvin
Guo, Yuhua
Gupta, Bhavyai
Hall, Graydon
