# Informe de organizacion del repositorio (2026-04-20)

## 1) Resumen del analisis inicial
Se analizo todo el material que estaba en `inbox/` y el contexto ya existente en:
- `contexto/materia.md`
- `contexto/estilo.md`
- `bibliografia/por-ppt.md`
- `bibliografia/por-fuente.md`
- `resumen/parcial-1/`

Tipos de material detectado en `inbox/` antes de ordenar:
- PPTs de catedra
- transcripciones de clase
- libros/papers/documentos de bibliografia
- resumenes complementarios de parcial/final
- archivos duplicados exactos

## 2) Estructura elegida
Se mantuvo la estructura base del proyecto y se refinó asi:
- `fuentes/` por parcial y por PPT (con `catedra/` y `clase/` cuando aplica)
- `bibliografia/` separada por parcial/tema + carpeta `duplicados/`
- `resumen/` por parcial (se mantiene el enfoque correcto para estudio)
- `inbox/` vacia como bandeja de entrada para nuevo material

## 3) Movimientos aplicados
- Se movieron y renombraron 67 archivos automaticamente.
- Registro completo: `trabajo/movimientos-aplicados.txt`

Estado final:
- Archivos en `fuentes/parcial-1`: 11
- Archivos en `fuentes/parcial-2`: 5
- Archivos en `fuentes/generales`: 1
- Archivos en `bibliografia/fuentes/parcial-1`: 29
- Archivos en `bibliografia/fuentes/parcial-2`: 14
- Archivos en `bibliografia/fuentes/generales`: 5
- Archivos en `bibliografia/duplicados`: 2
- Archivos restantes en `inbox`: 0

## 4) Decisiones importantes
- Se priorizo granularidad por PPT dentro de `fuentes/parcial-1` para facilitar integracion de contenidos.
- Se separo bibliografia del material de catedra para evitar mezclar insumos primarios con soporte teorico.
- Los duplicados exactos se conservaron pero aislados en `bibliografia/duplicados/`.
- Se normalizaron nombres de archivos para que sean claros y consistentes.

## 5) Duplicados detectados (exact hash)
- `Addison.Wesley.The.Mythical.Man-Month...` y `The Mythical Man-Month...`
- `Paper - SCM - Bersoff...` y `Paper - SCM - Bersoff-Elements...`

## 6) Pendientes identificados
No se encontraron localmente algunas referencias citadas en los PPTs/contexto:
- Orphans Preferred
- planningpoker.com/detail.html
- mountaingoatsoftware.com (referencia web)
- 21 Tips For Getting A MVP Early Learning And ROI
- Userpilot MLP
- Aha! MLP

Estos pendientes quedaron explicitados en:
- `bibliografia/por-ppt.md`
- `bibliografia/por-fuente.md`

## 7) Criterios usados
- Simplicidad: pocas carpetas, nombres predecibles.
- Claridad de estudio: foco real en parcial 1.
- Trazabilidad: cada PPT con sus fuentes y bibliografia asociada.
- Preparacion futura: parcial 2 ordenado estructuralmente sin curado profundo.
