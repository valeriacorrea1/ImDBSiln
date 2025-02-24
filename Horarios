mysql> show databases;
+--------------------------------+
| Database                       |
+--------------------------------+
| information_schema             |
| performance_schema             |
| valeriacorrea20$default        |
| valeriacorrea20$valeriacorrea1 |
+--------------------------------+
4 rows in set (0.01 sec)

mysql> use valeriacorrea20$default;
Database changed
mysql> show tables;
+-----------------------------------+
| Tables_in_valeriacorrea20$default |
+-----------------------------------+
| detalle_horario                   |
| horario                           |
| plantilla_detalle_horario         |
+-----------------------------------+
3 rows in set (0.00 sec)

mysql> DESC USUARIOS;
ERROR 1146 (42S02): Table 'valeriacorrea20$default.USUARIOS' doesn't exist
mysql> CREATE TABLE usuarios ( id int(10) not null, nombre varchar(15) not null, apellido varchar(15) not null, departamento varchar(20) not null primary key(id,nombre) );
ERROR 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near '(id,nombre) )' at line 1
mysql> CREATE TABLE usuarios (
    -> id int(10) not null,
    -> nombre varchar(15) not null,
    -> apellido varchar(15) not null,
    -> departamento varchar(20) not null,
    -> primary key(id,nombre)
    -> );
Query OK, 0 rows affected, 1 warning (0.03 sec)

mysql> 
mysql> insert into usuarios(id,nombre,apellido,departamento) values
    -> (1,'salvador','rivera','compras'),
    -> (1,'carlos','lopez','compras'),
    -> (1,'yael','zapata','compras'),
    -> (1,'dante','martinez','compras'),
    -> (1,'araceli','flores','compras'),
    -> (1,'juan','arenas','compras'),
    -> (1,'esmeralda','dueñas','compras'),
    -> (1,'victoria','ortiz','compras'),
    -> (1,'alejandro','quirarte','compras');
Query OK, 9 rows affected (0.00 sec)
Records: 9  Duplicates: 0  Warnings: 0

mysql> desc usuarios;
+--------------+-------------+------+-----+---------+-------+
| Field        | Type        | Null | Key | Default | Extra |
+--------------+-------------+------+-----+---------+-------+
| id           | int         | NO   | PRI | NULL    |       |
| nombre       | varchar(15) | NO   | PRI | NULL    |       |
| apellido     | varchar(15) | NO   |     | NULL    |       |
| departamento | varchar(20) | NO   |     | NULL    |       |
+--------------+-------------+------+-----+---------+-------+
4 rows in set (0.00 sec)
mysql> show tables;
+-----------------------------------+
| Tables_in_valeriacorrea20$default |
+-----------------------------------+
| detalle_horario                   |
| horario                           |
| plantilla_detalle_horario         |
| usuarios                          |
+-----------------------------------+
4 rows in set (0.00 sec)
mysql>  select * from usuarios;
+----+-----------+----------+--------------+
| id | nombre    | apellido | departamento |
+----+-----------+----------+--------------+
|  1 | alejandro | quirarte | compras      |
|  1 | araceli   | flores   | compras      |
|  1 | carlos    | lopez    | compras      |
|  1 | dante     | martinez | compras      |
|  1 | esmeralda | dueñas   | compras      |
|  1 | juan      | arenas   | compras      |
|  1 | salvador  | rivera   | compras      |
|  1 | victoria  | ortiz    | compras      |
|  1 | yael      | zapata   | compras      |
+----+-----------+----------+--------------+
9 rows in set (0.00 sec)
mysql> select * from usuarios;
+----+-----------+----------+--------------+
| id | nombre    | apellido | departamento |
+----+-----------+----------+--------------+
|  1 | alejandro | quirarte | compras      |
|  1 | araceli   | flores   | compras      |
|  1 | carlos    | lopez    | compras      |
|  1 | dante     | martinez | compras      |
|  1 | esmeralda | dueñas   | compras      |
|  1 | juan      | arenas   | compras      |
|  1 | salvador  | rivera   | compras      |
|  1 | victoria  | ortiz    | compras      |
|  1 | yael      | zapata   | compras      |
+----+-----------+----------+--------------+
9 rows in set (0.00 sec)
mysql> 
