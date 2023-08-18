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

## Support
Templates will be maintained until their respective software version is end-of-life. Repositories will then be archived and removed from any meta-templates.

If you have a question, suggestion or find a bug, please let us know via an Issues in the relevant repository or send us an email.

## License
All templates are distributed under the 3-Clause BSD NON-AI License. See `LICENSE` in every template repository for more information.
