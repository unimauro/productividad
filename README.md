# Productividad — Observatorio de Horas de Trabajo y Productividad

Observatorio interactivo que compara **horas trabajadas** frente a **productividad laboral**
(PIB por hora, PPA) entre países, con **Perú** enmarcado en América Latina frente a Estados
Unidos y economías de alta productividad. Suma capas de calidad de vida: **informalidad**,
**tiempo de traslado** (commute) y **feriados / días no laborables**.

## Contenido

- **Dispersión horas vs productividad** — cada país como punto; Perú resaltado.
- **Informalidad laboral** — % del empleo.
- **Traslado al trabajo** — minutos/día en la ciudad principal (Lima destacada).
- **Feriados + días no laborables** — con el debate peruano sobre su impacto en productividad
  y servicios esenciales.
- Tarjetas con foco Perú, filtros por grupo, tabla de datos con fuentes y tema claro/oscuro.

## Datos y fuentes (verificados, 2023 salvo indicado)

- **Horas anuales** y **PIB por hora (US$ PPA)** — OECD Productivity Database / Average annual hours.
  Perú, Brasil y Argentina (no OCDE) = estimación **Penn World Table** (OWID); base distinta, no
  comparable 1:1 con la serie OECD.
- **Informalidad** — INEI (Perú, 71,1% 2023) e ILOSTAT (ODS 8.3.1). EE.UU. no se mide bajo ese marco (s/d).
- **Traslados** — IPE/BCRP (Lima: +57% entre 2010 y 2024, de 0,84 a 1,33 h/día), Moovit y censos
  (US Census, Destatis, CBS). Métricas y años heterogéneos → min/día ida+vuelta aproximado.
- **Feriados y días no laborables** — gob.pe/feriados, El Peruano (D.S. 042-2025-PCM, 075-2026-PCM)
  y gobiernos oficiales. El conteo es nacional/federal (varios países suman feriados regionales).
- **Debate Perú** — CCL y BCRP (un feriado extra ~0,04 pp menos de crecimiento del PBI el primer año).

### Advertencias
- Productividad en US$ PPA **corrientes**; México y Chile tienen revisiones de *vintage* en OECD.
- Horas de países no OCDE son orden de magnitud (PWT), no comparables directamente con OECD.

> El dataset vive en `index.html` (bloque `DATA`), con las notas metodológicas en el pie de la página.

## Uso

Es un sitio **estático de un solo archivo** (`index.html`), sin dependencias externas.
Se sirve tal cual en GitHub Pages o cualquier hosting estático.

## Licencia

Datos de fuentes públicas citadas. Código bajo MIT.
