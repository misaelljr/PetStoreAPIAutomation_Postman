<h1 align="center"> Testes automatizados na API PetStore com Postman </h1>

![Badge em Desenvolvimento](http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge)

<p align="left">🚀 Este repositório contém uma collection exportada via Postman com um projeto de automação de testes da <a href="https://github.com/swagger-api/swagger-petstore">API PetStore</a>

### Features

- [x] Importação de Swagger no Postman
- [x] Ordenação de requisições seguindo o padrão <a href="https://pt.wikipedia.org/wiki/CRUD">CRUD</a>
- [x] Geração de dados de teste usando o <a href="https://learning.postman.com/docs/writing-scripts/pre-request-scripts/">pre-request script</a> do Postman
- [x] Uso de uma variação da heurística <a href="https://maximilianoalves.medium.com/vader-heuristica-para-teste-de-api-na-pratica-fcf78c6acec">VADER (Verbos, Authorization, Data, Errors e Responsiveness)</a> para escrita dos testes de API
- [x] Escrita de casos de teste em Javascript para serem executados no Postman
- [x] Geração de um relatório dos resultdos do teste usando <a href="https://learning.postman.com/docs/running-collections/using-newman-cli/installing-running-newman/">Newman</a>
- [ ] Integração direta com o Git

### Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas: [Postman](https://www.postman.com/downloads/) e [Newman](https://www.npmjs.com/package/newman)

### Gere um report dos testes via Newman
 
```bash
# Executar comando no terminal
$ newman run Swagger\ Petstore.postman_collection.json
```

### Autor
---

<a href="https://scholar.google.com/citations?user=kwbs4ksAAAAJ&hl=en">
 <img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/11947429?v=4" width="100px;" alt=""/>
 <br />
 <sub><b>Misael Jr</b></sub></a> <a href="https://scholar.google.com/citations?user=kwbs4ksAAAAJ&hl=en" title="Rocketseat">🚀</a>


Feito com ❤️ por Misael Jr 👋🏽 Entre em contato!

[![Linkedin Badge](https://img.shields.io/badge/-Misael-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/misaelljr/)](https://www.linkedin.com/in/misaelljr/) 
[![Gmail Badge](https://img.shields.io/badge/-juniomisael@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:juniomisael@gmail.com)](mailto:juniomisael@gmail.com)
