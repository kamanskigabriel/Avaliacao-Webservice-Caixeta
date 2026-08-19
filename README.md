# Avaliacao-Webservice-Caixeta
----------------------------------------------------------------
## Nome
Gabriel Kamanski Oliveira

## Curso
Curso - Técnico em informática para a internet

## Unidade curricular
2026

## Breve descricao do projeto

Serviço web REST individual desenvolvido em Node.js com o framework Express, para o domínio de uma biblioteca, gerenciando o recurso livro. A aplicação implementa os quatro verbos HTTP fundamentais — GET, POST, PUT e DELETE — todos representando os dados de entrada e saída em JSON, e respondendo com o código de status HTTP adequado a cada situação (200, 201, 204 e 404).

Os dados são armazenados em uma lista (array) em memória, simulando um banco de dados simples enquanto o servidor está em execução.

## Endpoints
`Get /status`
`Get /livros`
`Get /livros/: id`
`Post /livros`
`Put /livro/: id`
`Delete /livros/: id`
## como clonar
Clonar o repositorio
com "Git clone <URL>"
## intalação
npm i express
npm init
npm i
## Como rodar via GitBash
npm run dev