# Andela-Bootcamp-XVI-Database-Assignment

A simple online shopping database for Andela bootcamp XVI <br>


1. Fetch a user with 'username' Ibrahim from 'users' Table.<br>
   SELECT * FROM `users` WHERE `username` = 'Ibrahim' <br>
   
2. Create a new user with 'username' Ibrahim and 'email' lethal@mail.com.<br>
   INSERT INTO `users` ( `username`, `email` ) VALUES ( 'Ibrahim', 'lethal@mail.com' ) <br>
   
3. Fetch an item from 'items' Table whose 'id' is 32. <br>
   SELECT * FROM `items` WHERE `id` = 32 <br>
   
4. Change the Name of an Item in the 'items' Table  with an 'id' 12.<br>  
   UPDATE `items` SET `name` = 'Food Item' WHERE `id` = 12 <br>

5. Remove a row from the 'transactions' table with 'user_id' 3 and 'item_id' 344.
   DELETE FROM `transactions` WHERE `user_id` = 3 AND `item_id` = 344 <br>
