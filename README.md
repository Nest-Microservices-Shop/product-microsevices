<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

[circleci-image]: https://img.shields.io/circleci/build/github/nestjs/nest/master?token=abc123def456
[circleci-url]: https://circleci.com/gh/nestjs/nest

# Product Microservice

[![My Skills](https://skillicons.dev/icons?i=prisma,git,nestjs,sqlite,ts,yarn)](https://skillicons.dev)

## Dev

1.  Clonar el repositorio
2.  Instalar dependencias
3.  Crear un archivo `.env` basdo en el `env.template`
4.  Ejecutar migracion de prisma `npx prisma migrate dev`
5.  Levantar el servidor de nats

```pwsh

docker run -d --name nats-server -p 4222:4222 -p 8222:8222 nats

```

6.  Ejecutar `yarn start:dev`
