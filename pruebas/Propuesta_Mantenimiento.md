| Caso | Descripción                           | Entrada              | Resultado Esperado                            | Validación       |
| ---- | ------------------------------------- | -------------------- | --------------------------------------------- | ---------------- |
| CP01 | Registrar libro                       | Datos completos      | Libro se registra y aparece como Disponible   |  Confirmado     |
| CP02 | Prestar libro disponible              | Código libro “L-102” | Estado cambia a "Prestado"                  |  Correcto       |
| CP03 | Intento de préstamo de libro prestado | Código libro “L-102” | El sistema debe mostrar “Libro no disponible” |  Error mostrado |
