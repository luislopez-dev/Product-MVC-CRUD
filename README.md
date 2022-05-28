# Aplicación web Productos

## Tabla de contenidos

* [Introducción](#introducción)
* [Tecnologías](#tecnologías)
* [Variables de entorno](#variables-de-entorno)
* [Ejecución](#ejecución)
* [Páginas](#páginas)
* [Licencia](#licencia)

## Introducción

El siguiente proyecto es una aplicación web de productos utilizando la arquitectura Modelo Vista Controlador.
Segundo proyecto del Bootcamp React / Ruby on Rails. 

## Tecnologías

* ruby 2.7.0
* Rails 6.1.5
* pg (postgres) 1.1
* Bootstrap 5

## Variables de entorno

1. `DB_NAME:` Nombre de la base de datos
2. `DB_USERNAME:` Nombre de usuario de la base de datos
3. `DB_PASSWORD:` Contraseña de la base de datos
4. `DB_HOST:` Host de la base de datos 

## Ejecución:

1. Clone el repositorio
2. Diríjase a la carpeta raíz del proyecto e instale las dependencias a través del siguiente comando:  `bundle install`
3. Cree las variables de entorno en un archivo llamado `application.yml` en la carpeta `Config`
4. Ejecute las migraciones del proyecto usando el siguiente comando: `Rails db:migrate`
5. Ejecute el proyecto usando el siguiente comando: `Rails server` o `Rails s`

## Páginas:

#### URL: `/products`
* Descripción: Lista todos los productos guardados en la base de datos.
![alt text](https://i.imgur.com/jBFjhPM.png)

#### URL: `/products/id`
* Descripción: Muestra información de un producto en específico basándose en su identificador.
![alt text](https://i.imgur.com/bDImVRK.png)

#### URL: `/products/id/edit`
* Descripción: Edita un producto.
![alt text](https://i.imgur.com/g9vFJhO.png)

#### URL: `/products/new`
* Descripción: Crea un producto.
![alt text](https://i.imgur.com/qYCoR2f.png)

#### Licencia
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
* Licencia MIT