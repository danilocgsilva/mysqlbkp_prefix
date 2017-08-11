# Technical documentation

1. Checks if the connection info file (connectiondata.txt) is available. Exits if don't.
2. Validates the connectiondata.txt. Asks to correct the format if have something not valid and exits.
3. Tests the connection.
4. Asks to confirm the information from the connectiondata.txt.
5. If everything is ok, backups the database in the following format: mslbkp.YEAR MONTH DAY.HOUR h MINUTE m SECONDS s.sql