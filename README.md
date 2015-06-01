nginx compiled with google's pagespeed nginxmodule.

Installation
============
Switch on appropriate pagespeed filters in global.conf
Build the given docker file
Run ``fig up -d`` to run nginx

Usage
=====
- Docker commands will stop and start nginx. 
- Edit nginxconf/nginx.conf and restart the docker for the changes to take effect.
- global.conf is the first conf file loaded by nginx and is built into the image. 
- If you want to change pagespeed's configurations, you'll have to build the image again.
