# CloudSolutions SpA — Servicios Tecnológicos & Infraestructura Cloud

badges: Location: Iquique, Chile | Architecture: Modular Monolith | Database: PostgreSQL 18.0+ | Backend: ASP.NET Core / .NET | Containers: Docker

---

### Sobre CloudSolutions SpA

**CloudSolutions Chile Servicios Tecnológicos SpA** es una empresa constituida en Iquique, Chile, dedicada a la provisión de infraestructura tecnológica de alto rendimiento, hosting, virtualización, inteligencia artificial, consultoría TI y desarrollo de sistemas a medida.

Especializados en el diseño de arquitectura moderna, impulsamos soluciones integrales que abarcan desde la gestión automatizada de activos de TI hasta el monitoreo proactivo de servidores en tiempo real.

---

### Stack Tecnológico & Ecosistema de Infraestructura

#### Backend & Servicios
- **Lenguajes & Frameworks:** C# | ASP.NET Core (.NET)
- **Comunicación en Tiempo Real:** SignalR para notificaciones e interacciones instantáneas
- **Seguridad & Autenticación:** Identity, SCRAM-SHA-256, OAuth 2.0 y JWT Refresh Tokens

#### Base de Datos & Motor Relacional
- **Motor Primario:** PostgreSQL 18.0+
- **Optimizaciones Avanzadas:** 
  - Asynchronous I/O (AIO) para maximizar IOPS en disco
  - Claves primarias UUIDv7 ordenadas temporalmente para reducir la fragmentación en índices B-Tree
  - Columnas generadas almacenadas (STORED) para cálculos financieros inmutables (IVA/Subtotales)
  - Consultas indexadas compatibles con B-Tree Skip Scans

#### Virtualización & Cloud
- **Contenerización:** Docker sobre Servidores Linux Dedicated/Host
- **Aislamiento de Recursos:** Asignación granular de CPU (millicores), RAM (MB), PIDs y ancho de banda
- **Control de Red:** Redes aisladas por cliente y comunicación vía mTLS (Puerto 2376) / Túneles SSH

---

### Proyectos & Soluciones Principales

#### SIGA-TI (Sistema de Gestión de Activos TI)
Plataforma SaaS integral bajo arquitectura de **Monolito Modular** diseñada para centralizar:
- **Gestión de Inventario TI:** Hardware, software, licencias y dispositivos de red con trazabilidad de mantenimiento.
- **Suscripciones & Facturación:** Motor de facturación recurrente con integración DTE (SII Chile: Facturas, Boletas, Notas de Crédito/Débito) e integración con pasarelas de pago (Webpay, MercadoPago, Stripe).
- **Proyectos Ágiles:** Módulo Scrum/Kanban integrado con gestión de sprints, historias de usuario y tareas.

#### HostGuard
Sistema de monitoreo proactivo de alta disponibilidad que realiza seguimiento continuo a la latencia HTTP, certificados SSL y disponibilidad (uptime) de infraestructuras críticas.

---

### Contacto & Ubicación Corporativa

- **Razón Social:** CloudSolutions Chile Servicios Tecnológicos SpA
- **Ubicación:** Iquique, Región de Tarapacá, Chile
- **Especialidades:** Cloud Computing, Hosting Dedicado, Desarrollo de Sistemas & Monitoreo TI

---

© 2026 CloudSolutions SpA. Todos los derechos reservados. | Propiedad Intelectual Corporativa

