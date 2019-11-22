Task Spooler
------------

This is a fork of [Task Spooler](http://vicerveza.homeunix.net/~viric/soft/ts/) by  **Lluís Batlle i Rossell**.

Users
------------------------
If you are in a system which understands POSIX and has the GNU toolkit, you
probably can run:
 make
 make install

If you want to install to another path than /usr/local, you can run:
 make install PREFIX=/usr


Developers
------------------------
Run ". setenv" before adding bugs to the database.
Use 'bug' for the database.  http://freshmeat.net/projects/bug/

ts-1.1
------------------------
Adding a new job options, 
* -R [ram] RAM size (GB) required by the job (0 GB required default)
* -M [num] get/set the number of max RAM (GB) of the server (1 default)


