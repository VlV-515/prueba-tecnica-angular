# 📝 Prueba Técnica - Lista de Usuarios con API y Detalles

## 🎯 Objetivo

Crear una aplicación en Angular que consulte información de una API pública, liste los resultados en una tabla y muestre los detalles de un usuario seleccionado. Diseño simple pero funcional, se puede hacer uso de Angular Material o Bootstrap o Tailwind o Código Vanilla.

---

## ⏳ Duración

**45 minutos**

---

## 📌 Requisitos

## 1. Página de Bienvenida

Crear una página que muestre de forma centrada:

- El nombre del desarrollador (tu nombre).
- Un **botón** que al hacer clic lleve al listado de usuarios.

## 2. Página de Listado de Usuarios

Esta página deberá:

- **Consumir la API de:** `https://jsonplaceholder.typicode.com/users`.
- **Listar los usuarios en una tabla**, mostrando al menos la siguiente información (obtenida de la respuesta de la API):
    - ID (`id`)
    - Nombre (`name`)
    - Correo electrónico (`email`)
    - Ciudad (`address.city`)
    - Un **botón** con el texto "Ver Detalles" por cada usuario.
- *(Opcional)* Se recomienda incluir un indicador visual mientras se cargan los datos de la API.

## 3. Página de Detalles del Usuario

Al hacer clic en el botón "Ver Detalles" de un usuario en la lista, la aplicación deberá navegar a una nueva página que muestre **la información completa del usuario obtenido de la API** (o los campos que consideres relevantes).

En la página de **Detalles**, debe haber un botón que permita volver a la página con la lista de usuarios.

---

## **Consideraciones:**

* Se valorará la organización del código, la claridad en la implementación y el manejo de posibles errores (aunque no sea un requisito estricto para esta prueba).

¡Mucho éxito!
