######### Shell script for mysql/mariadb database backup automation ###########

                           ***BY Jithin John Jose***
                           
1)Shell script dump all databases into separate files and stored to specified location


2)Shell script to take automatic backup to single database.


3)Shell script to take automatic backup to all databases to single file.


4)set permission of script to 755 and run ./(filename).sh


5)Cron job for scheduling backup


6)If the file was compressed, uncompressed it first : gunzip [file_name].sql.gz


7)Restore from backup using :  mysql -u root -p < dbname.sql
