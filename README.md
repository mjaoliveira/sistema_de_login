# sistema_de_login

my sql

create database sistema_de_login
default character set utf8
default collate utf8_general_ci;

create table usuarios(
id int auto_increment primary key not null,
email varchar(100) not null,
senha varchar(32) not null
)default charset = utf8;

insert into usuarios
(email, senha)
values
('suporte@b7web.com.br', md5('123456'));

select *from usuarios;
