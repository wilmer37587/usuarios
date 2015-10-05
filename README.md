# usuarios
Proyecto ejemplo - control de versiones

1. Para la creación de la base de datos se debe ejecutar el siguiente script:

```mysql
CREATE DATABASE prueba_control_versiones;

USE prueba_control_versiones;

CREATE TABLE usuario(
	id INT AUTO_INCREMENT NOT NULL,
	numero_documento VARCHAR(10) NOT NULL,
	nombres VARCHAR(50) NOT NULL,
	apellidos VARCHAR(50) NOT NULL,
	direccion VARCHAR(100) NOT NULL,
	telefono VARCHAR(10) NOT NULL,
	PRIMARY KEY(id)
);

```

2. Se debe tener activado el controlador de mysql para realizar pruebas
