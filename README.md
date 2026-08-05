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

## Datos y fuentes

Fuentes oficiales e internacionales: **OECD** (horas anuales, PIB por hora), **ILOSTAT** e
**INEI** (informalidad), **Moovit / estudios locales** (traslados), **PCM / El Peruano**
(feriados y días no laborables). Los países fuera de la OCDE (Perú, Brasil, Argentina) usan
estimaciones de ILOSTAT / Conference Board donde la OECD no publica el dato; se indican como tales.

> Nota: el dataset se mantiene en `index.html` (bloque `DATA`). Cada valor cita su fuente en la
> tabla de la página.

## Uso

Es un sitio **estático de un solo archivo** (`index.html`), sin dependencias externas.
Se sirve tal cual en GitHub Pages o cualquier hosting estático.

## Licencia

Datos de fuentes públicas citadas. Código bajo MIT.
