---
title: "Agenda básica CLI con Python"
version: "0.1"
fecha: "29/04/2026"
---

# spec.md - Especificación funcional #
## 1.Descripción general.
La aplicación es una herramienta de línea de comandos (CLI) escrita en lenguaje Python que permite gestionar una agenda de contactos almacenada en una base de datos MYSQL
ofreciendo operaciones propias de CRUD.

## 2.Funcionalidades
- Crear,listar,actualizar y eliminar contactos.
- Buscar contactor por nombre, por telefono y por email
- Listar todos los contactos
- Crear un menú de opciones
- CLI sea interactiva
- Almacene información en una base de datos MySQL.

##  3.Modelo de datos
Tabla contacto en base de datos MySQL
| Campo | Tipo | Obligatorio | Descripcion |
|-------|------|-------------|-------------|
| id | INT auto_incremental | Yes | Identificador único |
| name | varchar(100) | Yes | Nombre del contacto |
| surname | varchar(200) | Yes | Apellidos contacto |
| tel1 | int | Yes | telefono contacto1 |
| tel2 | int | No | telefono contacto2 |
| email | varchar(100) | No | Email contacto |
| notes | TEXT |  No | Informacion contacto |

## 4. Casos de uso
### CU-01: Añadir contacto
### CU-02: Ver contacto
### CU-03: Eliminar contacto
### CU-04: Modificar contacto
### CU-05: Listar contactos
