# MariaDB Server 10.11
Bastille template to install and configure MariaDB Server with some sane defaults.

* Disables remote access to MySQL and databases.
* Removes default anonymous users and test databases.
* Has user configurable MySQL settings in /usr/local/etc/mysql/custom.cnf.

## Bootstrap
```
bastille bootstrap https://github.com/jail-templates/mariadb-10.11
```

## Apply template
```
bastille template $JAIL jail-templates/mariadb-10.11
```
