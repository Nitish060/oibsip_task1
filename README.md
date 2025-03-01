# oibsip_task1--> Railway Reservation System
**This is a Java project on Railway Reservation System for Oasis Infobyte internship.**
**It is based on MySQL for the purpose of database which can be accessed by any authorised person to retrieve information and also helps customers for easy use of platform.**

***The following shows the steps to run this application:***

**Prerequisites->**
 
1. Instal JAVA as this application is based on it.
2. MySQL database for storing the information. URL -> https://dev.mysql.com/downloads/installer/
3. You have to connect your code to MySQL database by adding jar file to reference libraries of your program.
4. For the usage of MySQL database you have to create a username and password for it. Set username : 'root', password : '1234'.
5. A new database should be created and name as 'railwaydb'.
6. There should be three tables in 'railwaydb' database and name them as-> 'user','train' and 'chart'.
7. The fields of 'user' table will be uname(string),pass(string),age(int),g(string)(for gender),timestamp(timestamp).
8. The fields of 'train' table will be tnum(int), tname(string), seats(int), bp(string), dp(string), fAC(int), sAC(int), tAC(int), sc(int), doj(date), dtime(string)(departure-time), atime(string)(arrival-time).
9. The fields of 'chart' table will be sno(int), pnr(int), name(string), age(int), g(string)(for gender), seatno(int), coach(string), status(string), timestamp(timestamp), dot(date), tnum(int).

 **The program will be execute through Reservation_sys named file as it contains the main method.**
