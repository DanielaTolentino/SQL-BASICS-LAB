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

