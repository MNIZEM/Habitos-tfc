# Propuesta inicial del proyecto

## 1. Título del proyecto

**Habitos** — Aplicación de seguimiento de hábitos y rutinas personales

## 2. Descripción y contexto

Muchas personas quieren adoptar hábitos saludables (beber agua, hacer ejercicio,
leer, meditar...) pero les cuesta mantener la constancia por falta de seguimiento
visual de su progreso. Habitos busca resolver esto ofreciendo una herramienta
sencilla donde el usuario registra sus hábitos diarios y visualiza su evolución
mediante estadísticas y rachas, para motivar la constancia.

## 3. Objetivo general

Desarrollar una aplicación multiplataforma que permita a los usuarios crear,
seguir y analizar sus hábitos diarios, con el fin de fomentar la constancia
mediante estadísticas de progreso y elementos de entretenimiento.

## 4. Objetivos específicos

1. Diseñar y modelar una base de datos relacional que soporte usuarios,
   hábitos, registros diarios, rachas y estadísticas.
2. Desarrollar una API REST que exponga toda la lógica de negocio
   (autenticación, CRUD de hábitos, registro de cumplimiento, cálculo de
   estadísticas).
3. Implementar una aplicación cliente (móvil y/o web) con una interfaz
   intuitiva pensada para el uso diario rápido.
4. Implementar un sistema de autenticación y gestión de usuarios (registro,
   login, recuperación de contraseña).
5. Diseñar un sistema de notificaciones que refuercen el cumplimiento de los hábitos.
6. Desarrollar un módulo de estadísticas visuales (rachas, % de cumplimiento, heatmap, gráficas de evolución).
7. Incorporar elementos de gamificación (logros, niveles, puntos) para
   mejorar la motivación del usuario.
8. Aplicar buenas prácticas de desarrollo de software: control de versiones,
   testing, documentación técnica y metodología de trabajo.

## 5. Alcance del proyecto

### Incluye
- Gestión de hábitos personalizados (crear, editar, eliminar).
- Registro diario de cumplimiento.
- Estadísticas y gráficas de progreso.
- Sistema de notificaciones.
- Autenticación y gestión de usuarios.
- Elementos básicos de gamificación (rachas, logros, niveles...).

### No incluye (de momento)
- Funciones sociales (compartir progreso con amigos, rankings públicos).
- Integración con wearables (Fitbit, Apple Watch, etc.).
- Versión offline completa.


## 6. Propuesta de tecnologías
- Backend: Spring Boot
- Base de datos: PostrgreSQL
- Frontend: Flutter/Angular
- Autenticacion: JWT
- Control de versiones: Git + GitHub

## 7. Autor/a
Martin Ansia Canton - 2DAM - IES San Mamede