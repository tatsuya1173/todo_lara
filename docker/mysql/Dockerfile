FROM mysql:8.0

ENV MYSQL_DATABASE=sample_db \
  MYSQL_USER=root \
  MYSQL_PASSWORD=root \
  MYSQL_ROOT_PASSWORD=root \
  TZ=Asia/Tokyo

COPY ./my.cnf /etc/mysql/conf.d/my.cnf
RUN chmod 644 /etc/mysql/conf.d/my.cnf