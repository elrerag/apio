# Aplicación de interfaz original - APIO

Este recurso se realiza gracias al servicio disponible en [https://my-json-server.typicode.com/](https://my-json-server.typicode.com/). 

## Crear un servidor propio

Se debe crear un repositorio en gitHub y dentro de este, debe existir el archivo `db.json`, dentro de este hacemos lo siguiente:

```javascript
{
    "usuarios" : [
        {/*usuario 1*/},
        {/*usuario 2*/}
    ],
    "otros" : [
        /*otros...*/
    ]
}
```

De esta forma tendremos un API de pruebas personal en la dirección:

```
https://my-json-server.typicode.com/<tuUsuarioGitHub>/<tuProyecto>
```
y los end points serán `/usuarios` y `/otros`

```
https://my-json-server.typicode.com/<tuUsuarioGitHub>/<tuProyecto>/usuarios
https://my-json-server.typicode.com/<tuUsuarioGitHub>/<tuProyecto>/otros
```