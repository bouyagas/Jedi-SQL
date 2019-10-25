# Jedi-SQL

Jedis SQL Lab
1. Seeding the Database
First, let's seed the database together. I'll be walking through this with you, but for later reference here is the series of commands you will need to do when you seed a database.

Create new database
createdb jedi_db in terminal
Connect to the database to make sure it has been created
psql -d jedi_db in terminal
exit out of psql shell with \q
Run seeds file in new database
psql -d jedi_db -f jedis.sql in the terminal
Connect to database and check if seeded correctly
psql -d jedi_db in terminal
SELECT * FROM jedis; in psql shell

2. Exercise
SELECT all Jedis with red lightsabers
SELECT all Jedis who have been tempted by the darkside
UPDATE all gray lightsabers to green
UPDATE all Jedis who have been tempted by the darkside so that their training goes up by 10
UPDATE all Jedis with blue lightsabers so that their training goes up by 30
Select the temptation from all Jedis whose training is more thann 8 years.
SELECT the lightsaber color and name of all Jedis whose training is less than 8 years and who are not tempted by the darkside
Find the sum of all the jedis years_training who have blue lightsabers
Find the average years_training of all jedis who are not tempted by the darkside
Find the sum of all jedis years_training who are not tempted by the darkside and have purple lightsabers
