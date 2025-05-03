## Installation

```bash
$ npm install
$ npx prettier --write .
```

## Running the app

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

## Test

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```

## Nats

```bash
# Run server nats
$ docker run -d --name nats-main -p 4222:4222 -p 6222:6222 -p 8222:8222 nats
```

## PROD

Ejecutar
```
docker build -f dockerfile.prod -t client-gateway .
```

## License

Nest is [MIT licensed](LICENSE).
