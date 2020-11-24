# redmine
Personal notes for the redmine project found here: https://www.redmine.org/

Docker: https://hub.docker.com/_/redmine

The tricky part about priority fields it it's found in 'Enumerations' of Administration. 

The -v /my/own/datadir:/usr/src/redmine/files part of the command mounts the /my/own/datadir directory from the underlying host system as /usr/src/redmine/files inside the container, where Redmine will store uploaded files.


for mysql:

Volument exposed for the database: /var/lib/mysql
