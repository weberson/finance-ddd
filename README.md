# Sistema Financeiro Pessoal com DDD

Este repositório faz parte de uma **série de artigos técnicos sobre Domain-Driven Design (DDD)**, aplicando os principais conceitos da abordagem de forma progressiva, prática e didática.
O objetivo é construir um projeto real, do zero, explicando as decisões de modelagem e arquitetura em cada etapa, com exemplos de código e links diretos para os artigos correspondentes.

---

## Objetivo do Projeto

O projeto simula um sistema de controle financeiro pessoal, onde o usuário poderá:
- Registrar transações (entradas e saídas)
- Gerenciar múltiplas contas (ex: carteira, conta bancária, cartão de crédito)
- Definir orçamentos por categoria e acompanhar gastos
- Gerar relatórios simples para análise

Mais importante do que o sistema em si é **a forma como ele será modelado**, utilizando princípios de DDD e boas práticas de arquitetura de software.

---

## Sobre a Série de Artigos

A série está sendo escrita com os seguintes objetivos:
- Consolidar e compartilhar o conhecimento sobre DDD
- Ensinar conceitos complexos com uma abordagem acessível
- Demonstrar a evolução real de um sistema ao longo do tempo
- Servir como material de estudo e referência pública

Cada artigo implementa uma parte do sistema e está associado a uma branch específica neste repositório.

---

## Estrutura do Repositório

```plaintext
src/
├── Finance.Domain/          # Núcleo do domínio: entidades, VOs, serviços, interfaces
├── Finance.Application/     # Casos de uso (Application Services)
├── Finance.Infrastructure/  # Persistência, repositórios concretos, adapters
└── Finance.API/             # Interface de comunicação (API) — será implementada futuramente

tests/
└── Finance.UnitTests/       # Testes automatizados focados no domínio e na aplicação

README.md
.gitignore
FinanceDDD.sln
```

---

## Artigos da Série

| Parte | Título                                     | Link       |
| ----- | ------------------------------------------ | ---------- |
| 1     | Porque DDD e como vamos aplicar na prática | (em breve) |

---

## Tecnologias Utilizadas
- .NET 8
- C#
- Arquitetura em camadas (inspirada em Clean Architecture)
- Princípios de Domain-Driven Design (DDD)
- xUnit para testes automatizados

---

## Status atual do projeto

✅ Estrutura inicial do projeto criada.
📝 Redação e preparação do primeiro artigo (Parte 1)
🚧 Implementação do domínio começará na Parte 2

---

## Autor

Weberson dos Santos Pereira

📬 *Se quiser acompanhar a série, fique à vontade para seguir, contribuir ou abrir issues. Feedbacks são sempre bem-vindos!*

