# Contexto CosmosDB (AutoGenDB)

### Descripción y Tipado de Campos

- **id**: Identificador único del registro [type: string]
- **fecha**: Fecha de venta [type: string]
- **ventas_Modelo1**: Número de ventas del modelo 1 [type: integer]
- **ventas_Modelo2**: Número de ventas del modelo 2 [type: integer]
- **total_ventas**: Total de ventas de ambos modelos [type: integer]

### Clave de Partición (PK) y Ordenación (SK)

- **PK**: fecha
- **SK**: None

### Ejemplo de Estructura de Datos

```json
{
  "id": "d0f4485c-2670-4d26-b267-99d7e9c05e6c",
  "fecha": "2024-03-01",
  "ventas_Modelo1": 1,
  "ventas_Modelo2": 2,
  "total_ventas": 3
}