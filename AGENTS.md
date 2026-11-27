# material — insumo documental de IF483BIN

Capturas en Markdown de los materiales de **IF483BIN Formulación y Proyectos de
TI (EPIIS–UNSAAC)** y de las guías de laboratorio de **Pensamiento Computacional
e IA**.

**Esto no es el informe.** El informe vive en otro repositorio (`informe`), con
las secciones en `src/main/sections/*.tex`. Aquí solo se lee y se busca: nada de
este repositorio se compila, se enlaza ni se copia literal al informe.

## Estructura

```text
slides/                 deck y consignas del curso IF483BIN (17 archivos .md)
  AGENTS.md             inventario, secuencia de sesiones y rarezas → leerlo antes de citar
pensamiento-ia-labos/
  README.md             índice de temas, diferencias por grupo y cómo regenerar
  md/grupo-{a..d}/unidad-{1,2}/guia-NN.md   48 guías de laboratorio (otro curso)
  pdfs/                 fuente original (PDF, XLSX, CSV, PNG) — NO versionada
```

Cada subcarpeta tiene su propio documento con el detalle. Este archivo solo
explica el contrato común.

## Reglas duras

1. **No se edita una captura.** Es el registro de un documento de un tercero. Una
   extracción corregida es una captura nueva con fecha nueva, no una reescritura.
2. **No se copia literal.** Se parafrasea; la cita va a `library.bib` del repo del
   informe, nunca al `.md` de acá.
3. **Lo dictado no es norma.** Para marco legal/normativo (Invierte.pe, D. Leg.
   1252, PMBOK) se cita la fuente oficial, no el deck.
4. **`[H]` significa hipótesis didáctica**, no hecho del caso. Va como hipótesis
   con su pregunta de validación.
5. **Números del TDR de videoconferencia (S/ 45 281,56, 2021) son históricos.**
   No son precios vigentes ni diagnósticos del proyecto propio.

## Lo que no está en git

`pensamiento-ia-labos/pdfs/` (~45 MB) está en `.gitignore`: son los PDF/XLSX/PNG
de origen, de los que se derivó `md/`. En un clon nuevo **no existen**. No
inventes su contenido ni asumas que están: si hacen falta, se piden. Todo `.pdf`
está ignorado por extensión.

## Cómo buscar

```bash
rg -n 'validación' slides/            # por contenido, nunca por nombre de archivo
rg -l '22 de octubre' slides/         # localizar una sesión por su fecha interna
rg -n '^#+ ' slides/2026-11-02_clase_22oct2026_costos_riesgos_caso_tdr_final_unsaac.md
rg --files pensamiento-ia-labos/md | rg 'guia-0[4-6]'
```

La fecha del nombre en `slides/` es la de **captura**, no la de la sesión (hay
cuatro excepciones tabuladas en `slides/AGENTS.md`). Al buscar por semana,
ordenar por sesión real.

## Antes de afirmar algo

1. ¿Sale de un deck (criterio de clase) o de una fuente primaria? Si es un deck,
   redactar como criterio del curso, no como dato.
2. ¿Es un número del caso 2021? Marcarlo como histórico.
3. ¿Está marcado `[H]` o «por validar»? Entonces es hipótesis, no hallazgo.
4. ¿Es formato de entrega? Manda la consigna
   `slides/2026-10-23_indicaciones_primera_sustentacion_formulacion_v1.md`, por
   encima de las diapositivas.

## Mantenimiento

Solo Markdown: no hay build, tests ni linter. Si agregas una captura, actualiza el
inventario de `slides/AGENTS.md` (familia, sesión real, estado de la extracción);
si agregas una guía, el índice de `pensamiento-ia-labos/README.md`.
