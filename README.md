Download Composer or update composer self-update.
Run php composer.phar create-project --prefer-dist cakephp/app [app_name].
If Composer is installed globally, run

composer create-project --prefer-dist cakephp/app
In case you want to use a custom app dir name (e.g. /myapp/):

composer create-project --prefer-dist cakephp/app myapp
You can now either use your machine's webserver to view the default home page, or start up the built-in webserver with:

bin/cake server -p 8765
Then visit http://localhost:8765 to see the welcome page.

Configuration
Read and edit the environment specific config/app_local.php and setup the 'Datasources' and any other configuration relevant for your application. Other environment agnostic settings can be changed in config/app.php.
