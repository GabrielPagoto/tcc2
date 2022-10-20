Comandos utilizados para subir o MySql no Docker:

cd tcc2/
docker compose up -d
(Em um novo terminal)docker exec -it tcc2-mysql-1 bash
(No bash)mysql -uroot -p tcc2 < tables.sql
(Colocar a senha "root")
mysql -uroot -proot
use tcc2;
show tables;