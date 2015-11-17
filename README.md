PHP 5.5.25 for Ubuntu 10.04, configured for Moodle

This is the standard PHP 5.5.25 built from source

Note: Use the first release, the second release I published was not packaged right

Ensure that you have removed any other versions of PHP you might have installed, sudo apt-get remove --purge method

How to Install?

Step 1: sudo service apache2 stop

Step 2: wget https://github.com/bshp/php-55_moodle/blob/master/php_5.5.25-1_amd64.deb

Step 3: dpkg -i php_5.5.25-1_amd64.deb

Step 4: copy contents of /etc/php5/apache2

Step 5: sudo service apache2 reload

Step 6: sudo service apache2 start

*Note: All PHP binaries and extensions will be placed in the default Ubuntu locations. PHP-CLI is built into the standard PHP Binary.

