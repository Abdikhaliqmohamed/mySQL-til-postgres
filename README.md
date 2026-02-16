# Preface 

projektet omhandler migrerings af enterprice data fra mySQL til Prostgres

Verktøjer som vil blive anvendt:

- Jupyter notebook
- Postegres
- MySQL


# Sudo code

## High level
1. Audit data in MySQL server
2. Udtræk data fra serveren
3. Transformere dataen
4. Load data i Postgres
5. Validere data
6. Generer en validererings rapport

## Low level

- Oprette en .env fil
- load miljø filerne
- forbinde VS code med mySQl via OBDC
- Forbind til Postgres via psycopg2
- Audit data
- For each data (loops)
- Find række tal (i sql)
- Udtræk alle rækker
- transformer data til lowercase
- konvertere datatyper
- Opret tabeller i Postgres
- Load tabellerne
- Kør efter-data migrations tjek 
- Generere en validerings rapport