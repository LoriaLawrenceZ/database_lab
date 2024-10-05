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
SELECT * FROM <table>;
```
>concatenação `||`
```SGBD
SELECT <column> || <column> FROM <table>;
``` 

```SGBD
SELECT <column> || <column> as <alias> FROM <table> ORDER BY <alias>;
```

```SGBD
SELECT <column> || <column> as <alias> FROM <table> ORDER BY <alias> DESC;
```

```SGBD
SELECT DISTINCT <column> || <column> as <alias> FROM <table> ORDER BY <alias> DESC;
```

```SGBD
SELECT <column> || <column> as <alias> FROM <table> ORDER BY <alias> DESC GROUP BY <alias>;
```

```SGBD
SELECT <column> || <column> as <alias> FROM <table> WHERE <column> = <value> ORDER BY <alias> DESC GROUP BY <column>;
```

```SGBD
SELECT <column> || <column> as <alias> FROM <table> ORDER BY <alias> DESC GROUP BY <alias> HAVING <alias> = <value>;
```

```SGBD
SELECT * FROM <table> WHERE <column> = 1 OR <column> = 2 OR <column> = 3 OR <column> = 4 OR <column> = 5;
```

```SGBD
SELECT * FROM <table> WHERE <column> IN (1, 2, 3, 4, 5);
```

```SGBD
SELECT * FROM <table> WHERE <column> BETWEEN 1 AND 5;
```

```SGBD
SELECT * FROM <table> WHERE <column> LIKE '%TeStE%';
```

```SGBD
SELECT * FROM <table> WHERE <column> ILIKE '%tEsTe%';
```

```SGBD
SELECT * FROM <table> WHERE <column> LIKE 'T__TE%';
```

```SGBD
SELECT * FROM <table> WHERE <column> ILIKE '%$%%' ESCAPE '$';
```

```SGBD
CREATE DATABASE <database_2> WITH TEMPLATE <database_1>;
```
