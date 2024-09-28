# database_lab
Repository for database study through VR Software

---

- DDL (Data Definition Language)   -> Alteração Estrutural
- DQL (Data Query Language)        -> Consulta de Dados (**select**)
- DML (Data Manipulation Language) -> Alteração de Dados (**insert**, **update**, **delete**)
- DTL (Data Transaction Language)  -> Gerenciamento de Transação (**begin**, **commit**, **rollback**)
- DCL (Data Control Language)      -> Controle de Acesso (**grant**, **revoke**)

---

# Terminal

>**psql** | Acessar o banco de dados no terminal

\h - help
\h SELECT - help do comando SELECT

---

# DQL

```SGBD
SELECT * FROM <tabela>;
```

```SGBD
SELECT <campo> || <campo> FROM <tabela>;
``` 

```SGBD
SELECT <campo> || <campo> as <alias> FROM <tabela> ORDER BY <alias>;
```

```SGBD
SELECT <campo> || <campo> as <alias> FROM <tabela> ORDER BY <alias> DESC;
``` 
