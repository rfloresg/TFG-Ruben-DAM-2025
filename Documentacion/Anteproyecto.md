```markdown
# Anteproyecto – DropBid

## 1. Datos del alumno

- Alumno: **Rubén Flores Garrote**  
- Ciclo Formativo: **Desarrollo de Aplicaciones Multiplataforma (DAM)**  
- Curso: **2º**  
- Centro: **IES La Vereda**  

## 2. Título del proyecto

**DropBid – Aplicación móvil de compraventa con subasta holandesa**

## 3. Descripción de la idea

La idea del proyecto es crear una aplicación móvil de compraventa que funcione de forma similar a Wallapop, pero con una diferencia importante: el sistema de **subasta holandesa**.

En este tipo de subastas:

- El vendedor establece un **precio inicial alto**.
- Con el paso del tiempo, el precio va **bajando automáticamente** hasta alcanzar un **precio mínimo configurado**.
- El **primer usuario** que decide comprar el producto al precio actual se lo queda.

Este modelo obliga a los usuarios a **decidir cuándo comprar**: si esperan demasiado, se arriesgan a que otra persona se adelante; si compran demasiado pronto, pagan un precio más alto.

Como posible mejora futura, se plantea un segundo modo de venta basado en **participaciones o papeletas**:

- El producto se divide en un número de participaciones.
- Por ejemplo, unas zapatillas de 100 € podrían ofrecerse a 150 €, divididas en 15 participaciones de 10 €.
- Cada usuario puede comprar una o varias participaciones.
- Cuando se venden todas, se realiza un **sorteo** (p. ej. con una ruleta virtual) y el ganador se lleva el producto.

Este sistema añade un componente de **gamificación** y puede atraer a un público diferente.

## 4. Objetivos del proyecto

- Desarrollar una **aplicación móvil Android** funcional para compraventa.
- Implementar una **API REST** con Spring Boot que gestione usuarios, productos y subastas.
- Diseñar y gestionar una **base de datos** relacional (MySQL/MariaDB).
- Implementar un sistema de **autenticación segura** con contraseñas cifradas y tokens JWT.
- Crear la lógica de la **subasta holandesa**, calculando el precio en función del tiempo.
- Permitir la **compra inmediata** de productos y el registro de pedidos.
- Implementar un sistema básico de **chat** entre comprador y vendedor.
- Documentar todo el proceso (análisis, diseño, implementación y pruebas) en la memoria del TFG.

## 5. Aspectos técnicos

- **Aplicación móvil:**
  - Plataforma: Android
  - Lenguaje: Java
  - Interfaz construida con actividades, fragments y vistas clásicas (XML).

- **Backend:**
  - Framework: Spring Boot
  - Estilo: API REST
  - Gestión de seguridad y autenticación con JWT

- **Base de datos:**
  - Motor: MySQL o MariaDB
  - Tablas para usuarios, productos, subastas, pedidos y mensajes de chat.

- **Autenticación y seguridad:**
  - Registro e inicio de sesión de usuarios.
  - Contraseñas cifradas (BCrypt).
  - Tokens JWT para autenticar las peticiones.

## 6. Funcionalidades principales previstas

- Registro e inicio de sesión de usuarios.
- Publicación de productos:
  - Título, descripción, categoría, imágenes.
  - Precio inicial, precio mínimo y duración de la subasta.
- Algoritmo de **subasta holandesa**:
  - El precio baja automáticamente según el tiempo configurado.
- Lista de subastas activas y detalle de cada producto.
- Compra inmediata por parte del primer interesado.
- Historial de subastas activas y finalizadas.
- Chat básico entre comprador y vendedor.
- **Funcionalidad futura opcional**:
  - Venta mediante participaciones y sorteo aleatorio.
  - Visualización del sorteo de forma interactiva (ruleta u otro sistema).

## 7. Metodología de trabajo

Se utilizará una metodología **ágil** con pequeñas iteraciones:

1. Análisis y diseño básico.
2. Implementación del backend (API REST, base de datos, seguridad).
3. Implementación de la app Android (pantallas, conexión con la API).
4. Pruebas y ajustes.
5. Documentación final y preparación de la defensa.

## 8. Planificación aproximada

- **Noviembre–Diciembre**: Análisis, diseño, modelo de datos y estructura del proyecto.
- **Enero–Marzo**: Desarrollo del backend y de la app Android.
- **Abril**: Pruebas, pulido y mejoras.
- **Mayo**: Redacción de la memoria final y preparación de la presentación.