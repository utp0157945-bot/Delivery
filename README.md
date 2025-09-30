# Delivery
Este documento se basa en como organizar un sprint de uma semana paar el Delivery

1. Descripción

La App de entregas es una aplicación multiplataforma diseñada para optimizar el proceso de pedidos y entregas de comida. Está enfocada en ofrecer una solución digital que conecte de manera eficiente a clientes, restaurantes y repartidores, garantizando rapidez, seguridad y comodidad en cada fase del servicio.

En la actualidad, las aplicaciones de entrega de alimentos han transformado la manera en que las personas consumen productos gastronómicos. Sin embargo, muchos sistemas carecen de integración completa o presentan limitaciones en aspectos como la experiencia de usuario, el rastreo en tiempo real y la seguridad en los pagos. La App de entregas busca cubrir estas necesidades mediante un flujo de trabajo ágil, un diseño intuitivo y tecnologías modernas de desarrollo de software.

Las principales funcionalidades que contempla el proyecto son:

Registro e inicio de sesión seguro de usuarios (clientes, restaurantes y repartidores).

Catálogo de restaurantes y productos con filtros avanzados.

Carrito de compras para gestionar pedidos de manera sencilla.

Pasarela de pagos confiable que soporte diferentes métodos de pago.

Seguimiento en tiempo real del repartidor mediante geolocalización.

Sistema de notificaciones instantáneas tanto para clientes como para repartidores.

Panel de administración para la gestión de restaurantes, pedidos y usuarios.

La arquitectura de la aplicación se desarrollará bajo un enfoque ágil y DevOps, permitiendo que el equipo entregue valor de forma continua mediante ciclos de desarrollo cortos (sprints), pruebas constantes, despliegue automatizado y monitoreo del rendimiento en producción.

En resumen, la App de entregas no solo busca ser una alternativa tecnológica más, sino una solución completa que combine usabilidad, escalabilidad y seguridad, ofreciendo un servicio de calidad a los usuarios finales y facilitando la operación de los restaurantes y repartidores.

2. Objetivo

El objetivo general de la App de entregas es crear una plataforma digital que agilice el proceso de compra, entrega y monitoreo de pedidos de comida, proporcionando una experiencia eficiente tanto para los clientes como para los negocios asociados y los repartidores.

Objetivos específicos:

Implementar un sistema de registro e inicio de sesión seguro con validaciones y protección contra accesos no autorizados.

Desarrollar un catálogo de restaurantes y productos que permita búsquedas rápidas y personalizadas.

Incorporar un carrito de compras dinámico que permita modificar pedidos antes de confirmar la compra.

Integrar una pasarela de pagos segura que soporte tarjetas de crédito, débito y plataformas digitales.

Habilitar el rastreo en tiempo real del repartidor mediante servicios de geolocalización.

Diseñar un sistema de notificaciones automáticas para mantener informados a clientes y repartidores.

Garantizar la escalabilidad del sistema mediante arquitectura en la nube y despliegue con contenedores.

Cumplir con normas y estándares internacionales de calidad y seguridad en software (ISO/IEC, OWASP, ITIL).

3. Sprint de una semana (ejemplo)

 Duración: 7 días (1 semana)
 Objetivo del sprint: Implementar el módulo de registro e inicio de sesión de usuarios con conexión a la base de datos y validaciones de seguridad.

 | Día       | Actividad principal                                                    | Responsable                                 | Herramientas                           |
| --------- | ---------------------------------------------------------------------- | ------------------------------------------- | -------------------------------------- |
| **Día 1** | Planificación del sprint, definición de historias de usuario y backlog | Product Owner (Hugo) + Scrum Master (Aylin) | Trello / Jira                          |
| **Día 2** | Diseño de la base de datos y endpoints de autenticación                | Dev Team                                    | MySQL, Workbench                       |
| **Día 3** | Desarrollo del API de registro e inicio de sesión                      | Dev Team                                    | Node.js / Express / Visual Studio Code |
| **Día 4** | Desarrollo de frontend con formulario de login y registro              | Dev Team                                    | Angular / React                        |
| **Día 5** | Pruebas unitarias y de integración (login y registro)                  | Dev Team                                    | Jest, Postman                          |
| **Día 6** | Integración continua y despliegue en entorno de prueba                 | Scrum Master                                | GitHub Actions / Docker                |
| **Día 7** | Revisión de sprint, retrospectiva y demo al equipo                     | Todo el equipo                              | Zoom / Google Meet                     |

4. Herramientas a utilizar
🔹 Gestión y planificación

Jira / Trello: Para la administración de historias de usuario, backlog y tareas.

Scrum: Marco de trabajo ágil para la organización de sprints y roles.

🔹 Desarrollo

Frontend: Angular o React para interfaces dinámicas e intuitivas.

Backend: Node.js con Express para creación de APIs escalables.

Base de datos: MySQL como sistema de gestión de datos.

IDE: Visual Studio Code como entorno de desarrollo principal.

🔹 Control de versiones y CI/CD

GitHub: Repositorio central de código.

GitHub Actions: Automatización de integración y despliegue.

Docker: Contenerización y despliegue en entornos controlados.

🔹 Pruebas y seguridad

Jest (JS): Pruebas unitarias en el backend.

Postman: Pruebas de endpoints de API.

OWASP ZAP: Pruebas de seguridad contra vulnerabilidades.

🔹 Despliegue y monitoreo

AWS / Azure: Infraestructura en la nube para producción.

Prometheus + Grafana: Métricas de rendimiento y monitoreo en tiempo real.

Sentry: Registro de errores en producción.

