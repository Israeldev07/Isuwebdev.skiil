name: "isu"
description: "Skill especializada en arquitectura frontend premium con Next.js (React) para interfaces estaticas y un backend robusto en NestJS con PostgreSQL tolerante a fallos." 

# Isu Endo: Frontend Estructurado & Datos Robustos

## 1. FRONTEND: Enfoque Limpio, Estático y Accesible

### Stack Tecnológico
* **Framework:** Next.js (Configurado con Server-Side Rendering para optimización SEO).
* **Lenguaje:** TypeScript (Configuración estricta, `noImplicitAny: true` mandatorio).

### Principios de Diseño (Estilo Kenji Endo)
1. **Paleta de Colores**:
   * Fondo: Negro puro (`#000000`) o gris asfalto oscuro (`#0a0a0a`).
   * Texto: Blanco puro (`#ffffff`) para contenido principal y gris (`#888888`) para jerarquía secundaria.
   * Acento cromático: Un solo color quirúrgico (ej. `#ff0033` o `#00ffcc`) aplicado exclusivamente a estados *hover* y elementos interactivos clave.

2. **Tipografía**:
   * Fuentes Sans-Serif de alto impacto con *letter-spacing* generoso en títulos.
   * Contraste extremo: Encabezados monumentales de peso ligero y textos informativos pequeños pero de alta legibilidad.
   * Uso de `text-transform: uppercase` estricto en menús, etiquetas y botones.

3. **Interactividad y Animación**:
   * Transiciones cinéticas utilizando **GSAP** con curvas de aceleración `power3.out` o `expo.out`.
   * Efectos de revelado de texto mediante contenedores con `overflow: hidden`.
   * Implementación de cursor personalizado interactivo con retraso orgánico (*smooth lagging*).



## 2. BACKEND Y BASE DE DATOS: Estructura Robusta

### Stack Tecnológico
* **Runtime/Framework:** Node.js con NestJS.
* **Base de Datos Principal:** PostgreSQL.

### Arquitectura de Datos
* **Normalización:** Estricta hasta Tercera Forma Normal (3NF) para asegurar la integridad referencial.
* **Estrategia de Índices:** Indexación optimizada mediante estructuras B-Tree para búsquedas frecuentes y GiST para datos complejos.
* **Alta Disponibilidad:** Configuración de arquitectura de replicación Física (Master-Slave) con Read Replicas dedicadas.
* **Transacciones:** Cumplimiento estricto de propiedades ACID en operaciones críticas de inventario y pasarelas de pago.
* **Migraciones:** Control de versiones de base de datos obligatorio gestionado mediante Prisma Migrations.



## 3. DIRECTRICES DE CALIDAD DE CÓDIGO (Reglas de Ejecución)

### Estructura HTML y Semántica
* Prohibido el uso de layouts sobrecargados de `div`. Es obligatorio el uso de etiquetas semánticas (`<main>`, `<section>`, `<nav>`, `<canvas>`).
* Diseño de secciones de pantalla completa (`100vh`) donde cada bloque actúe como una pieza independiente.

### Estilos y Renderizado 3D
* Ocultar el cursor nativo (`cursor: none`) únicamente cuando el componente del cursor personalizado esté activo y montado en el DOM.
* Para efectos de distorsión avanzada, grano de película (*noise*) o aberración cromática, inyectar un *boilerplate* limpio de **Three.js** utilizando shaders de fragmentos personalizados.

### Protocolo de Pruebas y Validación
* **Frontend:** Pruebas unitarias enfocadas exclusivamente en la fidelidad del renderizado de datos y manejo de estados (no validar transiciones visuales ni animaciones).
* **Base de Datos:** Ejecución obligatoria de pruebas de estrés (Load Testing) y optimización de consultas (*Query Explain*) antes del despliegue a producción. 
