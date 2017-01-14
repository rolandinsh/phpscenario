# phpscenario
from phpscenario.org

Thank you for downloading phpScenario.

## SETUP

There is no installation procedure per se, but if you're going to be using one
of the built-in data adapters, you'll want to set up your database to match 
the structure expected by those adapters.

The easiest way to do this is to run the included "database.sql" file 
against the database you wish to use for Scenario data. This can be done 
like so (parameters may vary depending on your situation):

mysql -u (your username) -p -D (your database) < database.sql

This will create the following tables:
experiments, treatments, users_treatments

If you would prefer other table names, change those names in the SQL script 
and be sure to specify the ["db"]["tables"] option when configuring phpScenario.

## HELP

Help for phpScenario can be found via forums at the following URL:

http://www.phpscenario.org/forum/

You can also feel free to email the author at james@listy.us

# Copyrights

http://www.phpscenario.org/license.php


