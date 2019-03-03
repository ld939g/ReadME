Log Analysis with SQL

##Description
Developing a python script to run SQL commands against a database including large data to show a report of:

  •	Three most viewed articles
	•	Most viewed authors
	•	Days where more then 1% of requests returned errors

Requirements
	•	Pyton Editor
	•	Vagrant & VirtualBox

Set up
	1.	Install Vagrant & Virtual Box 
	2.	Bring the virtual machine online using command (vagrant up) then log in with command vagrant ssh
	3.	Download database from here  (newsdata.sql)
	4.	Open code within vagrant follow instructions 
	5.	Load the database psql -d news -f newsdata.sql
	6.	Explore Data (Authors, Articles, Logs)
	7.	Load .py file in the vagrant directory then run to see data

Example Data Below:
Popular Articles:

"Candidate is jerk, alleges rival" - 338647 views
"Bears love berries, alleges bear" - 253801 views
"Bad things gone, say good people" - 170098 views

Popular Authors:

Ursula La Multa - 507594 views
Rudolf von Treppenwitz - 423457 views
Anonymous Contributor - 170098 views
Markoff Chaney - 84557 views

Days on which more than 1% of requests lead to errors:

July      17, 2016 - 2.3% errors


