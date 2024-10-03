# Dockerized Postgres Avanti

Basic boiler plate for running a containerized [Avanti Framework](https://adiantiframework.com.br/home) instance, using [phpdocker.io](https://phpdocker.io/) for easier containerization


## Building it

```bash
docker-compose pull
docker-compose up --build
```

## Acessing it:
The project uses `http://localhost/template` for browser connections, it can be change through `app/config/application.ini`, for more information see [Avanti Framework quick guide](https://adiantiframework.com.br/guia-rapido)