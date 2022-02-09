# Template para proyectos con Node y Handlebars

## Instalación

Para poder utilizar este template, es necesario que se descargue o se realice un `git clone`.

Una vez hecho esto, realizar instalación de dependencias.

```shell
$ npm install 
```

Posteriormente, crear un archivo `.env` con las siguientes propiedades:

```env
# ESTABLECER EL PUERTO
PORT= 

# ESTABLECER LA BASE DE DATOS
MONGODB_URI=

# ESTABLECER LA PALABRA SECRETA PARA LAS COOKIES
SECRET=

```

Puedes revisar como ejemplo el archivo `.env.example` con las propiedades.

## Consideraciones

- Si el despliegue sucede en un Cloud Environment (a.k.a. Heroku), vale la pena revisar tu sección de `config vars`.



## Créditos

Para cualquier inquietud, contáctame [m@nieva.team](mailto:m@nieva.team) o a mi twitter [@mikenieva](https://twitter.com/mikenieva)
