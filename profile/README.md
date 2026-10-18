# CloudSolutions SpA — Servicios Tecnológicos & Infraestructura Cloud

<p align="center">
  ![Ubicación](https://img.shields.io/badge/Ubicaci%C3%B3n-Iquique%2C%20Chile-0052CC?style=for-the-badge&logo=googlemaps&logoColor=white)
  ![Arquitectura](https://img.shields.io/badge/Arquitectura-Monolito%20Modular-8A2BE2?style=for-the-badge)
  ![Backend](https://img.shields.io/badge/Backend-ASP.NET%20Core%20%2F%20.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
  ![Base de Datos](https://img.shields.io/badge/Base_de_Datos-PostgreSQL%2018.0%2B-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
  ![Infraestructura](https://img.shields.io/badge/Infraestructura-Docker%20%2F%20Linux-2496ED?style=for-the-badge&logo=docker&logoColor=white)
</p>

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

### 📦 Tipos de Proyectos & Soluciones

En **CloudSolutions SpA** nos especializamos en el diseño, desarrollo y despliegue de diversas tipologías de software corporativo e infraestructura cloud:

- **Plataformas SaaS & Sistemas de Gestión Enterprise:** Soluciones integrales para la administración de activos de TI, gestión de inventarios, automatización de clientes y facturación recurrente.
- **Servicios de Hosting & Virtualización Mantenida:** Aprovisionamiento y despliegue de soluciones de hosting gestionado, entornos contenerizados en Docker y administración de servidores dedicados Linux.
- **Sistemas de Monitoreo & Observabilidad (Alta Disponibilidad):** Plataformas de monitoreo proactivo para la verificación continua de tiempo de actividad (*uptime*), análisis de latencia HTTP y estado de certificados SSL.
- **Desarrollo Web & Portales Corporativos:** Aplicaciones web dinámicas, sitios corporativos de alto rendimiento y sistemas de gestión de contenidos (CMS) a medida.
- **Consultoría Tecnológica & Integración Tributaria/Pasarelas:** Servicios de arquitectura de software, integración con pasarelas de pago y cumplimiento de facturación electrónica DTE (SII Chile).

---


© 2026 CloudSolutions SpA. Todos los derechos reservados. | Propiedad Intelectual Corporativa
