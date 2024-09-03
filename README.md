## Pelo Postman ou Similar:
## Listar Usuários

```bash
# Acessando a URL será listado todos os usuários, utilizando o método "Get":
# URL: https://app-crudbasico-gen-teste-b90232056227.herokuapp.com/users
```

## Visualizar Usuário Específico

```bash
# Passando o ID do usuário ao final da URL, utilizando o método "Get".
# https://app-crudbasico-gen-teste-b90232056227.herokuapp.com/users/<id>
```

## Adicionar Novo Usuário

```bash
# Enviar o JSON do novo Usuário utilizando o método "Post":
# {
#   "name" : "username",
#   "email" : "email",
#   "password" : "senha"
# }
```

## Atualizar Usuário Específico

```bash
# Enviar o JSON do Usuário passando o ID do mesmo ao final da URL, utilizando o método "Patch":
# Ex.: {
#   "name" : "nome a ser alterado"
# }
```

## Deletar Usuário

```bash
# Passando o ID do usuário ao final da URL, utilizando o método "Delete".
# https://app-crudbasico-gen-teste-b90232056227.herokuapp.com/users/<id>
```