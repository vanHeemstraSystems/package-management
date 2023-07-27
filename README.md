[![Quarto Publish](https://github.com/vanHeemstraSystems/customer-relationship-management/actions/workflows/publish.yml/badge.svg)](https://github.com/vanHeemstraSystems/customer-relationship-management/actions/workflows/publish.yml)

customer-relationship-management
# Customer Relationship Management

Can be read as "Customer Relationship Management" at https://app.gitbook.com/s/Rs3XPuVclvoj92Exb9AA/

Can be browsed as "Customer Relationship" at https://vanheemstrasystems.github.io/customer-relationship-management/

Documentation of this repository is automatically done with Quarto using GitHub Actions as described at https://github.com/vanHeemstraSystems/quarto-to-github-pages/blob/main/300/300/README.md

Based on "How to Run PostgreSQL and pgAdmin Using Docker" at https://towardsdatascience.com/how-to-run-postgresql-and-pgadmin-using-docker-3a6a8ae918b5

Based on "Twenty" at [https://github.com/sissbruecker/linkding](https://github.com/twentyhq/twenty)

Create yarn.lock file as follows:

```
$ cd containers/app/main
$ yarn install
```

Run as follows:

```
$ cd containers/app
$ docker-compose --file docker-compose.dev.yml --project-name customer-relationship-management-dev up --build -d
```
