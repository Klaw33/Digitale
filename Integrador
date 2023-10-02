use entrega;
create table Productos (
idbicicleta int(11) not null auto_increment primary key,
Codigo int(4) not null,
Marca Varchar(15) not null,
Modelo varchar(15) not null,
color varchar(15) not null
);

create table Clientes( 
idCliente int not null auto_increment primary key,
Nombre Varchar(15) not null,
Apellido Varchar(15) not null,
DNI Varchar(8) not null,
Domicilio Varchar(30)
); 

CREATE TABLE Tipo_bicicletas ( idtipos int PRIMARY KEY auto_increment,
  codigo INT(3),
  descripcion VARCHAR(20) NOT NULL
);
insert into Tipo_bicicletas(codigo, descripcion) values 
(1, 'Paseo'),
(2, 'Montaña'),
(3, 'Carrera');

select * from Tipo_bicicletas;

insert into Clientes (Nombre, Apellido, DNI) values ('Claudio', 'Lopez', '39618460');

SELECT Clientes.nombre, Clientes.apellido, Productos.Marca, Productos.Modelo, Tipo_bicicletas.descripcion
FROM Clientes
join Productos
join Tipo_bicicletas;
