 ##### MySql

### Commands:
Dont forget the ;

mysql = will open up the msql command line interface

show databases; = will show defult databases

use (databse name) = will change to the database that you want. Case sensative 

use mysql; 

show tables; = shows defult tables

Quit; = exits the myqsl command line

Wget = lets us download any webpage or from the net (wget then the url)

Wget https://raw.githubusercontent.com/lerocha/chinook-database/master/ChinookDatabase/DataSources/Chinook_MySql_AutoIncrementPKs.sql

To install use mysql < whatever file –v verbose

pip3 install pymysql  == to install pymysql lets python code to connect with mysql

select * from albums = will select all the albums

select * from Album limit 5; = will limit the amount of search results.

select * from Genre where Name = 'Traditional'

* = Wildcard operator will select everything from that table (if you wanted to search every name with ke* because the wildcard operator is there the search will find any name 
that begins with KE so Kevin or Keira etc

if connecting from MySql from a Python file user name "root" defult user name.

desc Genre; = shows the properties of table. 

insert into Genre (Name) values('Trad') = will insert a new Genre

SELECT LAST_INSERT_ID(); =  will query the GENRE 

select Name from Artist; = will find all names from Artist

select Name from MediaType   =wil display the media types

select FirstName, LastName from Customer; = will find all first names and lastanme of customer.#

select * from Track; = will return all colums in track table

select * from Track where Composer = 'U2';

update Genre set Name = 'Traditional' where Name = 'Trad' = will change the name from trad to traditional

delete from Genre where Name = 'Traditional';= will delete the gere traditional

mysql> select * from Genre where GenreId = 26; = will query the genre we created.

tee file.txt = will log all your activity at the mysql command line to a text file.
notee = will stoplogging to the file.

source = to run a script use the source command followed by the script name. (source test.sql)

