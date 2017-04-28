# README #

This are the files for the ACME WordPress Site (test).

Steps to deploy to production:
1) You need a FTP account so you can upload the files.
2) You need to create a database, and get the data to configure the connection (user, password, database name, passhost).
3) Replace the database connection data in the wp-config.php
4) Upload all files by FTP.
5) Enter to the WP Admin Panel, and rename the site URL. Or directly in the database if you can use a database manager, (table wp_options), replace the Site Url.
6) In the WP Admin Panel go to Settings -> General, and save Permalinks.

