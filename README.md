### cockroach
---
https://github.com/cockroachdb/cockroach

```
cockroach start --insecure --listen-addr=localhost

cockroach start \
--insecure \
--store=node2 \
--listen-addr=localhost:26258 \
--http-addr=localhost:8081 \
--join=localhost:26257
```

```sql
CREATE DATABASE bank;
CREATE TABLE bank.accounts (id INT PRIMARY KEY, balance DECIMAL);
INSERT INTO bank.accounts VALUES (1, 1000.50);
SELECT * FROM bank.accounts;

SELECT * FROM bank.accounts;
SELECT * FROM bank.accounts;


```

```
```


