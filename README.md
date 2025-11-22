# Sistema de Gestión de Biblioteca – Caso 4

## Descripción del Caso
Este proyecto implementa un **Sistema de Gestión de Biblioteca** que permite registrar libros, realizar préstamos y devoluciones, y controlar el estado de disponibilidad de cada ejemplar. El objetivo es facilitar la administración básica de una biblioteca académica mediante un sistema claro, organizado y fácil de usar.
## Objetivos del Sistema
- Registrar y organizar libros dentro del catálogo.  
- Permitir la búsqueda rápida de libros por título, autor o categoría.  
- Automatizar el proceso de préstamos y devoluciones.  
- Controlar la disponibilidad de los ejemplares.  
- Mantener la integridad de la información registrada.
##  Requerimientos del Sistema (Resumen)
### **Requerimientos Funcionales**
- **RF1:** Registrar libros con título, autor, categoría, año y código único.  
- **RF2:** Buscar libros por título, autor o categoría.  
- **RF3:** Registrar préstamos indicando fecha y estudiante.  
- **RF4:** Registrar devoluciones de libros.  
- **RF5:** Mostrar el estado de cada libro (Disponible o Prestado).  
- **RF6 (V2):** Autenticación básica del bibliotecario.  
### **Requerimientos No Funcionales**
- **RNF1:** Interfaz sencilla y comprensible.  
- **RNF2:** Búsquedas deben ejecutarse en menos de 1.5–2 segundos.  
- **RNF3:** Evitar préstamos duplicados de un mismo libro.  
- **RNF4:** Sistema mantenible y fácil de extender.  
- **RNF5 (V2):** Respaldo automático de información semanal.
## Tabla de Pruebas Funcionales

| Caso | Descripción | Entrada | Resultado Esperado |
|------|-------------|---------|--------------------|
| **CP01** | Registrar nuevo libro | Datos completos del libro | Libro registrado correctamente y aparece como Disponible |
| **CP02** | Prestar libro disponible | Código “L-102” | El libro cambia estado a *Prestado* |
| **CP03** | Intentar prestar un libro ya prestado | Código “L-102” | Mensaje: “Libro no disponible” |

---

## Tipo de Mantenimiento Propuesto
El mantenimiento seleccionado para este caso es **Perfectivo**, ya que busca mejorar y ampliar las funcionalidades del sistema, ofreciendo una mejor experiencia al bibliotecario.  
Mejoras planteadas:
- Búsqueda inteligente con autocompletado.
- Historial de préstamos por estudiante.
- Alertas visuales para libros con retraso.
- Rediseño de interfaz para uso en pantallas pequeñas.
## Reflexión sobre el Control de Versiones
El uso de Git y GitHub permitió mantener un registro claro del progreso del proyecto, organizando de forma ordenada cada cambio realizado. Gracias al control de versiones se evitaron pérdidas de información, se conservaron las distintas versiones de los documentos (DRS v1 y v2) y se facilitó la documentación técnica.  
Esta herramienta es fundamental para el trabajo académico y profesional, ya que garantiza trazabilidad, seguridad y organización en el desarrollo de software.
Reflexión sobre el Control de Versiones
El uso de Git y GitHub permitió mantener un registro claro del progreso del proyecto, organizando de forma ordenada cada cambio realizado. Gracias al control de versiones se evitaron pérdidas de información, se conservaron las diferentes versiones de los documentos (DRS v1 y v2) y se facilitó la documentación técnica dentro del repositorio.
Esta herramienta es fundamental para el trabajo académico y profesional, ya que garantiza trazabilidad, seguridad y organización en el desarrollo de software.
