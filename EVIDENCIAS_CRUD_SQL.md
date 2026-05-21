# Evidências - INSERT, UPDATE e DELETE no banco db_em

## Identificação

Nome: Ana Clara  
Turma: 3A  
Data: 21/05/2026

---

# 1. SELECT final - Leituras do dia 2026-04-04

```sql
SELECT *
FROM leituras
WHERE timestamp >= '2026-04-04'
AND timestamp < '2026-04-05'
ORDER BY timestamp ASC;
13 | EM-ARACATUBA-01 | 2026-04-04 08:00:00 | 23.4 | 76.2
14 | EM-ARACATUBA-01 | 2026-04-04 09:00:00 | 25.2 | 72.0
15 | EM-ARACATUBA-01 | 2026-04-04 10:00:00 | 25.9 | 70.5