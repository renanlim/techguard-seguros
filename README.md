# TechGuard Seguros — MVP

> Sprint de Gestão Ágil de Projetos e Produtos

---

## Sobre o projeto

O **TechGuard Seguros** é um MVP de plataforma web para contratação digital de seguros para equipamentos eletrônicos como notebooks, celulares, tablets e hardware corporativo.

O objetivo é validar se usuários conseguem cadastrar seus dados, registrar um equipamento, escolher um plano de cobertura e gerar uma apólice digital — tudo de forma simples, rápida e sem atendimento manual.

---

## Problema e oportunidade

Contratar seguro para equipamentos eletrônicos ainda é um processo burocrático, pouco transparente e dependente de atendimento humano. O TechGuard Seguros resolve isso com uma experiência 100% digital, focada em clareza e autonomia para o cliente.

---

## Público-alvo

- Pessoas físicas com equipamentos eletrônicos de valor
- Profissionais autônomos que dependem de equipamentos para trabalhar
- Pequenas empresas com dispositivos utilizados por colaboradores
- Equipes internas de seguradoras (analistas operacionais)

---

## Funcionalidades do MVP

| Funcionalidade | Rota da API |
|---|---|
| Cadastrar segurado | POST /segurados |
| Listar segurados | GET /segurados |
| Consultar segurado por ID | GET /segurados/{id} |
| Cadastrar equipamento | POST /equipamentos |
| Listar equipamentos | GET /equipamentos |
| Listar equipamentos de um segurado | GET /segurados/{id}/equipamentos |
| Listar planos disponíveis | GET /planos |
| Gerar apólice digital | POST /apolices |
| Listar apólices | GET /apolices |
| Documentação interativa da API | GET /apidocs (Swagger) |

---

## Stack técnica

- **Back-end:** Python + Flask + SQLite + Swagger (Flasgger)
- **Front-end:** Single Page Application (SPA) em HTML, CSS e JavaScript puro

---

## Time Scrum hipotético

| Papel | Responsabilidade |
|---|---|
| Product Owner | Prioridades, validação de requisitos, representação do negócio |
| Scrum Master | Cerimônias ágeis, remoção de impedimentos |
| Dev Back-end | API REST, regras de negócio, banco de dados, Swagger |
| Dev Front-end | Interface web, integração com API |
| UX/UI Designer | Fluxo do usuário, wireframes, protótipos |
| QA / Tester | Validação de critérios de aceitação e qualidade |

---

## Jira do projeto

Backlog e Sprint 1 construídos no Jira (projeto TG — techguard seguros):

https://renanbio20199.atlassian.net/jira/software/projects/TG/boards/1/backlog?atlOrigin=eyJpIjoiZGZhZTViY2NiNjI2NDJjOTgzZmQxM2ZjMmMwZTkzZjMiLCJwIjoiaiJ9

**Sprint 1:** 17/06/2026 a 01/07/2026 · 10 itens · 40 story points

---

## Épicos do backlog

| Epic | Título | Itens |
|---|---|---|
| TG-5 | Gestão de Segurados | TG-12 a TG-16 |
| TG-6 | Gestão de Equipamentos | TG-17 a TG-21 |
| TG-7 | Gestão de Planos | TG-22 e TG-23 |
| TG-8 | Gestão de Apólices | TG-24 e TG-25 |
| TG-9 | Interface do Usuário | TG-26 |
| TG-10 | Requisitos Não Funcionais | TG-27 a TG-30 |

---

## Estrutura do repositório

```
techguard-seguros-mvp/
│
├── README.md                        ← este arquivo
├── canvas-url.txt                   ← URL do board no Miro (Lean Inception + MVP Canvas)
├── product-backlog.pdf              ← backlog completo: épicos, features, histórias, DoR e DoD
├── sprint-backlog.pdf               ← Sprint 1 detalhada com critérios de aceitação
├── video-url.txt                    ← link do vídeo de apresentação
│
└── wireframes/
    ├── 01-tela-inicial.png
    ├── 02-cadastro-segurado.png
    ├── 03-cadastro-equipamento.png
    ├── 04-planos.png
    └── 05-geracao-apolice.png
```

---

## Lean Inception

A Lean Inception foi conduzida no Miro e cobriu as seguintes etapas:

1. Product Vision
2. O produto É / NÃO É / FAZ / NÃO FAZ
3. Objetivos do produto
4. Personas (João — freelancer, Mariana — pequena empresa, Carlos — analista interno)
5. Jornadas do usuário
6. Feature Brainstorming
7. Revisão técnica, de negócio e de UX
8. Sequenciador
9. MVP Canvas

Acesse o board completo pelo arquivo `canvas-url.txt`.

---

## Sprint 1 — objetivo

Entregar o fluxo principal do MVP: cadastrar segurado e equipamento, visualizar planos disponíveis, gerar e consultar apólices — com API REST documentada via Swagger.

**Total:** 40 story points · **Duração:** 2 semanas (17/06 a 01/07/2026)

---

## Status

Projeto acadêmico desenvolvido para a Sprint de Gestão Ágil de Projetos e Produtos.
