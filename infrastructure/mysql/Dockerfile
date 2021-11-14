FROM mysql/mysql-server:8.0.27

ENV MYSQL_DATABASE=cookie \
  MYSQL_USER=phpuser \
  MYSQL_PASSWORD=secret \
  MYSQL_ROOT_PASSWORD=default \
  TZ=Asia/Tokyo

COPY ./my.cnf /etc/my.cnf
RUN chmod 644 /etc/my.cnf