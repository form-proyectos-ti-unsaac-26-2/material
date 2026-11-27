# Guías de laboratorio — Pensamiento Computacional e IA (en Markdown)

Texto de las 48 guías de laboratorio del curso, convertido de PDF a Markdown.
Son solo texto: las imágenes, capturas y fórmulas de los PDF originales **no**
están acá (ver [Límites](#límites)).

## Estructura

```
md/
├── grupo-a/
│   ├── unidad-1/   guia-01.md … guia-06.md
│   └── unidad-2/   guia-07.md … guia-12.md
├── grupo-b/        (misma estructura)
├── grupo-c/
└── grupo-d/
```

- `grupo-{a,b,c,d}`: grupo de laboratorio (A–D).
- `unidad-{1,2}`: unidad del curso. Unidad 1 = guías 1–6, unidad 2 = guías 7–12.
- `guia-NN.md`: guía con número a dos dígitos, así ordenan bien alfabéticamente.

Las guías 1, 2 y 3 son **idénticas** en los cuatro grupos (mismo PDF de origen);
están repetidas para que cada `grupo-*/` se pueda leer completa por su cuenta. De
la 4 en adelante cada grupo tiene su propia versión.

## Índice de temas

| Guía | Tema |
| --- | --- |
| 01 | Fundamentos de informática |
| 02 | Internet y herramientas colaborativas |
| 03 | Herramientas de IA en el desarrollo académico y científico |
| 04 | Ingeniería de prompt (orientada a la carrera de cada grupo) |
| 05 | Búsqueda de información y artículos científicos |
| 06 | Sociedad y ética digital |
| 07 | Organización y procesamiento de datos (Portal Nacional de Datos Abiertos) |
| 08 | Gestión y visualización de datos |
| 09 | Estructuras secuenciales |
| 10 | Estructuras selectivas simples y dobles |
| 11 | Estructuras selectivas anidadas y múltiples |
| 12 | Estructuras repetitivas |

De la guía 04 en adelante el enfoque cambia según el grupo, aunque el tema sea el
mismo:

| Guía | Grupo A | Grupo B | Grupo C | Grupo D |
| --- | --- | --- | --- | --- |
| 04 | Ingeniería de prompt | Prompts aplicados a ciencias de la salud | Prompts aplicados a ciencias empresariales | Herramientas de IA en ciencias sociales |
| 05 | Artículos científicos en ingeniería | Artículos científicos en ciencias de la salud | Artículos científicos en ciencias empresariales | Búsqueda de información |
| 06 | Sociedad y ética digital | Ética en el uso de datos: Big Data y datos abiertos en Excel | Sociedad y ética digital | Verificación de similitud (Plagiarism Checker X) |
| 08 | Power BI | Power BI | Power BI y tablas dinámicas | Tablas dinámicas |
| 09 | Pensamiento computacional y estructura secuencial | Estructuras secuenciales | Estructuras secuenciales | Estructuras secuenciales |
| 11 | Python (`if`/`elif`/`else`) | Google Colab | Razonamiento lógico con condicionales | PSeInt (`Si`/`SiNo`) |
| 12 | Algoritmos de estructura repetitiva | Bucles `for`/`while` en Python (Colab) | Algoritmos de estructura repetitiva | Estructuras repetitivas |

Las guías 01, 02, 03, 07 y 10 son iguales (o casi iguales) en los cuatro grupos.

## Cómo moverse

```console
$ ls md/grupo-a/unidad-2          # ver las guías de un grupo/unidad
$ less md/grupo-c/unidad-1/guia-04.md
$ batcat md/grupo-d/unidad-2/guia-10.md   # con resaltado, si está instalado
```

### Buscar

```console
$ rg -l "estructura repetitiva" md/             # qué archivos lo mencionan
$ rg -n "Power BI" md/grupo-b/unidad-2/guia-08.md  # con número de línea
$ rg --files md/ | rg "guia-0[1-6]"             # por nombre de archivo
```

Cada `.md` empieza con el título (`# GUÍA DE LABORATORIO #NN`) y sigue con
`Tema`, `Competencias`, `Materiales`, `Fundamento teórico` y `Ejercicios`, así que
`rg -n "^#+ " archivo.md` da el índice de esa guía.

### Comparar grupos

```console
$ diff -u md/grupo-a/unidad-2/guia-09.md md/grupo-d/unidad-2/guia-09.md
$ md5sum md/*/unidad-*/guia-*.md | sort    # ver qué versiones coinciden
```

## Archivos originales

Los PDF, ZIP, XLSX, CSV y PNG de origen siguen intactos en la raíz, en las
carpetas `grupa a - unidad 1/`, `grupo a/GUIAS GRUPO A/`, `grupo b unidad 1/`, etc.
Equivalencias:

| Carpeta de origen | Destino |
| --- | --- |
| `grupa a - unidad 1/` (sic) | `md/grupo-a/unidad-1/` |
| `grupo a/GUIAS GRUPO A/` | `md/grupo-a/unidad-2/` |
| `grupo b unidad 1/` | `md/grupo-b/unidad-1/` |
| `grupo b unidad 2/GUIAS GRUPO B/` | `md/grupo-b/unidad-2/` |
| `grupo c unidad 1/` | `md/grupo-c/unidad-1/` |
| `grupo c/GUIAS GRUPO C/` | `md/grupo-c/unidad-2/` |
| `grupo d - unidad 1/` | `md/grupo-d/unidad-1/` |
| `grupo d unidad 2/GUIAS GRUPO D/` | `md/grupo-d/unidad-2/` |

Material adjunto que **no** está en `md/` porque no es texto convertible: los
`.xlsx` de trabajo y `.png` del solucionario de la guía 8 (grupo C, subcarpeta
`GUIA 8- ARCHIVOS/`), el `GRUPOS DE PCEEIA PARA CHARLA DE IA.xlsx` (grupo D) y el
`Listado_pacientes_nuevos_inen_enero2022_junio2024.csv` (grupo B, unidad 1).

## Regenerar

```console
$ ~/skills/opencode-skill-pdf2md/.venv/bin/pdfmd "grupo b unidad 1/Guia 4 Grupo B - Pensamiento Computacional e IA.pdf" \
    -o md/grupo-b/unidad-1/guia-04.md -v
$ ~/skills/opencode-skill-pdf2md/.venv/bin/mdlint md/grupo-b/unidad-1/guia-04.md
```

`mdlint` sin salida y con código 0 significa que el `.md` está bien formado. Las
páginas de estos PDF tienen capa de texto, así que no hace falta OCR (y el
paquete de idioma español de Tesseract no está instalado en esta máquina).

## Límites

- Sin imágenes: capturas, diagramas y figuras de los PDF no se extraen.
- Sin fórmulas ni bloques de código: el contenido matemático queda como texto plano.
- Las tablas se emiten como tablas GFM; filas combinadas pueden quedar achatadas.
- Algunos encabezados del PDF se derivan por numeración, así que el nivel de
  `#` puede variar de una guía a otra.
