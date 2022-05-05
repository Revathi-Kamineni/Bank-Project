# Bank-Project
The Banking System project is a java application that allows users to register and manage their accounts. Clients can register accounts and they are able to edit their profile, view their account, transfer money.
# Technologies used :
Java,JDBC,MySQL,Maven,JUnit,Log4J
# Getting started :
git clone git@github.com/Revathi-Kamineni/Bank-Project.git
Eclipse or webdevelopers
MYSQL 8.0.28.0/MYSQL workbench
create project database in mysql
create table trans with type property given below
+-------------+-------------+------+-----+---------+-------+
| Field       | Type        | Null | Key | Default | Extra |
+-------------+-------------+------+-----+---------+-------+
| fromid      | varchar(20) | YES  |     | NULL    |       |
| toid        | varchar(20) | YES  |     | NULL    |       |
| transamount | double      | YES  |     | NULL    |       |
| date        | date        | YES  |     | NULL    |       |
+-------------+-------------+------+-----+---------+-------+
create table accountdetails (Account details)
+----+-----------+------------+---------+---------+-----------------+------+
| id | user_name | phone_no   | address | balance | type            | age  |
+----+-----------+------------+---------+---------+-----------------+------+
|  1 | kamineni  | 3763       | jdfh    |    2323 | Savings Account | 19   |
|  2 | dfghj     | 5432       | dfghj   |   56789 | Savings Account | 23   |
|  3 | fg        | 123456     | asdfghj |   12345 | Savings Account | 19   |
|  4 | abcd      | 8989898989 | jhghk   |    5678 | Savings Account | 22   |
|  5 | saisasran | 887766221  | kadapa  |    1000 | Savings Account | 22   |
|  6 | harani    | 89778998   | hgsshjh |    1000 | Savings Account | 20   |
+----+-----------+------------+---------+---------+-----------------+------+
# Features :
We can able to add banking details of the user and able to transfer the amount from one to another account. We have created functions like save(for saving details of the both entities), count(for counting the transactions), delete(deleting the account), transfer(for transfering the amount from one account to another) and edit(for changing the details).
# Usage :
We can able to add the values in both the entities, count the number of transactions, deleting the account and transferring the amount from one account to another account by giving specific details of the users.
