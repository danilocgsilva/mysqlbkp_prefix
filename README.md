# mysqlbkp_prefix

Backups a mysql database based on prefix

Sometimes you can or you needs to have just a single database where you going to install saveral systems. The majority of big good CMSs (like WordPress or Drupal) have the 'prefix' feature available or required by default.

And sometimes you needs to make a system backup. In case where you have several systems in the same database, they are differentiated by tables prefix. And mysql, in its comon backup tool does not considers the tables prefix.

This program fills this gap.
