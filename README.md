# Meus Resumos de Estudo: Fullstack com JavaScript, Vue.js e Node.js

Bem-vindo(a) ao meu repositório de resumos de estudo! Este espaço foi criado para centralizar e organizar todo o meu aprendizado na stack de desenvolvimento Fullstack com foco em **JavaScript/TypeScript**, o ecossistema **Vue.js (com Quasar)** e **Node.js** para o backend.

O objetivo é criar um guia de referência rápida para mim e para qualquer pessoa da comunidade que esteja estudando os mesmos tópicos.

## Estrutura do Repositório

Os resumos estão organizados em pastas que correspondem aos módulos listados abaixo. Cada pasta contém anotações, exemplos de código e links úteis sobre os respectivos assuntos.

---

## 📚 Módulos de Estudo

### Módulo 1: Fundamentos da Linguagem JavaScript/TypeScript e Programação Orientada a Objetos

#### JavaScript (ES6+)
- **Tipos:** Primitivos e de referência.
- **Operadores:** Aritméticos, relacionais, lógicos, bitwise, ternário, spread/rest.
- **Controle de Fluxo:** `if/else`, `switch`, `for`, `while`, `do while`, `for...in`, `for...of`.
- **Funções:** Declaração, expressões, *arrow functions*, parâmetros *rest*, *callbacks*.
- **Conceitos Avançados:** Escopo, *Hoisting*, *Closures*.
- **Tratamento de Exceções:** `try/catch/finally`, `throw`.
- **Manipulação de Arrays e Objetos.**
- **Estruturas de Dados:** `Map`, `Set`, `WeakMap`, `WeakSet`.

#### TypeScript
- **Fundamentos:** Tipagem estática e inferência de tipos.
- **Tipos:** Básicos, literais, união, interseção.
- **Recursos Avançados:** Funções tipadas, tipos genéricos (*Generics*).
- **Estruturação:** `Interfaces` e tipos personalizados.
- **Tipos Específicos:** `Enums`, `Tuplas`.
- **Metaprogramação:** Introdução a *Decorators*.

#### Programação Orientada a Objetos (POO) em JS/TS
- **Pilares:** Classes e Objetos, Encapsulamento, Herança e Polimorfismo.
- **Abstração:** Uso de `Interfaces` e Classes Abstratas.
- **Contexto:** `this`, `bind`, `call`, `apply`.
- **Boas Práticas:** Princípios **SOLID** aplicados ao JS/TS.
- **Padrões de Projeto (*Design Patterns*):** *Singleton*, *Factory*, *Observer*, *Strategy*.

#### Coleções e Estruturas de Dados
- **Implementações:** Arrays, Pilhas, Filas, *LinkedLists*.
- **Comparações:** `Map` e `Set` vs `Object` e `Array`.
- **Tipagem:** Uso de *Generics* com TypeScript para criar estruturas de dados flexíveis.

---

### Módulo 2: Desenvolvimento Frontend com Vue.js + Quasar + TypeScript

#### Vue.js (3.x, Composition API)
- **Fundamentos:** Instância Vue, diretivas (`v-if`, `v-for`, `v-bind`, `v-model`, `v-on`).
- **Componentização:** Ciclo de vida, composição com `Props` e `Emits`.
- **Reatividade:** `ref`, `reactive`, `watch`, `computed`.
- **Comunicação Avançada:** `Slots`, `Provide/Inject`.
- **Gerenciamento de Estado:** Pinia (ou Vuex 4).
- **Customização:** Diretivas personalizadas.

#### Quasar Framework
- **Setup:** Instalação e estrutura de projeto.
- **Componentes:** Botões, modais, layouts, listas, tabelas e mais.
- **Ferramentas:** Quasar CLI e Vue CLI.
- **Customização:** Temas, design responsivo, ícones, internacionalização (i18n).
- **Plugins:** `Notify`, `Dialog`, `Loading`, etc.

#### HTML5, CSS3 e SCSS
- **Estrutura e Layout:** Semântica, *Flexbox*, *Grid*, *Media Queries*.
- **CSS Moderno:** Variáveis CSS e *custom properties*.
- **Pré-processadores:** SASS/SCSS.
- **Design Responsivo:** *Mobile-first* e técnicas modernas.

#### Testes no Frontend
- **Unitários:** Jest / Vitest.
- **Componentes:** Vue Test Utils.
- **E2E (*End-to-End*):** Cypress ou Playwright.

#### Acessibilidade e SEO
- **Acessibilidade:** Boas práticas de **WAI-ARIA**, contraste, navegação com teclado.
- **SEO:** *Meta tags*, `sitemap.xml`, performance no *Lighthouse*.

---

### Módulo 3: Backend com Node.js + Express/NestJS + APIs REST e GraphQL

#### Node.js
- **Core:** *Event Loop* e Modelo Assíncrono.
- **Módulos Nativos:** `fs`, `path`, `events`, `os`, `http`, `crypto`.
- **Assincronismo:** *Promises*, `async/await`, *callbacks*.
- **Módulos:** Padrão *CommonJS* vs *ESModules*.

#### Express.js
- **Estrutura:** Rotas, *Middlewares*, *Controllers*.
- **Requisições:** *Query params*, *body*, *headers*.
- **Validações:** Joi, Zod, `express-validator`.
- **Autenticação:** **JWT** e **OAuth2** (conceito + prática).
- **Recursos:** Upload de arquivos, `CORS`, *rate limiting*.
- **Design de API:** Princípios **REST**, versionamento.

#### NestJS
- **Arquitetura:** Módulos, Controladores, Serviços, Injeção de Dependência.
- **Recursos:** *Pipes*, *Guards*, *Interceptors*.
- **Ferramentas:** Integração com Swagger, *Middleware*, *Logging*.

#### GraphQL
- **Fundamentos:** *Schemas*, *Queries*, *Mutations*, *Resolvers*.
- **Servidor:** Apollo Server.
- **Comparativo:** Vantagens e desvantagens em relação ao REST.

#### Bancos de Dados
- **SQL (Relacional):** PostgreSQL, MySQL (modelagem, `joins`, normalização).
- **NoSQL (Não Relacional):** MongoDB, DynamoDB (coleções, documentos, índices).
- **ORMs:** Prisma, TypeORM, Sequelize.
- **Gerenciamento:** *Migrations*, *seeds* e relações.

#### Mensageria e Microsserviços (Introdução)
- **Ferramentas:** RabbitMQ, Kafka (conceitos + uso básico com Node).
- **Padrão:** Comunicação assíncrona entre microsserviços.

---

### Módulo 4: DevOps, Arquitetura, Testes e Projeto Profissional

#### Testes e Qualidade
- **Código Limpo:** *Clean Code* e Arquitetura Limpa em JS/TS.
- **Metodologia:** **TDD** com Jest/Vitest.
- **Métricas:** Cobertura de código (*coverage*).
- **Padronização:** *Linting* com ESLint e Prettier.
- **Automação:** Husky e `lint-staged` para *pre-commit hooks*.

#### Docker e CI/CD
- **Conteinerização:** `Dockerfile`, `docker-compose`, *volumes*, *networks*.
- **Build:** Geração de imagens para frontend e backend.
- **Automação de Deploy:** CI/CD com GitHub Actions ou GitLab CI.
- **Plataformas de Deploy:** Heroku, Railway, Vercel, Render, AWS.

#### Cloud e Monitoramento
- **Provedores (Conceitos):** AWS (S3, EC2, Lambda), Azure Functions e GCP.
- **Observabilidade:** Logs, métricas e monitoramento com LogRocket ou Sentry.

#### Segurança Web
- **Princípios:** **OWASP Top 10**.
- **Vulnerabilidades Comuns:** `CORS`, `CSRF`, `XSS`, `SQL Injection`.
- **Boas Práticas:** Criptografia com `bcrypt`, uso de Helmet, *rate limiting*, `HTTPS`.

#### Arquitetura Fullstack Moderna
- **Estrutura de Projeto:** *Monorepo* (Turborepo, Nx).
- **Renderização:** SSR/SSG com Nuxt (Vue) ou Next.js.
- **Padrões de Arquitetura:** **BFF** (*Backend For Frontend*).
- **Design de Software:** *Clean Architecture* + *Domain-Driven Design* (**DDD**) com JS/TS.
