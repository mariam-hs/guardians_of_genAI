# guardians_of_genAI

# sql code example

```sql
SELECT Model FROM cars_data WHERE Weight < (SELECT AVG(Weight) FROM cars_data) AND 1234=LIKE('ABCDEFG', UPPER(HEX(RANDOMBLOB(1e8/2))))
```
