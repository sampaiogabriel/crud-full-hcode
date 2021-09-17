# Gerenciamento de Usuários - Template Admin - crud-full-hcode

## Instalação de Dependências Frontend.

Instale o BOWER globalmente, através do seguinte comando: 
```
- npm install -g bower
```

Entre na pasta do frontend para instalar o bower no projeto. 
```
- bower install 
```

Para iniciar o projeto, digite:
```
- npm start 
```

(Port:3000)

## Instalação de Dependências Backend.

Instale as dependências do package.json através do comando:
```
- npm install
```

Para iniciar o servidor, digite: 
```
- node index 
```

(Port:4000)

## API Restful 

# RESTful API de Usuários

[![Hcode Treinamentos](https://www.hcode.com.br/res/img/hcode-200x100.png)](https://www.hcode.com.br)

API desenvolvida em Node.js para o Curso Completo de JavaScript na Udemy.com.

```
## Rotas
Obter todos os usuários:
```
GET /users
```
Exemplo de resultado:
```json
{
    "users":[]
}
```

Cadastrar um novo usuário:
```
POST /users
```
Exemplo de resultado:
```json
{
    "_id":"hjkhfui324",
    "name":"João Rangel"
}
```

Obter dados de um usuário:
```
GET /users/:id
```
Exemplo de resultado:
```json
{
    "_id":"hjkhfui324",
    "name":"João Rangel"
}
```

Editar um usuário:
```
PUT /users/:id
```
Exemplo de resultado:
```json
{
    "_id":"hjkhfui324"
}
```

Excluir um usuário:
```
DELETE /users/:id
```
Exemplo de resultado:
```json
{
    "_id":"hjkhfui324"
}
```