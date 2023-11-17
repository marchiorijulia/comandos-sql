# Comandos SQL

* Para executar os comandos CTRL + Enter

### Criar database
```
create database NOME_DATABASE;
```
### Definir a database de uso
```
use NOME_DATABASE;
```
### Criar tabela de usuários
```
create table usuarios(
	id int not null auto_increment,
    nome varchar(120) not null,
    email varchar(120) not null,
    senha varchar(120) not null,
    dt_nascimento date,
    primary key(id)
);
```

### Inserir dados
```
insert into usuarios(nome, email, senha, dt_nascimento)
values ('Renato', 'renato@gmail.com', 'secreta', '2000-05-12');
```
### Listar dados da tabela de usuários
```
select * from usuarios;
```