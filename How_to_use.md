# How to use

In the same script directory, you must have a file called ```connectiondata.txt```, that will holds the database connection information.

This file must have the following:

```
user:USERNAME
pass:PASSWORD
dbname:DATABASE_NAME
prefix:SYSTEM_PREFIX
host:DATABASE_HOST
deletethisafter:yes|no
```

The ```user```, ```pass```, ```dbname``` and prefix are required.

```host``` is not required. Assumes ```localhost``` if blank.

```deletethisafter``` tells to script if the connectiondata.txt must be deleted after the backup. If not provided, assumes ```yes```.

