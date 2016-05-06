# PostgreSQL の設定

* パッケージのインストール

```
$ sudo yum install postgresql postgresql-server postgresql-libs postgresql-devel
$ sudo su postgres
bash-4.2$ initdb --encoding=UTF8 --pgdata=/var/lib/pgsql/data
bash-4.2$ exit
$ sudo systemctl start postgresql
$ sudo su postgres
bash-4.2$ psql
postgres=# create role vagrant with createdb login;
CREATE ROLE
postgres=# \q
bash-4.2$ exit
```
