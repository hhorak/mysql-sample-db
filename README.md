# mysql-sample-db

Sample MySQL and MariaDB database data that can be used for upgrade testing.

Database structure and data are taken from [mysqltutorial.org](http://www.mysqltutorial.org/mysql-sample-database.aspx) and the database is initialized with the `mysqld` daemon of particular version. The initialized data of a particular version are kept in corresponding branch.

We have (or plan to have) the following versions available in corresponding branches:

 * [MySQL 5.0](../../tree/mysql-5.0)
 * [MySQL 5.1](../../tree/mysql-5.1)
 * [MySQL 5.5](../../tree/mysql-5.5)
 * [MySQL 5.6](../../tree/mysql-5.6)
 * [MySQL 5.7](../../tree/mysql-5.7)
 * [MariaDB 5.3](../../tree/mariadb-5.3)
 * [MariaDB 5.5](../../tree/mariadb-5.5)
 * [MariaDB 10.0](../../tree/mariadb-10.0)
 * [MariaDB 10.1](../../tree/mariadb-10.1)
 * [MariaDB 10.2](../../tree/mariadb-10.2)

Such data can be used for various tasks, for example testing upgrade.

Generation of the data can be done using `./mysql-sample-db generate` and the data are stored into `./data`.

Validity of the data can be checked using `./mysql-sample-db check` script.

