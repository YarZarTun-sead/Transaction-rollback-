# Transaction-rollback-
Testing mysql transaction rollback in node js.
There is 2 table,user and admin.User table has 2 coloums,name and phone.Both data type are varchar.
Admin table also has 2 coloums,name and phone.But name's data type is varchar and phone's data type is int.
So,if you put alphabet in phone field,admin table will get error and the inserted user table data will be rollback.So,it will help you in case of remaining data from broken transacation.
