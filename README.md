Proyecto: Sandbox 2.0 – Sistema de Gestión de Accesos Automatizado

Descripción técnica y funcional
Sandbox 2.0 es un sistema desarrollado con Google Apps Script, Google Sheets, Google Drive y Google Docs, diseñado para automatizar la gestión de accesos a entornos sandbox. El proyecto implementa una arquitectura basada en microservicios, cada uno responsable de una función específica, lo que permite mantener el sistema modular, escalable y fácil de mantener.

Funcionalidades principales

Gestión de usuarios e iniciativas mediante Google Sheets como base de datos central.

Generación automática de documentación legal (cartas responsivas) en Google Docs, indexadas en Drive y enlazadas a los registros en la base de datos.

Control de vencimientos con fórmulas dinámicas y triggers programados en Apps Script.

Reportes semestrales automáticos, actualizados en hojas dedicadas sin duplicar la información base.

Notificaciones simuladas mediante logs estructurados y capa de comunicación lista para integrarse con servicios externos.

Protección de integridad de datos, asegurando que solo ciertos campos sean editables, mientras que cálculos automáticos y checks permanecen protegidos.

Resultados

Reducción de tiempos de gestión gracias a la automatización.

Eliminación de errores manuales en cálculos de vencimiento y estados.

Mayor trazabilidad y control centralizado de accesos y documentación.

Preparado para evolucionar hacia analítica predictiva o integración con sistemas de notificación real (SMTP/API).
