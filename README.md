The project was completed using JDK 12 in Eclipse. I used Maven to help build dependencies and the OpenCSV and SQLite repositories.
The code should run after compiling the main Maven file (pom.xml). The class file can be found in ParseIntoDB.java and the main class
is within Main.java.

My approach started with doing preliminary research for what I needed to accomplish for the project, namely how to read and write CSVs in 
Java and how to maintain a SQLite database. I quickly found that OpenCSV would be an efficient solution for parsing through and writing 
CSVs as well as many other resources about in-memory SQLite databases. From there, I finally began setting up the ParseIntoDB class and 
the main class. I divided up the main project into all of its subproblems (creating a database, parsing a CSV, inserting data into the 
database, getting the current timestamp, writing to a new CSV file, and writing to a new text file). The project was completed by 
implementing and testing each of these subproblems before testing the entire project as a whole.
