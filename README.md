Server administration helper scripts
====================================
(needs [postfixadmin][http://postfixadmin.sourceforge.net/])

These scripts are helpful tools for server administration.

What does it do
------------
Reads database tables maintained by [Postfixadmin][http://postfixadmin.sourceforge.net/] and generates
- DNS zonefiles for Bind
- Apache configuration
- Lookup-Tables for Postfix MTA
- User databases in Mysql

Advantages
----------

- Apache runs with static configuration files
- DNS runs with static zone files
- Domains and Mail accounts are fully automated
- A stable server!


Installation
------------

- Copy file ispconfig-example to `/etc/default/ispconfig`
- Copy the shellscripts to `/etc/cron.hourly`
    

Requirements
-----
- postfixadmin
- Mysql
