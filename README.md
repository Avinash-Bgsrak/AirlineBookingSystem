<pre>
************************************************************************************************************************<br>
                             Welcome TO My Airline Ticket Booking System Project<br>
************************************************************************************************************************<br>


Brief about the project:-
A full stack Java project with attractive user interface and of several functionality based on Java Swing.

Following are the functionality consists inside this project:
1.Add Customers :-> Admin can add particular customer for ticket booking.
2.Search Customer:-> Admin can search a customer by entering the customer ID of a particular customer.
3.Book Ticket :-> Here admin can search the flighs and book the tickect for a customer easily. 
4.Booked History :-> Here admin can see the history of previous tickets booked.
5.Print Ticket :-> Here admin can see the status of booked tickets and print it by entering the valid ticket number.
6.Add user :-> Here admin can add the users to give him the access for using AirlineBookingSystem.  
7.Add Flight :-> Here admin can add the flights with flight details.


How to open project in NetBeans ?
First extract the downloaded Zip file.
Step 1: Go to file menu then import project from ZIP and choose the project from extracted folder.
Step 2: Import the AirLineSys_DB_Backup.sql in your System database.
Step 3.Add JAR Files which is in repository.
Note : Be sure add the both jar files before going for step 4. 
Step 4: Go to class file with name DatabaseUserAndPassword.java here default user and password is "root" you need to type your mysql usernamme and password.  
Step 5: Now run the program in Netbean.
Step 6: A user login page will open use below user id and passward as defaut.
   User: avi Password: 1234
Step 7: Now you can access the AirlineBookingSystem.

That's it!!!


Note : If you face problem in JDBC connection use the given mysqlconnector jar.

How to add MysqlConnector Jar file ?
Step 1: Download myysqlconnector.jar from repository.
Step 2: Open NetBeans and select the project go to project particular library left click on that select add JAR.
Step 3: Select that downloaded mysqlconnector JAR file and open it.
Step 4: All done finally run the program.

How to add JCalendar Jar file ?
Step 1: Download JCalandar.jar from repository.
Step 2: Extract it.
Step 3: Open NetBeans go to tools>palette>Swing/AWT Components a dialog box will appear select swing control then select add from JAR choose from extrcted Jcalander JAR folder go to lib folder inside lib choose Jcalandar jar then click next select all component(like JDateChooser ,JCalandar.. etc) and then next select swing controler and finally click on finish.
Step 4: Select that downloaded mysqlconnector JAR file and open it.
Step 5: All done finally run the program.

How to add AirLineSys_DB_Backup.sql in your system.
Step 1. Open mysql command line using your password.
Step 2. Create database with name MyAirlineSystem.
Step 3. Now write the following commands one by one :
  use database MyAirlineSystem
  source file_path(like C:\Users\Avinash Kumar\Downloads\Compressed\....AirLineSys_DB_Backup.sql;
  
 then press enter
 Your sql table will be inserted.

Thank You!
</pre>


<h1>Screensots</h1>


![login](https://user-images.githubusercontent.com/120415611/212031547-357cf6aa-119d-44df-b205-5c839c7b48b7.png)

![Dashboard](https://user-images.githubusercontent.com/120415611/212031773-d6572cb6-6011-49bf-98e1-4237ff7f6647.png)

![addcust](https://user-images.githubusercontent.com/120415611/212032055-d09192c3-7565-4ab0-a9e7-489b4e0e0400.png)

![addfilght](https://user-images.githubusercontent.com/120415611/212032144-5e87088a-6bc2-499c-953b-bd45d0e68acd.png)

![searchcust](https://user-images.githubusercontent.com/120415611/212032227-6d9058eb-bff2-4626-9d81-2aeee36a5f17.png)

![printtkt](https://user-images.githubusercontent.com/120415611/212032303-db71b7f4-bb94-4237-9ee7-09b7332a6c13.png)

![Capture](https://user-images.githubusercontent.com/120415611/214411869-4b210099-9915-44ef-b3ee-8ced1db6e3ad.JPG)


