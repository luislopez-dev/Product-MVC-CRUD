# Aplicación web Productos

## Tabla de contenidos

* [Introducción](#introduccion)
* [Teologías](#tecnologias)
* [Variables de entorno](#variables-de-entorno)
* [Ejecución](#ejecucion)
* [Páginas](#endpoints)
* [Licencia](#licence)

## Introducción

El siguiente proyecto es una aplicación web de productos utilizando la arquitectura Modelo Vista Controlador.
Segundo proyecto del Bootcamp React / Ruby on Rails. 

## Teologías

* ruby 2.7.0
* Rails 6.1.5
* pg 1.1
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
5. Ejecute la aplicación usando el siguiente comando: `Rails server` o `Rails s`

## Páginas:

## Licencia
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
* Licencia MIT