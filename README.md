## Compilar e Rodar o Projeto

```bash
# dev
$ npm run start:dev
```

## Adicionar Novo Usuário

```bash
# Enviar o JSON do novo Usuário (seguindo o padrão do "CreateUserDto") para a URL
# http://localhost:3000/users/ utilizando o método "Post".
```

## Visualizar Usuários

```bash
# Acessar URL http://localhost:3000/users/ utilizando o método "Get".
```

## Visualizar Usuário Específico

```bash
# Acessar URL http://localhost:3000/users/<id> utilizando o método "Get".
# <id> = id do usuário
```

## Atualizar Usuário Específico

```bash
# Enviar o JSON com os novos dados do Usuário para a URL http://localhost:3000/users/<id>, utilizando o método "Patch".
# <id> = id do usuário
```

## Deletar Usuário

```bash
# Acessar URL http://localhost:3000/users/<id>, utilizando o método "Delete".
# <id> = id do usuário
```