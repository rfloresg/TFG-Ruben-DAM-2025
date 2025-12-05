# DropBid – TFG DAM 2025

Proyecto Final de Grado de **Desarrollo de Aplicaciones Multiplataforma (DAM)**.

- **Alumno:** Rubén Flores Garrote  
- **Centro:** IES La Vereda  
- **Curso:** 2º DAM (2024–2025)  

## Idea del proyecto

DropBid es una aplicación móvil de compraventa de productos de segunda mano que combina el modelo tipo Wallapop con un sistema de **subasta holandesa**:

- El vendedor publica un producto con un **precio inicial alto**.
- Con el tiempo, el precio va **bajando automáticamente** hasta llegar a un **precio mínimo**.
- El **primer usuario** que decide comprar al precio actual se queda el producto.

En versiones futuras también se valorará un modo con **participaciones/papeletas** y sorteo entre los compradores.

## Tecnologías previstas

- **App móvil (frontend):** Android (Java)
- **Backend (API REST):** Spring Boot (Java)
- **Base de datos:** MySQL / MariaDB
- **Autenticación:** JWT + contraseñas cifradas (BCrypt)
- **Control de versiones:** Git + GitHub

## Estructura del repositorio

```text
TFG-Ruben-DAM-2025
├── Documentacion/
│   ├── Anteproyecto.md
│   ├── Diario_de_trabajo.md
│   └── (Memoria_TFG.docx más adelante)
├── Codigo/
│   ├── Backend/
│   ├── Frontend/
│   └── Base_de_datos/
├── Recursos/
│   ├── Imagenes/
│   └── Diagramas/
└── README.md
