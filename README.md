# MICROSERVICIO DE TRADUCCIÓN DE TEXTO

## ÍNDICE

1. [DESCRIPTION](#1-description)
2. [TECNOLOGÍAS UTILIZADAS](#2-tecnologías-utilizadas)
3. [ESTILO DE ARQUITECTURA](#3-estilo-de-arquitectura)
4. [PATRÓN DE ARQUITECTURA](#4-patrón-de-arquitectura)
5. [ESTRUCTURA DEL PROYECTO](#5-estructura-del-proyecto)
6. [BASE DE DATOS](#6-base-de-datos)
7. [COMO LEVANTAR EL PROYECTO](#7-como-levantar-el-proyecto)
8. [COMO CONSTRUIR LA IMAGEN](#8-como-construir-la-imagen-)
9. [COMO LEVANTAR LA IMAGEN CON DOCKER COMPOSE](#9-como-levantar-la-imagen-con-docker-compose)
10. [DOCUMENTATION](#10-documentation)
11. [VARIABLES DE ENTORNO .ENV](#11-variables-de-entorno-env)

## 1. DESCRIPTION

Este es un microservicio de traducción de texto, diseñado como ejemplo de aplicación de la **arquitectura hexagonal**.


## 2. TECNOLOGÍAS UTILIZADAS

    - Spring boot 3.4.5
    - Java 17
    - Maven 3.9.9

## 3. ESTILO DE ARQUITECTURA

- Microservicios

## 4. PATRÓN DE ARQUITECTURA

- Hexagonal

## 5. ESTRUCTURA DEL PROYECTO

- Infraestructure
- Applications
- Domain

## 6. BASE DE DATOS

- MySql

## 7. COMO LEVANTAR EL PROYECTO

Terminal
- Si tienes instalado Maven en tu máquina: 

```shell
> mvn spring-boot:run
```
- Si no tienes instalado Maven usa el wrapper: 

```shell
./mvnm spring-boot:run
```

## 8. COMO CONSTRUIR LA IMAGEN 

```shell
  docker build -t translator-latest .
```

## 9. COMO LEVANTAR LA IMAGEN CON DOCKER COMPOSE

Agregar detalles...

## 10. DOCUMENTATION

Se usará SWAGGER para documentar la Api Rest, aquí irá la url de tu documentación, por ejemplo: https//localhost:<port>/swager...

## 11. VARIABLES DE ENTORNO .ENV

Agregar detalles aquí si tu API REST depende de .env



