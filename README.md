Samba4 init script for Debian Wheezy
==================

This init script from samba wiki doesn't work for me: https://wiki.samba.org/index.php/Samba4/InitScript 

So, I cutomized it a little bit.  Please feel free to use it :) 

Usage
-----
Make the init script executable
```
chmod 755 /etc/init.d/samba4
```
Enable the script at startup
```
update-rc.d samba4 defaults
```
