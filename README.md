# Proyecto Base-Documental Documentación
Repositorio de documentación de la base documental.

## Resumen

El proyecto de documentacion de la base documental, se centra en propocionar una guia completa de una base documental y como trabajar con ella, esta misma se crea un sitio web estatico para ser publicado en GitHub Pages, dando visibilidad a todo la organización.
## MkDocs

Se utiliza el framework de [MkDocs](https://squidfunk.github.io/mkdocs-material/) para crear el sitio estatico del proyecto. El cual tiene dos tipos de entornos.

## Enviroments Dev
Para el entorno de desarrollo se crea de forma local con la Imagen de docker de [MkDocs-Docker](https://hub.docker.com/layers/squidfunk/mkdocs-material/8.2.7/images/sha256-63b7eefc788ee83928a75d32f10493a347e63a00d569d26ed0ebf98df9c44f63), la ultima versión hasta el momento es 8.2.7.
Se utiliza [docker-compose](docker-compose.yaml) para crear el contenedor de nombre **document-base** y se puede acceder en la siguiente dirección "http://localhost:8000"

