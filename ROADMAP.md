# Roadmap / Backlog — Observatorio Productividad

Tablero vivo: https://unimauro.github.io/productividad/ · Repo: https://github.com/unimauro/productividad

## Colaboradores
- **Carlos Cárdenas** ([@unimauro](https://github.com/unimauro)) — tablero de productividad, infraestructura, chatbot.
- **Alfredo Corillo** ([@camaradacori](https://github.com/camaradacori)) — análisis de **feriados** y **horas trabajadas / tiempo libre**.

> Idea acordada: el enfoque de Alfredo (comparar **feriados y tiempo libre**) entra como **subpanel** dentro del observatorio (misma marca, sección propia) en lugar de un repo separado.

---

## ✅ Hecho
- Gráfico horas trabajadas vs productividad (PIB/hora), con Perú resaltado; foco Perú/LatAm/USA/referentes.
- Barras de informalidad, traslado (commute) y feriados + días no laborables.
- Tarjetas con foco Perú (con fuente por tarjeta), tabla con fuentes, tema claro/oscuro (toggle persistente).
- Descargas: CSV, PDF (impresión) y **PNG por gráfico** (con marca de agua).
- Análisis en 5 cards colapsables con animación; FAQ (con fuentes país por país).
- Banderas en puntos y barras; degradados en barras.
- SEO: OG/Twitter + og.png, favicon, robots.txt (permite bots de IA), sitemap, JSON-LD.
- **Chatbot IA** (ai.tunky.net) con enlaces `#sección` clicables.
- **Sidebar** de navegación (fijo en escritorio, cajón en móvil) con sección activa.
- Créditos + apoyo (Café / Yape / PayPal) + compartir en redes.

## 🚧 En progreso
- **Más países**: China, India, Vietnam, Indonesia, Japón, Suiza, Rusia, Europa y más de LatAm (agente reuniendo data verificada). Grupo gris "Otros países" ya listo para no robar foco.
- **Grandes empresas (Fortune Global 500)** por país — nuevo indicador (tesis: economías con muchas grandes corporaciones generan más valor por hora).

## 🗺️ Backlog / ideas
- **Subpanel "Feriados y tiempo libre"** (Alfredo): comparar días de descanso vs horas efectivas de vida libre; ranking de tiempo libre real.
- **"Horas de vida"**: métrica de horas semanales/mensuales fuera de trabajo + traslado. En Lima el viaje llega a 3-4 h/día en los conos → ~60 h/mes solo en transporte. Mensaje: "trabajar y dormir".
- Nuevo gráfico Fortune Global 500 + card de análisis "ecosistema de grandes empresas".
- Sumar España y Corea del Sur (data ya reunida).
- Toggle de año (2023 vs 2024) donde haya serie.
- Elegir una sola base de productividad (PPA corriente vs volumen) y documentarla.
- Mejorar commute: separar "por trayecto" vs "por día" y citar año por celda.
- Banderas SVG embebidas (para que se vean también en Windows, no como "PE").
- i18n ES/EN.
- Compartir imagen del scatter con la posición de Perú resaltada (para redes).

## 🐞 Notas / deuda técnica
- Emoji de banderas: en Windows se ven como código de país ("PE") — pendiente banderas SVG.
- Productividad de México/Chile: revisión de vintage OECD (marcado en la tabla).
- Informalidad de EE.UU.: no se mide bajo ODS 8.3.1 (s/d).

---

_¿Cómo sumar algo?_ Abre un issue o PR, o añádelo a este backlog. Cada dato debe citar su fuente.
