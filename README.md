# postgresRandomHash
A postgres function for creating a random, base64 string

## Usage

```sql
 <column name> VARCHAR(32) NOT NULL default f_random_text(32) UNIQUE
```
