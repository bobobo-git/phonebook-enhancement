# Step 1

## creating the app to get data from myPBX with an incoming call
Starting an external application for a call.  
Should be OS independant.

Starting with Windows, calling cmd /K with parameters

# Step 2

Testing access to the phonebook table via Http(s) with __no Success__

# Step 3

Further testing access to the phonebook table via Http(s) with __no Success__

#Step 4

Decision to use an mysql-odbc-connector to access the phonebook-table

# Step 4

It ended with using mysql-odbc-connector and a selfmade  
programm started as external app from myPBX that checks  
incoming calls and shows an inputdialog for input names
and selecting  Numbertype (phone,mobile or home)

i have a running version here.

# [it's alive](https://youtu.be/xos2MnVxe-c?t=4)

# Step 5
Testing phase  __<- WE ARE HERE__

# Step 6

make an installation guide

- mysql-odbc-connector - install & config
- Edit my.cnf to get acces from extern (bind)
- mysql: add one more user for the external access via the mysql-odbc-connector
- install&config the local applikation
- config myPBX to use the local application

# Step 7  

think about if and how to publish it

----
[wiki-reference](http://wiki.innovaphone.com/index.php?title=Reference11r1:Concept_myPBX#Starting_an_external_application_for_a_call)
