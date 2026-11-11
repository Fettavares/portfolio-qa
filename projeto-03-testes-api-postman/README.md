# Projeto 03 — Testes de API com Postman

## Sobre o projeto

Projeto prático de testes de API REST utilizando o Postman e a API ServeRest, com foco no aprendizado de requisições HTTP, manipulação de dados em formato JSON e autenticação por Bearer Token.

## Ferramentas utilizadas

- Postman
- API ServeRest
- JSON
- JavaScript
- Métodos HTTP: GET, POST, PUT e DELETE

## Funcionalidades exploradas

### Autenticação
- Realização de login.
- Extração do token de autenticação por meio de script JavaScript.
- Armazenamento do token em variável da coleção.

### Usuários
- Cadastro de usuários.
- Consulta de usuário por ID.
- Listagem de usuários cadastrados.

### Produtos
- Listagem de produtos.
- Consulta de produtos por ID.
- Cadastro de produtos.
- Configuração de requisições para edição e exclusão de produtos.

## Objetivos de aprendizado

- Compreender o funcionamento de APIs REST.
- Praticar os principais métodos HTTP.
- Trabalhar com requisições e respostas em JSON.
- Utilizar variáveis e autenticação no Postman.
- Organizar coleções de requisições para testes de API.

## Como utilizar

1. Instalar o Postman.
2. Importar o arquivo `.postman_collection.json` disponível neste projeto.
3. Configurar a variável `Base_URL` com o endereço da API ServeRest.
4. Criar um usuário administrador e realizar o login.
5. Executar as requisições disponíveis na coleção, configurando os tokens e IDs necessários.

## Melhorias futuras

- Implementar validações automatizadas de status HTTP e respostas.
- Padronizar o gerenciamento do token de autenticação.
- Criar cenários positivos e negativos.
- Corrigir e completar as requisições de edição e exclusão.
- Organizar evidências e resultados dos testes.
