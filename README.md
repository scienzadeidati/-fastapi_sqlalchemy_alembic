# fastapi_sqlalchemy_alembic

Questo repository viene utilizzato come parte di un tutorial per mostrare come utilizzare Fastapi e pydantic con Sqlalchemy, postgresql, Alembic (per le migrazioni).

L'articolo completo è pubblicato sul sito [here](https://scienzadeidati.com/blog/fastapi-con-sqlalchemy-postgresql-e-alembic-e-ovviamente-docker-parte-1/)

## Come compilare

    docker-compose build

## Come eseguire

    docker-compose up

e collegarsi a:

    http://localhost:8000

## Documentazione

    swagger - http://localhost:8000/docs
    redoc - http://localhost:8000/redoc

## Pgadmin4

    http://localhost:5050