# SQL-BASICS-LAB
Simplicidade e pratica

# 📘 SQL Basics

Este repositório contém exemplos práticos de **comandos básicos em SQL**, ideal para iniciantes que desejam aprender e praticar a linguagem de consulta estruturada.

## 🛠️ Tecnologias
- SQL (Structured Query Language)
- Banco de dados de exemplo (SQLite / MySQL / PostgreSQL)

## 📂 Conteúdo
- **CREATE** → criação de tabelas e bancos de dados  
- **INSERT** → inserção de registros  
- **SELECT** → consultas simples e com filtros  
- **UPDATE** → atualização de dados  
- **DELETE** → remoção de registros  
- **JOIN** → junção entre tabelas (introdução)  

## 🚀 Exemplos

### Criando uma tabela
```sql
CREATE TABLE Clientes (
    id INT PRIMARY KEY,
    nome VARCHAR(100),
    email VARCHAR(100),
    cidade VARCHAR(50)
);

Inserindo registros
INSERT INTO Clientes (id, nome, email, cidade)
VALUES (1, 'Ana Silva', 'ana@email.com', 'São Paulo');

Consultando dados
SELECT nome, cidade
FROM Clientes
WHERE cidade = 'São Paulo';

Atualizando registros
UPDATE Clientes
SET cidade = 'Rio de Janeiro'
WHERE id = 1;

Deletando registros
DELETE FROM Clientes
WHERE id = 1;

🎯 Objetivo

Este projeto tem como finalidade praticar os principais comandos SQL e servir de material de consulta rápida para iniciantes.

📌 Como usar

Clone este repositório

git clone https://github.com/seu-usuario/sql-basics.git


Abra em seu SGBD (MySQL, PostgreSQL, SQLite etc.)

Execute os scripts SQL na ordem desejada

