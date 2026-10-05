 ID | Driver arquitectónico | Driver relacionado | Justificacion |Resultado|
|---|---|---|---|---|
| ADR-001 | Monolito modular | DA01-Escabilidad;DA06-Mantenibilidad | Organizar las funcionalidades en modulos independientes dentro de una misma aplicacion desplegable  | Modulos de Catalogo, Carrito, Pedido, Pagos y Usuarios |
| ADR-002 | Clean Architecture | DA06-Mantenibilidad | Separ las reglas del negocio de los detalles tecnologicos  | Dominio, Aplicacion, Infraestructura y Presentacion. |
| ADR-003 | Estrategia de caché| DA02-Rendimiento | Reducir consultas repetitivas a la fuente de datos | Caché para informacion de consulta frecuente  |
| ADR-004 | Integracion de pagos mediante interfaces y adaptadores | DA04-Integracion con pagos | Desacoplar los caoss de uso del proveedor de pagos  | Contrato de pagos y adaptardor para la pasarela extrema |