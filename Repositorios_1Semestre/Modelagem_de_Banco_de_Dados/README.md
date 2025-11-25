# Modelagem de Banco de Dados 🗄️

**Semestre:** 1º  
**Status:** Concluído

---

## 📝 Descrição
Este repositório documenta os estudos e projetos práticos realizados na disciplina de **Modelagem de Banco de Dados**.

O foco do conteúdo é a compreensão de como estruturar dados de forma eficiente, passando pelas etapas de abstração do mundo real (Conceitual), estruturação relacional (Lógico) e implementação de scripts (Físico).

## 🎯 Objetivos
- Compreender os conceitos de Entidade, Atributo e Relacionamento.
- Criar Diagramas Entidade-Relacionamento (DER/MER).
- Aplicar regras de Normalização (1FN, 2FN, 3FN) para evitar redundâncias.
- Definir Chaves Primárias (PK) e Chaves Estrangeiras (FK).
- Introdução à linguagem SQL (DDL e DML) para criação e manipulação de tabelas.

## 🛠 Tecnologias e Ferramentas Utilizadas
*   **SGBD (Sistema Gerenciador):** [Preencha aqui: Ex: MySQL / PostgreSQL / SQL Server / Oracle]
*   **Ferramentas de Modelagem:** [Preencha aqui: Ex: brModelo / MySQL Workbench / Draw.io / StarUML]
*   **Linguagem de Consulta:** SQL (Structured Query Language)

## 📂 Estrutura dos Arquivos

Os arquivos estão organizados seguindo as fases do projeto de banco de dados:

| Pasta | Descrição | Extensões Comuns |
| :--- | :--- | :--- |
| **01_Modelagem_Conceitual** | Diagramas de alto nível (MER) focados nas regras de negócio. | `.brM3`, `.png`, `.pdf` |
| **02_Modelagem_Logica** | Esquemas relacionais com definição de tipos de dados e chaves. | `.mwb`, `.png` |
| **03_Scripts_SQL** | Scripts de criação do banco (`CREATE TABLE`) e inserção de dados (`INSERT`). | `.sql` |
| **04_Consultas_Basicas** | Exercícios práticos de `SELECT`, filtros e ordenação. | `.sql` |

## 🚀 Como Executar os Scripts SQL

1.  Abra a ferramenta de banco de dados de sua preferência (ex: MySQL Workbench, DBeaver).
2.  Crie um novo esquema/database:
    ```sql
    CREATE DATABASE nome_do_projeto;
    USE nome_do_projeto;
    ```
3.  Abra o arquivo `.sql` desejado (presente na pasta `03_Scripts_SQL`).
4.  Execute o script para criar as tabelas e popular os dados.

---

---
*Este repositório compõe o portfólio acadêmico para a disciplina de Design Profissional (Avaliação A1).*
