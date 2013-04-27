Nginx Starter
======

A simple Windows program to start and stop your Nginx server and PHP Fast-Cgi.  Useful for Dokuwiki and Taskpaper+ users, and in fact any non-database PHP app.

Screenshots
------
![Start Nginx](https://taskpaperplus.googlecode.com/files/start-nginx.png)
&nbsp;&nbsp;&nbsp;
![Stop Nginx](https://taskpaperplus.googlecode.com/files/stop-nginx.png)


How To Use
------
Place the 2 files (start-nginx.exe, start-nginx.ini) into the root of your Nginx server folder.  E.g.

```
    Nginx
        └ conf
        └ contrib
        └ docs
        └ logs
        └ php
            └ ...
            └ php-cgi.exe
            └...
        └ temp
        └ html
            nginx.exe
            start-nginx.exe
            start-nginx.ini
```
      
By default the program assumes that the php executable (php-cgi-exe) is in the `php` folder, and that all Nginx are in the default `conf` folder.

Now double-click the `start-nginx.exe` program to start.  If all went well a new window should open.  Use the `Start` and `Stop` buttons to get your server going.


Notes
----
The language can be changed in the `start-nginx.ini` file, if you would like to translate it into your language.  The php folder can also be configured here.

----

Author: Symon Bent, 2013-04-25, Madagascar

Website: https://github.com/MrBertie/start-nginx
