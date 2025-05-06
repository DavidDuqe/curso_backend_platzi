# Titulo: Template de documento de diseño
---
## Overview: Problema a resolver
Descripción..

### Alcance(Scope)
Descripción..

#### Casos de uso
Descripción...
* Como editor me gustaria poder subir una review de una camara.
* Como editor me gustaria poder subir una review de un lente para las camaras.
* Como usuario no registrado me gustaria poder leer una review.


#### Out of Scope (casos de uso No Soportados)
Descripción...
* Como usuario no registrado me gustaria poder subir una review de una camara

## Arquitectura

### Diagramas
poner diagramas de secuencia, uml, etc

### Modelo de datos
Poner diseño de entidades, Jsons, tablas, diagramas entidad relación, etc..

---
## Limitaciones
Lista de limitaciones conocidas. Puede ser en formato de lista.
Ej.
* Llamadas al API que permite subir una reviw, no excede los limites de latencia Xms
* Llamadas al API que permite tener reviews para la lectura deben tener una latencia menor a 100ms
---
## Costo
Descripción/Análisis de costos
Contemplando 1000 usuarios diarios, que visitan recurrentemente cada hora:
Ejemplo:
"Considerando N usuarios diarios, M llamadas a X servicio/baseDatos/etc"
* 1000 llamadas diarias a serverless functions. $XX.XX
* 1000 read/write units diarias a X Database on-demand. $XX.XX
Total: $xx.xx (al mes/dia/año)
