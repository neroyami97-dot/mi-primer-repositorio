# Uso de Markdown en Documentación Técnica
## ¿Qué es Markdown?
Markdown es un lenguaje de marcado ligero que permite escribir texto con formato de manera sencilla. Fue creado para que cualquier persona pudiera generar documentos claros sin necesidad de herramientas pesadas como Word o editores WYSIWYG.
Es ampliamente usado en desarrollo de software, documentación técnica y plataformas como GitHub, GitLab o Bitbucket.
## ¿Por qué se usa en proyectos de software?
- Es **fácil de escribir** y leer incluso sin renderizado.
- No requiere programas especiales (solo un editor de texto).
- Permite **tablas, listas, títulos, enlaces, imágenes y código**.
- Es compatible con la mayoría de herramientas de control de versiones.
- GitHub lo interpreta automáticamente al mostrar archivos `.md`.
## Elementos básicos de Markdown
###  Títulos
# Titulo 1
## Titulo 2
### Titulo 3
###  Listas
- Elemento 1  
- Elemento 2  
- Elemento 3  
###  Texto en negrita y cursiva
**Negrita**

_Cursiva_

###  Tablas
| Caso     | Descripción                           | Entrada                   | Resultado Esperado                                       |
| -------- | ------------------------------------- | ------------------------- | -------------------------------------------------------- |
| **CP01** | Registrar nuevo libro                 | Datos completos del libro | Libro registrado correctamente y aparece como Disponible |
| **CP02** | Prestar libro disponible              | Código “L-102”            | El libro cambia estado a *Prestado*                      |
| **CP03** | Intentar prestar un libro ya prestado | Código “L-102”            | Mensaje: “Libro no disponible”                           |


###  Enlaces
[Mi-primer-repositorio](https://github.com/neroyami97-dot/mi-primer-repositorio)


###  Imágenes
### Historial de commits
![Historial](Evidencias/historial_commits.png)


##  Ventajas de usar Markdown + GitHub

- Documentación limpia y profesional.  
- Vista previa automática de todo el archivo.  
- Integración perfecta con repositorios.  
- Facilita el versionado (cada cambio en el `.md` queda registrado).  
- Ideal para README, manuales, guías rápidas, reportes y documentación técnica.

---

## Conclusión
Markdown es una herramienta fundamental en el desarrollo moderno. Su simplicidad, compatibilidad y potencia al combinarse con GitHub lo convierten en el formato ideal para documentar proyectos de manera clara, organizada y profesional.
