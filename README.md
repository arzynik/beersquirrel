![Beer Squirrel](https://raw.githubusercontent.com/arzynik/beersquirrel/master/www/icon.png)

## Beer Squirrel

Beer Squirrel is an Image and text sharing tool


#### Deploying on Heroku

The **Procfile** contains what you need to switch between Apache or Nginx. Nginx is set by default.

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)


#### Deploying on your own environment

You will need MySQL and Apache/Nginx installed.

1. Edit your **config/db.ini** file with your user, host, and database.
2. Edit your **config/config.ini** for they type of storage type you want (local, sql)
3. Open either **install/mysql.sql** or **install/pgsql.sql** and load it into your database.
4. If using local storage, make sure **data** is readable.
5. If using Apache, the **web/.htaccess** file should handle what you need.
6. If using Nginx, you should use the **src/nginx.conf** file.


See [Tipsy Documentation](https://github.com/arzynik/Tipsy/wiki) for more information.
