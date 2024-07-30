# Projeto Academico

### Funcionalidades:

1. Login
2. Logout
3. Cadastro do Candidato
4. Cadastro de Cursos
5. Cadastro de Salas
6. Listar Candidatos
7. Listar Cursos
8. Listar Salas
9. Geração de Relatórios

## Rodando o Laravel Framework

### Entre no container docker-php com o seguinte comando:

```
docker exec -it php bash
```

### Dentro do container execute os comandos abaixo:

#### Criação do projeto - execute somente na primeira vez.

```
composer create-project laravel/laravel name-app-laravel
```

## Subir o Projeto

### Execute o comando abaixo:

Realize o clone dentro do diretório **public** da Lemp-Stack.

```
git clone https://github.com/Miltex/academico.git
```

### Entre no container docker-php com o seguinte comando:

```
docker exec -it php bash
```

Entre no projeto com o comando abaixo:

```
cd academico
```

Dentro do Container php execute os seguintes comandos:

```
composer install
```


```
php artisan serve --host=0.0.0.0
```


### Acesse o Laravel Framework

http://localhost:8000/