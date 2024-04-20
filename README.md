# Orders MicroService

## Client Gateway

1. Clonar repositorio
2. Instalar dependencias `npm install`
3. Crear un archivo `.env` basado en el `env.template`
   Levantar servidor NATS
   ```
docker run -d --name nats-main -p 4222:4222 -p 6222:6222 -p 8222:8222 nats
```
4. Levantar los servicios que se van a consumir.
5. Ejecutar `npm run start:dev`


## Nats
```
docker run -d --name nats-main -p 4222:4222 -p 6222:6222 -p 8222:8222 nats
```