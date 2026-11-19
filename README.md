# RdvMedecins - Um exemplo cliente/servidor com NestJS e Angular

**O curso está disponível online aqui: [https://stahe.github.io/br-angular-nestjs-sept-2026/](https://stahe.github.io/br-angular-nestjs-sept-2026/)**

Este repositório contém apenas este README: o curso em si é publicado no endereço acima.

## Visão geral

Este curso constrói, passo a passo, uma aplicação completa de agendamento de consultas médicas ("RdvMedecins"): um servidor web NestJS/TypeScript que expõe uma API JSON, um banco de dados MySQL e um cliente Angular que consome essa API. Ele termina com autenticação baseada em token JWT e controle de acesso por papéis (ADMIN/USER).

Trata-se de uma migração para tecnologias modernas do curso [*Um exemplo cliente/servidor - AngularJS 1.x / Spring 4*](https://stahe.github.io/br-spring-angular1.x-juillet-2014/) (2014): mesmo estudo de caso, mesma arquitetura em camadas, mas com o servidor Java/Spring substituído por NestJS/TypeScript e o cliente AngularJS 1.x substituído por Angular (componentes standalone, signals).

## O que você encontrará no curso

- Configuração do ambiente de desenvolvimento (Node.js, MySQL, Visual Studio Code) e criação do banco de dados;
- Uma introdução ao NestJS: modelo de desenvolvimento, decoradores e injeção de dependência, por meio de um miniprojeto antes do estudo de caso;
- A construção do servidor NestJS completo do RdvMedecins: entidades TypeORM, camada DAO, camada de lógica de negócio, camada web (controllers e rotas JSON);
- Uma introdução ao Angular: do AngularJS 1.x à versão atual do Angular, componentes, signals, componentes standalone, injeção de dependência, comunicação HTTP e a nova sintaxe de controle de fluxo (`@if`, `@for`);
- O desenvolvimento completo do cliente Angular do RdvMedecins: modelos, serviços, interceptors, tradução da interface para francês/inglês, componentes;
- A adição de autenticação baseada em token JWT e de controle de acesso por papéis (ADMIN/USER);
- Uma conclusão que resume o que foi construído e traz sugestões para aprofundamento.

Cada explicação de código usa os identificadores exatos do código apresentado (tabelas, colunas, classes, decoradores etc.) para garantir a precisão e ajudar você a acompanhar os exemplos de perto.

## Pré-requisitos

Este documento não pressupõe nenhum conhecimento prévio de NestJS ou Angular. Familiaridade com TypeScript e com os fundamentos do desenvolvimento web (HTTP, JSON, bancos de dados relacionais) facilitará a leitura deste documento.

## Autor
**Claude AI da Anthropic**, revisado por Serge Tahé - setembro de 2026
