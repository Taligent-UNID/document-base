# Proyecto Base-Documental Documentación
Repositorio de web estatica para documentación de la base documental.

## Resumen

El proyecto de web estatica para documentación de la base documental, se centra en propocionar una guia completa de una base documental y como trabajar con ella, de una forma practica y flexible. El sitio web estatico esta publicado en GitHub Pages, dando la visibilidad a todo la organización.
## MkDocs

Se utiliza el framework de [MkDocs](https://squidfunk.github.io/mkdocs-material/) para crear la web estatica del proyecto. El cual tiene dos tipos de entornos.

## Enviroment Dev
Para el entorno de desarrollo se crea de forma local con la Imagen de docker de [MkDocs-Docker](https://hub.docker.com/layers/squidfunk/mkdocs-material/8.2.7/images/sha256-63b7eefc788ee83928a75d32f10493a347e63a00d569d26ed0ebf98df9c44f63), la ultima versión hasta el momento es 8.2.7.
Se utiliza [docker-compose](docker-compose.yaml) para crear el contenedor de nombre **document-base**:

`docker-compose up -d`

Se puede acceder a "http://localhost:8000" y visualizar la web estatica.
>[!WARNING] Previamente se debe tener instalado [Docker Desktop](https://www.docker.com/products/docker-desktop/)

## Enviroment Prod
Para el entorno productivo se debe realizar una rama *dev* y trabajar en ella para luego realizar el correspondiente PR (Pull Request), disparando la GitHub Actions de [mkdocs-to-gh-pages](.github/workflows/mkdocs-ghpages.yaml), al recibir un PR (Pull Request), compila el proyecto de MkDocs y genera un commit a la rama [gh-pages](https://github.com/Taligent-UNID/document-base/tree/gh-pages), la cual realiza un workflow de despliegue en **GH-PAGES**, publicando el sitio en la siguiente url:

- https://taligent-unid.github.io/document-base/
