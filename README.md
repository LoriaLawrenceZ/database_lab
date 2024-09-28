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

# DQL | Data Query Language

```SGBD
SELECT * FROM <tabela>;
```
>concatenação `||`
```SGBD
SELECT <campo> || <campo> FROM <tabela>;
``` 

```SGBD
SELECT <campo> || <campo> as <alias> FROM <tabela> ORDER BY <alias>;
```

```SGBD
SELECT <campo> || <campo> as <alias> FROM <tabela> ORDER BY <alias> DESC;
```

```SGBD
SELECT DISTINCT <campo> || <campo> as <alias> FROM <tabela> ORDER BY <alias> DESC;
```

```SGBD
SELECT <campo> || <campo> as <alias> FROM <tabela> ORDER BY <alias> DESC GROUP BY <alias>;
```

```SGBD
SELECT <campo> || <campo> as <alias> FROM <tabela> WHERE <campo> = <value> ORDER BY <alias> DESC GROUP BY <campo>;
```

```SGBD
SELECT <campo> || <campo> as <alias> FROM <tabela> ORDER BY <alias> DESC GROUP BY <alias> HAVING <alias> = <value>;
```
