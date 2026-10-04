# M3 — Conductores y Vehículos

Trabajo Práctico Integrador de Desarrollo de Software 2026 · Grupo 02.

Este repositorio reúne el trabajo del **Módulo 3** de la plataforma distribuida de movilidad urbana bajo demanda. M3 administra los datos y el estado de los conductores y sus vehículos.

## Estado

Proyecto en preparación. Las interfaces con otros módulos se definirán mediante OpenAPI antes de implementar las integraciones.

## Alcance del módulo

- Perfil del conductor y estado de habilitación.
- Registro de vehículos de tipo auto y moto y sus tipos de servicio.
- Metadatos y vencimientos de licencia, seguro y documentación del vehículo.
- Aprobación, observación, suspensión o rechazo de habilitaciones por un operador autorizado, con motivo trazable.
- Validación de habilitación del conductor y del vehículo antes de participar en el despacho.
- Estado conectado/desconectado y disponible/no disponible, coordinado con M4.
- Calificación del cliente después de un viaje completado, sin duplicados.

## Integraciones principales

| Módulo | Relación con M3 |
| --- | --- |
| M1 — Identidad y Acceso | Autenticación y permisos. |
| M4 — Ubicación y Disponibilidad | Coordinación del estado operativo y consulta de conductores aptos. |
| M5 — Solicitud y Despacho | Elegibilidad de conductores y vehículos para asignación. |
| M6 — Viajes y Ciclo de Vida | Información del conductor y validación de viajes completados para calificaciones. |

## Documentación y ejecución

Se agregarán aquí el contrato OpenAPI, las decisiones técnicas y las instrucciones para ejecutar y probar el módulo conforme avance el desarrollo.
