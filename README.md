PHP-MySQL-Ciutats-Paissos
=====

DESCRIPTION:
-----

PHP project with MySQL connection.

Page 1 shows a list with countries, and the possibility to add a new city to that country.

Page 2 shows a table with the country, city and country flag.

PREVIOUS REQUIREMENTS:
-----

+ Apache2
+ PHP 7.4
+ MySQL Server
+ Git

INSTALLATION GUIDE:
-----

Once you have succesfully satisfyed all the previous requirements:
1. Open a terminal and move to your Apache folder where you'll clone this repository (usually var/www/html). You can do this with `cd /var/www/html`.
2. Clone this repository in your folder with `git clone https://github.com/JesusSePe/PHP-MySQL-Ciutats-Paissos`.
> Note: It's possible that you don't have permissions to edit that folder. You can solve that adding sudo at the beginning of the previous command.

Now, it's time to add our database to MySQL.

3. `sudo mysql` *Opening MySQL.*

4. `source world.sql` *Adding our database to MySQL. This process may last a bit. Be patient.*

5. `CREATE USER 'php'@'localhost' IDENTIFIED BY 'Php_1c4J8';` *Creating a new user for the database.*

6. `GRANT ALL ON world.* TO 'php'@'localhost';` *Granting permissions to the database to our new user.*

7. `exit;` *We finished setting up our database*.

With all this done, our database is ready, and our php program can now run, and execute queries in our database. 

VISITING THE SITE:
-----

If you installed it in a local machine, and didn't set up any server name, you should be able to acces it searching on any browser `localhost/PHP-MySQL-Ciutats-Paissos/world1.php`.

If you installed it in a server, and configured a server name, you should be able to acces it searching on any browser `[Your_server_name]/PHP-MySQL-Ciutats-Paissos/world1.php`.
