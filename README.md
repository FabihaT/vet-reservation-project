ENSF 380 - Vet Reservation System

Client Problem Definition.  
The project’s goal was to develop a software application for Example Wildlife Rescue (EWR), which specializes in animals like coyotes, foxes, porcupines, beavers, and raccoons. The application generates a daily task list for volunteers to efficiently care for the animals in various areas and treatments, addressing EWR's need to automate their current manual and error-prone scheduling process.

Learning Outcomes.
- Object-Oriented Design and Documentation
- SQL Database Back-End to generate volunteer schedule and tasks
- GUI Application Front-End for interaction
- JUnit Testing for overall functionality

Run the GUI Application.  
Create the SQL database with the provided treatments.sql file.  
*The Testing file must be commented out to compile*  
To compile: javac -cp .;lib/* edu/ucalgary/oop/*.java  
To run: java -cp .;lib/mysql-connector-java-8.0.23.jar edu.ucalgary.oop.ScheduleAppGUI

Run the Tests:  
To compile: javac -cp .;lib/* edu/ucalgary/oop/*.java  
To run: java -cp .;lib/* org.junit.runner.JUnitCore edu.ucalgary.oop.AllTesting
