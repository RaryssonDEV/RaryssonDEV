<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/images/hero-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/images/hero-light.svg">
  <img alt="Rarysson Ferreira — Backend Developer. Python, Node.js, PHP/Laravel, APIs REST, automação e dados." src="assets/images/hero-dark.svg" width="100%">
</picture>

<br>

**Desenvolvedor backend.** Construo APIs, conecto sistemas que não foram feitos para conversar entre si e automatizo o trabalho manual que fica no meio do caminho — com Python, Node.js e PHP/Laravel sobre MySQL e PostgreSQL.

## O que eu construo

- **APIs e serviços backend** — endpoints REST com validação, paginação, filtros e testes. Python/FastAPI, Node.js, Laravel.
- **Integração de sistemas** — APIs REST e webhooks movendo dados entre ferramentas, sem ninguém copiando e colando.
- **Automação de processos** — scripts Python, automação de navegador com Playwright, fluxos no Uipath, Automation Anywhere, n8n e Power Automate.
- **Fluxos de dados** — coleta, limpeza e conciliação de dados com pandas e SQL; indicadores no Power BI.

## Stack

| | |
|:--|:--|
| **Backend & APIs** | <picture><source media="(prefers-color-scheme: dark)" srcset="assets/icons/stack-backend-dark.svg"><source media="(prefers-color-scheme: light)" srcset="assets/icons/stack-backend-light.svg"><img alt="Python, FastAPI, Node.js, PHP, Laravel" src="assets/icons/stack-backend-dark.svg" height="36"></picture> |
| **Bancos de dados** | <picture><source media="(prefers-color-scheme: dark)" srcset="assets/icons/stack-databases-dark.svg"><source media="(prefers-color-scheme: light)" srcset="assets/icons/stack-databases-light.svg"><img alt="MySQL, PostgreSQL" src="assets/icons/stack-databases-dark.svg" height="36"></picture> |
| **Automação** | <picture><source media="(prefers-color-scheme: dark)" srcset="assets/icons/stack-automation-dark.svg"><source media="(prefers-color-scheme: light)" srcset="assets/icons/stack-automation-light.svg"><img alt="Playwright, n8n, Power Automate" src="assets/icons/stack-automation-dark.svg" height="36"></picture> |
| **Dados** | <picture><source media="(prefers-color-scheme: dark)" srcset="assets/icons/stack-data-dark.svg"><source media="(prefers-color-scheme: light)" srcset="assets/icons/stack-data-light.svg"><img alt="pandas, Power BI, ETL" src="assets/icons/stack-data-dark.svg" height="36"></picture> |
| **Ferramentas** | <picture><source media="(prefers-color-scheme: dark)" srcset="assets/icons/stack-tools-dark.svg"><source media="(prefers-color-scheme: light)" srcset="assets/icons/stack-tools-light.svg"><img alt="Git, GitHub, VS Code, Postman" src="assets/icons/stack-tools-dark.svg" height="36"></picture> |

## Projetos em destaque

### [Book Catalog API](https://github.com/RaryssonDEV/books-api) — a mesma API, construída duas vezes
`PHP 8.1` `Laravel` `MySQL` `PHPUnit`

API de catálogo de livros (CRUD) com paginação e filtros por título e autor, implementada de duas formas para comparar os trade-offs:

- **[books-api](https://github.com/RaryssonDEV/books-api)** — Laravel: rotas versionadas (`/api/v1`), validação com Form Requests, API Resources, migrations/seeders e testes de feature.
- **[API-BOOK](https://github.com/RaryssonDEV/API-BOOK)** — PHP puro, sem framework: roteamento próprio sobre camadas Repository → Service → Validator, com erros em JSON estruturado (`422` em falhas de validação).

### [Corretor de Municípios IBGE](https://github.com/RaryssonDEV/Najason-Test)
`Python` `pandas` `RapidFuzz` `API REST`

**Problema:** um CSV de municípios brasileiros cheio de erros de digitação e acentos faltando. **Solução:** um pipeline que carrega uma única vez a lista oficial de municípios do IBGE, normaliza os nomes, faz matching aproximado de cada registro, gera um CSV corrigido com estatísticas e envia o resultado para uma API externa.

### [Mini Gerador de Roteiro](https://github.com/RaryssonDEV/mini-gerador-fht)
`Node.js` `HTTP` `API JSON` `node:test`

Aplicação web servida por um endpoint JSON (`POST /api/gerar`) sobre o módulo `http` nativo do Node — zero dependências em runtime — com validação de entrada e testes automatizados para casos de borda, como campos ausentes ou só com espaços.

<details>
<summary><b>Outros projetos</b></summary>
<br>

- **[Recintos do Zoo](https://github.com/RaryssonDEV/desafio-RaryssonDEV-2025)** — motor de regras de um desafio técnico (StartDB): aloca animais em recintos respeitando bioma, espaço e convivência entre espécies. JavaScript + Jest.
- **[Telemedicina](https://github.com/RaryssonDEV/Telemedicina)** — modelagem relacional normalizada para um sistema de telemedicina: pacientes, profissionais, consultas, prescrições, exames e pagamentos. MySQL.
- **[Gerador de NFS-e](https://github.com/RaryssonDEV/NSE-Project)** — gerador de nota fiscal de serviço com cálculo automático de impostos (IRPF, PIS, COFINS, INSS, ISSQN) e exportação em PDF. JavaScript.

</details>

## Atividade

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/generated/top-langs-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/generated/top-langs-light.svg">
  <img alt="Linguagens nos repositórios públicos, por volume de código (sem HTML/CSS)" src="assets/generated/top-langs-dark.svg" height="165">
</picture>
<!--
  Ativar quando houver mais atividade pública (o workflow já gera estes arquivos):
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/generated/stats-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/generated/stats-light.svg">
  <img alt="Estatísticas do GitHub" src="assets/generated/stats-dark.svg" height="165">
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/generated/streak-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/generated/streak-light.svg">
  <img alt="Sequência de contribuições no GitHub" src="assets/generated/streak-dark.svg" height="165">
</picture>
-->

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/generated/snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/generated/snake-light.svg">
  <img alt="Gráfico de contribuições animado como uma cobra comendo as células" src="assets/generated/snake-dark.svg" width="100%">
</picture>

<sub>Card de linguagens: proporção de código nos meus repositórios públicos (sem HTML/CSS), não um ranking de domínio. As imagens são regeneradas diariamente por uma <a href=".github/workflows/profile-assets.yml">GitHub Action</a> e ficam salvas neste repositório.</sub>

## Contato

[![LinkedIn](https://img.shields.io/badge/LinkedIn-rarysson--ferreira-161B22?style=flat-square)](https://www.linkedin.com/in/rarysson-ferreira/) [![E-mail](https://img.shields.io/badge/E--mail-raryssondev%40gmail.com-161B22?style=flat-square)](mailto:raryssondev@gmail.com) [![GitHub](https://img.shields.io/badge/GitHub-RaryssonDEV-161B22?style=flat-square)](https://github.com/RaryssonDEV)

<br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/images/footer-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/images/footer-light.svg">
  <img alt="" src="assets/images/footer-dark.svg" width="100%">
</picture>
