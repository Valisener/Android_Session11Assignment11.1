# Android_Session11Assignment11.1


A It is designed to manage the database creation and version management, It takes care of opening the database if it finds one, if not it creates the database, upgrades the database when it is needed. Helps maintain the database as well over all a very useful class for database usage.


b. is for changing the database, adding new columns ect... adding constraints. The users that use an old version with the old version in the database releasing a new database version will automatically get the old users running the new database to avoid problems. This way they can upgrade the database without having to delete the entire database and lose the information they had and recreate it otherwise it would be very troublesome to keep having to delete the database and losing all the things in the database.


c. With a ListView in an XML file and then in the java code link the ListView to the reference in the xml file then set an adapter to it the adapter handles the information the listview will show the database table information. The adapter would be filled using an ArrayList to hold all of the data from the database.

Not sure if thats what you were talking about, do you mean the information that is set in the table? or displaying the column information like Type, Column name, ect?

If thats not what you were asking then you can get Android Device Monitor to bring up the database for the android application however its been gotten rid of in the recent update of android there is a button on the bottom right Device File Explorer you can use that to get the database file from the application if thats what you were talking about.
