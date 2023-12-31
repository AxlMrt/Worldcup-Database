# FreeCodeCamp World Cup Challenge Solution
The submission for freecodecamp's worldcup database automated population and retrieval using bash scripts

## What is the challenge?
Creating the required databases `teams`, `games` and populate the content of both using a bash script `insert_data.sh` that pipelines the contents of a csv file, and the `psql` PostgreSql CLI utility. Afterwards, query the database using the same utility i na different bash script `queries.sh`

## The submission requirements
- Creating `worldcup`, and two tables `games`, `teams` DB within a terminal session using psql
- Pipeline the contents of `games.csv` into respective tables, while avoiding redundant insertions, and getting foreign keys for teams, which is implemented in `insert_data.sh`
- After populating the database, retrieve data according to specs defined within the comments in `queries.sh` using PostgresSQL queries

## Contents of the Repo
- the resulting DB contents dumped in `worldcup.sql` using `pg_dump` CLI utility
- bash scripts used for population and insertion `insert_data.sh` and `queries.sh`
