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
- **42 países** en el dataset (OECD + Penn World Table); coloreados por **región** (Perú, América Latina, Norteamérica, Europa, Asia, Oceanía) con Perú resaltado.
- **Filtros por región dinámicos** (Todos / América Latina / Norteamérica / Europa / Asia / Perú vs USA) + **ejes que se auto-ajustan** al filtro (no queda todo aplastado abajo).
- **Gráfico Fortune Global 500** (barras) + **gráfico de burbujas** (productividad × horas × nº de grandes empresas) + card de análisis "grandes empresas y ecosistema".
- **Manifiesto/tesis con título en efecto de fuego** arriba (la baja productividad = falta de ambición/escala empresarial).
- **Subpanel de Alfredo**: tiempo comprometido (jornada + traslado, % de vigilia, 8 países LatAm) y traslado en Perú (ENUT 2024: nacional/Lima/periferia).
- **Traslado ampliado a 37/42 países** (Moovit + censos; one-way ×2 a día; caveat de heterogeneidad). s/d: RU, ID, GT, BO, HN.
- Google Analytics (gtag `G-KESBHVEHTC`).
- Fix: chatbot cierra con la X; textos a ancho completo; triángulo de acordeón grande con rebote.

## 🚧 Pendiente para próxima sesión (prioridad)
1. **Subpanel de Alfredo para más países**: llevar "jornada + traslado / % vigilia" más allá de los 8 LatAm (necesita jornada legal por país + commute; commute ya está para 37).
2. **Top-N en barras largas**: informalidad (~30), feriados (~38), FG500 (42) y traslado (37) hacen la página muy alta. Mostrar top-N con "+N más" (sin ocultar a Perú; log de lo recortado).
3. **Banderas SVG embebidas**: en Windows los emoji de bandera se ven como código ("PE"). Reemplazar por SVGs inline.
4. **Normalizar commute**: elegir one-way vs día y mostrar año/método por barra (hoy mezcla 2013-2026 y algunas one-way ×2). Portugal: nacional INE (20 one-way) vs Numbeo Lisboa — decidir.
5. **i18n ES/EN**.

## 🗺️ Backlog / ideas
- **Subpanel "Feriados y tiempo libre"** (Alfredo): ranking de tiempo libre real (días de descanso vs horas de vida libre).
- **"Horas de vida"**: horas semanales/mensuales fuera de trabajo + traslado (Lima: hasta ~60 h/mes solo en transporte → "trabajar y dormir").
- Toggle de año (2023 vs 2024) donde haya serie.
- Elegir una sola base de productividad (PPA corriente vs volumen) y documentarla.
- Compartir imagen del scatter/burbujas con Perú resaltado (para redes).
- Banner de consentimiento de cookies (por GA, si se busca cumplimiento GDPR/UE).

## 🐞 Notas / deuda técnica
- Emoji de banderas: en Windows se ven como código de país ("PE") — pendiente banderas SVG.
- Productividad de México/Chile: revisión de vintage OECD (marcado en la tabla).
- Informalidad de EE.UU.: no se mide bajo ODS 8.3.1 (s/d).
- Commute: 5 países en s/d (RU, ID, GT, BO, HN); métricas/años heterogéneos.
- Feriados: LatAm = conteo legal nacional; resto = Nager.Date (nacional) → no comparable 1:1 entre ambos grupos.

---

_¿Cómo sumar algo?_ Abre un issue o PR, o añádelo a este backlog. Cada dato debe citar su fuente.
