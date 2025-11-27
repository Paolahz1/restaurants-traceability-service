# restaurants-traceability-service
trazabilidad de los pedidos de los clientes dentro de la plazoleta de comidas, permitiendo saber en todo momento el estado de cada pedido y su historial de cambios.

## Responsabilidades principales
- Registrar cada cambio de estado de un pedido (pendiente, en preparación, listo, entregado).  
- Mantener un historial completo de la evolución de cada pedido.  
- Permitir que los clientes consulten la trazabilidad de sus propios pedidos.  
- Integrarse con **hub-service** mediante llamadas para actualizar la trazabilidad cuando se crea o modifica un pedido.  
- Persistir la información en **MongoDB** para un acceso rápido a historiales y logs.

## Tecnologías
- **Spring Boot**  
- **MongoDB**  
- **Arquitectura hexagonal**  
