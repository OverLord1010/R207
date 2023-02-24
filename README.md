# R207
SQL Learning

# Utilisation de sqlite :

sqlite3 sujet.sqlite

.read magasin_sqlite.sql
.quit

# Requête de base en SQL:

select * from X where numprod in (select numprod from Y where Z)

# Pour rendre les résultats plus lisibles :

.mode column
.headers on

# Pour consulter les tables :

.tables
