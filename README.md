# 📚 Miniguia de SQL: Do Básico ao Avançado no NotebookLM

> **Link do Caderno no NotebookLM:** 📖 [Do zero ao profissional, guia completo](https://notebook.google.com/notebook/ed52f153-fe46-443d-8a27-760f5bea25e2)

---

## 🎯 Contexto e Objetivos

Este repositório contém um guia prático de SQL construído e organizado através do **NotebookLM**.

O material foi modelado no formato de um curso progressivo: vai desde o nível **introdutório** (ideal para quem nunca teve contato com banco de dados) até conceitos **avançados** de consulta e otimização.

### Objetivos de Estudo:
* Preencher lacunas de conhecimento acumuladas em cursos anteriores sobre SQL.
* Aprofundar o entendimento teórico e prático sobre bancos de dados relacionais.
* Criar uma base de conhecimento interativa no NotebookLM para testar e validar aprendizados na prática.

---

## 📑 Curadoria de Fontes

Para alimentar o NotebookLM e garantir um aprendizado completo, foram selecionadas fontes em vídeo, artigos e cheat sheets técnicas:

**[Learn SQL Beginner to Advanced in Under 4 Hours](https://www.youtube.com/watch?v=OT1RErkfLNQ)

**[Curso SQL Completo 2025 Iniciantes + Desafios + Muita Prática](https://www.youtube.com/watch?v=G7bMwefn8RQ)

**[SQL Cheat Sheet](https://www.itechguides.com/sql-cheat-sheet-basic-to-advanced/)

**[SQL Full Course for Beginners (30 Hours) – From Zero to Hero](https://www.youtube.com/watch?v=SSKVgrwhzus)

---

## 🔬 Engenharia de Prompts e "Cicatrizes" (Troubleshooting)

### Prompts Estratégicos Testados

* **Prompt de Persona (Instrutor):**
  > *"Aja como um curso profissionalizante de SQL, mostrando explicações claras do básico ao avançado com exercícios práticos ao final de cada módulo."*
* **Prompt de Teste de Conhecimento:**
  > *"Crie um conjunto de 5 questões práticas sobre JOINs e cláusula WHERE com cenários do mundo real para eu testar meu aprendizado."*

### Dificuldades Encontradas e Ajustes (Troubleshooting)

| Dificuldade | Causa | Como foi resolvido no Prompt |
| :--- | :--- | :--- |
| **Respostas muito genéricas** | Perguntas sem restrição do nível de detalhamento. | Adição de contexto: *"Forneça exemplos práticos de sintaxe e explicação do 'porquê' a consulta funciona desse jeito."* |
| **Mistura de sintaxes entre SGBDs** | O modelo trazia sintaxes de SQL Server e PostgreSQL juntas. | Especificação explícita do ecossistema estudado nos prompts. |

---

## 🛠️ Miniguia de Estudo (Entrega Final)

### Resumo Estruturado dos Módulos

1. **Módulo Introdutório:** O que é banco de dados relacional, estrutura de tabelas e comandos DDL/DML básicos (`CREATE`, `INSERT`, `SELECT`, `WHERE`).
2. **Módulo Intermediário:** Agrupamentos (`GROUP BY`, `HAVING`), ordenação e combinação de dados através de `JOIN`s (`INNER`, `LEFT`, `RIGHT`).
3. **Módulo Avançado:** Otimização de consultas, subconsultas, CTEs (`WITH`) e funções de janela (*Window Functions*).

---

### Glossário de Conceitos

* **SQL (Structured Query Language):** Linguagem padrão para gerenciamento e manipulação de bancos de dados relacionais.
* **SGBD (Sistema Gerenciador de Banco de Dados):** Software responsável por criar, gerenciar e manipular bancos de dados (ex: PostgreSQL, MySQL).
* **Primary Key (Chave Primária):** Campo único que identifica de forma exclusiva um registro em uma tabela.
* **Foreign Key (Chave Estrangeira):** Campo que estabelece um relacionamento entre duas tabelas.

---

### Prompts Reutilizáveis para Revisão Futura

```markdown
### 🤖 Prompt 1: Dúvidas de Sintaxe
"Explique a diferença prática entre `WHERE` e `HAVING` no SQL usando um exemplo simples de tabela de vendas."

### 🤖 Prompt 2: Gerador de Desafios
"Me dê um problema de consulta SQL de nível intermediário envolvendo JOIN de duas tabelas. Não mostre a resposta até que eu tente resolver."
