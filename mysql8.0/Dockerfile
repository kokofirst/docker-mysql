FROM mysql:8.0.12

RUN usermod -u 2199 mysql && groupmod -g 2199 mysql && chown -R mysql:mysql /var/lib/mysql && chown -R mysql:mysql /run/mysqld