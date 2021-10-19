# adonis-boilerplate

Boilerplate with the [adonis](https://adonisjs.com/) framework.

## Requires

- [Docker-compose](https://docs.docker.com/compose/install/)

## Installation

```
cp .env.example .env
docker-compose build
```

## Usage

Check your `.env` file to map ports to your containers.

```
docker-compose up -d
```

## Run Database Migrations

```
docker exec ${APP_CONTAINER_ID} node ace migration:run
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[BSD](https://opensource.org/licenses/BSD-3-Clause)