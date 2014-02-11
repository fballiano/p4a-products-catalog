Products catalog application for P4A
====================

To run this sample application you need to import our sample
database schema into your local MySQL.

To do this simply write:
```
mysqladmin create p4a_products_catalogue
mysql p4a_products_catalogue < db_dump_mysql.sql
```

You also need to let composer install all dependencies with
```
composer install
```

Now you can open your browser to:
```
http://localhost/p4a-products-catalog
```
or change the url to reflect the path where you installed the application.

Have fun!
