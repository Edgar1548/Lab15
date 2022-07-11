# Lab15
## Edgar Santos Chacon Arrospide
## P1
> Creacion de la table
``` sql
CREATE TABLE colegio(
	codigo integer,
	nombre varchar(150),
	direccion varchar(200),
	ciudad varchar(100),
	nivelacad integer,
	totalalumnnos integer,
) PARTITION BY RANGE(totalalumnos)
```
