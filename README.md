# External Captive Portal for Ubiquiti Unifi

External captive portal for Ubiquiti Unifi with MySQL database backend.

The captive portal web server can be setup using the instructions given [here](https://gist.github.com/nasirhafeez/4e1c2c5536d313db96e2b4ce4b3b269e). The following actions are required to use the code given in this repo:
 
Copy the `.env.example` file to the upper level folder and change its name to `.env`. Set the values of the given project-wide environment variables in it.

Rename the `parameters.php.example` file to `parameters.php` and set the values of variables according to the current site.

*Install Composer*

Then run `php composer.phar install` to install the packages given in `composer.json`.
