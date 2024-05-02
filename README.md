# TP1-ProgDist2

# Instrucciones Trabajo práctico inicial

- Primero hay que abrir la consola y situarse en el directorio

```bash
cd .\TP1-ProgDist2\Tp1ApiGateway\
```

- Una vez situados correr el docker compose

```bash
docker compose up
```

- Para probar el proyecto importar la coleccion de Postman.
Es importante primero ejecutar el endpoint de login, para realizar las pruebas iniciales loguear con el siguiente usuario y contraseña.

```bash
{
  "username": "admin",
  "password": "admin"
}
```
- Una vez ejecutado esto se generara el token que debe de ser utilizado en las request a la app de usuarios.
- Se puede guardar el Token obtenido en la variable en postman Token(principal sugerencia) o agregarlo directamente en cada pedido en la seccion de "Bearer Token" en la parte de Authorization

- Una vez realizadas todas las consultas presionando ctrl+C en la misma consola paramos el servicio, o desde otra consola en el mismo directorio lo damos de baja con :

```bash
docker compose down
```
