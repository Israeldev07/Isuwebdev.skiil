# AI SKILL SPECIFICATION: kenji-endo-clean-frontend-robust-db

## Meta
* **Name:** Isu Endo: Frontend Estructurado & Datos Robustos
* **Version:** 2026.2.0
* **Description:** Skill optimizada para interfaces web japonesas limpias y estáticas, respaldadas por un backend con bases de datos relacionales de alta tolerancia a fallos.

---

## 1. FRONTEND: Enfoque Limpio, Estático y Accesible

### Framework
* React + TypeScript o Next.js (Server-Side Rendering para SEO e indexación en buscadores japoneses)

### Design Philosophy
* **Cero animaciones complejas:** Priorizar velocidad de carga y legibilidad absoluta.
* **Diseño denso en información:** Estilo UI clásico japonés, estructurado con layouts limpios y bordes definidos.
* **Internacionalización estricta:** Soporte nativo para cambio de idioma (Japonés / Inglés) sin romper cajas de texto.
* **Accesibilidad web:** Cumplimiento de pautas JIS X 8341 (estándar de accesibilidad japonés) y WCAG.

### Typography
* Uso correcto de fuentes sans-serif japonesas (Noto Sans JP, Meiryo) optimizadas para pantallas legibles de cualquier tamaño.
* Manejo impecable del espaciado de caracteres (kerning) para texto denso en Kanji e Kana.

---

## 2. BACKEND Y BASE DE DATOS: Estructura Robusta e Inquebrantable

### Primary DB
* PostgreSQL (Configuración relacional estricta)

### DB Architecture
* **Normalización práctica:** Flexible según necesidades del proyecto para garantizar la integridad referencial de la información corporativa.
* **Índices:** Uso de índices optimizados para consultas pesadas frecuentes (B-Tree, GiST).
* **Disponibilidad:** Estrategia de réplicas de lectura (Read Replicas) y Master-Slave para asegurar cero pérdida de datos en contingencias.
* **Transacciones:** Uso de transacciones ACID garantizadas para operaciones críticas (inventarios, pasarelas de pago locales).

### Backend Runtime
* Node.js (NestJS) o Go (Golang) para un manejo eficiente de hilos y conexiones concurrentes a la BD.

---

## 3. DIRECTRICES DE CALIDAD DE CÓDIGO

* El tipado en TypeScript debe ser **flexible**. Se permite una configuración estándar y el uso selectivo del tipo `any` cuando la velocidad de desarrollo o la integración con librerías externas lo requieran.
* Migraciones de base de datos controladas por versiones (con herramientas como Liquibase o Knex/Prisma migrations).
* Pruebas unitarias de frontend enfocadas en renderizado de datos correctos, no en transiciones visuales.
* Pruebas de estrés y rendimiento de queries en la base de datos antes de pasar a producción.

---
*END OF SKILL*
