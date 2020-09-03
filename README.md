# sql-source-jam
## To Run:

-  create a .env file using the example as a guide.
- docker-compose up.

## To migrate db:

Do not edit any existing scripts.  You must add subsequent scripts.
Use the existing ones as a guide with special comments.

## To run migrations only: 

docker-compose restart liquibase.

## To run on some other db:
alter .env file accordingly.


## To Run without compose
checkout migrate.sh for inspiration.


