FROM mysql:5.6.41

RUN usermod -u 2199 mysql && groupmod -g 2199 mysql && chown -R mysql:mysql /var/lib/mysql && chown -R mysql:mysql /run/mysqld