# Juank Data Lab · Apoyo por encargo para agencias

Servicio asistido por IA, operado desde Quito. Consolidación de datos y preparación de documentos con alcance acordado, entregables editables y comprobaciones. Podemos entregar sin nuestra marca cuando se acuerde; la asistencia por IA se comunica a la agencia.

## Prueba pagada de consolidación — USD 45

- Entrada: hasta 3 archivos CSV/XLSX, 5.000 filas en total, 20 columnas y 5 MB por archivo. Una tabla rectangular por archivo; sin macros ni archivos protegidos.
- Reglas acordadas: correspondencia de columnas, identificadores como texto, formatos y criterio exacto de duplicados. Una coincidencia aproximada se marca para revisión; no se fusiona por suposición.
- Entrega: XLSX consolidado, resumen por fórmulas con hasta 3 medidas y una agrupación, conciliación de registros y una guía PDF breve. CSV de salida si se acuerda.
- Una corrección contra el alcance aprobado. Plazo: 72 horas desde archivos completos, reglas y condiciones de pago confirmadas.
- El precio cubre el lote descrito. Los trabajos de integración, OCR, VBA o cambios en sistemas en producción se cotizan por separado.

## Continuidad de reportes — USD 120 por un mes

Después de aceptar un piloto y confirmar la carga, se puede contratar un paquete de hasta 4 entregas en el mes, con la misma estructura y reglas: hasta 3 archivos, 3.000 filas totales y 20 columnas por entrega. Cada entrega incluye consolidación, conciliación y resumen acordado; una corrección. Plazo de 72 horas desde cada recepción completa.

El cliente o la agencia envía cada lote por el canal privado acordado. Se trata de reportes por lotes; la puesta en marcha de integraciones o infraestructura se cotiza aparte. Sin renovación automática. La capacidad y el calendario se confirman antes de contratar.

## Documentación de entrega — USD 35

Preparación de un documento comercial o manual breve a partir del contenido final de la agencia: hasta 1.800 palabras, 6 imágenes suministradas y 6 páginas A4. Entrega PDF digital y DOCX editable; una corrección; 72 horas desde el material final y las condiciones acordadas. Los materiales deben contar con autorización de uso.

## Demostración con datos ficticios

Este ejemplo muestra los controles propuestos. No es un trabajo de un cliente ni un testimonio comercial.

Dos lotes contienen siete registros: tres en A y cuatro en B. B repite exactamente FAC-002, incluye una fila vacía y añade FAC-004 y FAC-005. La fuente se conserva como trazabilidad; se compara el contenido de las otras cuatro columnas para detectar duplicados exactos.

| Control | Resultado calculado |
|---|---:|
| Registros de entrada, sin encabezados | 7 |
| Filas vacías | 1 |
| Duplicados exactos | 1 |
| Registros conservados | 5 |
| Conciliación | 7 = 5 + 1 + 1 |
| Importe conservado | USD 60,00 |

| Fuente | Factura ficticia | Identificador de cliente como texto | Región | USD |
|---|---|---|---|---:|
| A | FAC-001 | `001` | Norte | 12.50 |
| A | FAC-002 | `029` | Sur | 20.00 |
| A | FAC-003 | `1` | Norte | 7.50 |
| B | FAC-004 | `007` | Sur | 15.00 |
| B | FAC-005 | `010` | Centro | 5.00 |

Resumen comprobado: Norte USD 20,00; Sur USD 35,00; Centro USD 5,00. Los identificadores `001` y `1` permanecen distintos. Si una misma clave aparece con valores incompatibles, la regla de resolución debe acordarse antes de procesar el lote.

## Para cotizar un lote real

Enviar solo una descripción, formato, volumen, plazo y, si hace falta, una muestra anonimizada. Confirmamos reglas, entrega, precio final y condiciones de pago/facturación antes de empezar. Los archivos reales se reciben y entregan por un canal privado; no se publican en este repositorio.

Contacto comercial: triride593@gmail.com  
[Catálogo general](README.md) · [Consulta pública sin archivos privados](https://github.com/Juank2223/juank-data-lab/issues/1)

Versión comercial: 23 de noviembre de 2026.
