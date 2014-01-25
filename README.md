# Zabbix server 2.2 and Percona Mysql easy install

## What is this
Zabbix is an enterprise-class open source software for monitoring of networks and applications. Percona is a high-performance mysql fork. This is an easy-install script for quickly compiling Zabbix for use with Percona mysql. This install uses Zabbix 2.2 source code and Percona Mysql 5.6

This install takes all of the work out of compiling and configuring the server. It's suitable for quickly getting a server online or for testing purposes.

## Installing
Installing is simple. Simply clone the repo and run
```
sudo ./bootstrap
```
and the auto-install script will take care of everything.

If you want to update the zabbix server configs again once you've installed, you can do this easily by visiting ```http://zabbix_server/setup.php```.

## Requirements
This currently only works on Ubuntu/Debian systems. It can be updated for relhat but someone will need to do testing.

This also assumes you have a relatively clean system -- no zabbix or percona/mysql installed already.
