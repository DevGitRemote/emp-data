use this cmd
sudo apt install mysql-server
sudo apt install python3
sudo apt install python3-flask
sudo apt install python3-mysql
sudo apt install python3-boto3
----------------------------------------------------------------------------
create table employee (empid VARCHAR (20), first_name VARCHAR (20), last_name VARCHAR (20), primary_skills VARCHAR (20), location VARCHAR (20));
----------------------------------------------------------------------------
in config.py modify the details listed

in ExamApp.py modify search for try statement[block] and modify region name and table name

After all steps go to aws-code-main directory and run sudo python3 EmpApp.py 
