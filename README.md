# Session7_Assignment1


a. What is the  use of SQlite open helper class in SQLite?
ans: SQlite open helper class is used in maintaining the creation of database and maintaining
     the upgradation status of the database. It helps in creation of the database by checking
     whether the database is already created or not if not created then it will create the database
     else it will not create the database. In upgradation it will check the version 
     of the database and if there is change in the version that is running then the upgradation
     of the database will take place else the version will continue as it is.


b. What is the use of OnUpgrade function in SQLiteOpenHelper class?
ans: In upgradation it will check the version of the database and if there is change in the version
     that is running then the upgradation of the database will take place else the version will continue 
     as it is.The upgradation of the database means removing a table or adding a table as per the requirement
     of our App.

c. How to show SQLite database table information in android application what is the best way to do it? 
ans: The best way to show the sqlite database table information in android application is using the array
     of object type and pass it through the array adapter and display it through the list view.
