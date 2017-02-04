ep_user_pad
===========

User-Management System for etherpad-lite

This is the admin tool for the ep_user_pad_frontend plugin for etherpad-lite.

The frontend plugin for the user-management system can be found at

https://github.com/aoberegg/ep_user_pad_frontend/

IMPORTANT NOTE: currently not maintained
========================================

This plugin is currently NOT maintained (apart from smaller bug fixes)! Nevertheless: You are welcome to use the plugin. If you find bugs it would be nice if you can provide pull requests.

Installation
------------

In order to use this plugin you have to [configure Etherpad Lite to use MySQL as backend database](https://github.com/ether/etherpad-lite/wiki/How-to-use-Etherpad-Lite-with-MySQL).

After that you can install the plugin from the administrator interface or with the npm package manager by typing:

    npm install ep_user_pad

Then use the provided [SQL script](/sql_listing.sql) to create the schema:

    mysql -u USER -p < sql_listing.sql

Please look at installation.pdf for further installation informations. 

Known alternatives to this plugin
---------------------------------

- https://github.com/PabloCastellano/ep_maadix/
- https://github.com/framasoft/ep_mypads
- https://github.com/vltugraz/ep_user_pads
- https://github.com/reality/ep_frontend_community
