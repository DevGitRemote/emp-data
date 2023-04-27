use this cmd
sudo apt install mysql-server (in webserver and database server)
install below only in database server
sudo apt install python3
sudo apt install python3-flask
sudo apt install python3-mysql
sudo apt install python3-boto3

create table employee (empid VARCHAR (20), first_name VARCHAR (20), last_name VARCHAR (20), primary_skills VARCHAR (20), location VARCHAR (20));

in config.py modify the details listed

in ExamApp.py modify search for try statement[block] and modify region name and table name of DynamoDB table also look for MySql table name,database name.

for about page upload the about.html to s3 bucket>properties>static website hosting | enter name - about.html > proceed > copy url > go to emp-data > templates > nano AddEmp > scroll down >  see like href=/about > delete /about and paste the static web s3 url here.
After all steps go to emp-data directory and run sudo python3 EmpApp.py 
