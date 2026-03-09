# Campo de Inteligencia · 2026

Mapa interactivo del ecosistema de IA en 2026. Una guía estratégica visual para navegar modelos, precios y casos de uso — desde CDMX.

**Live:** [campo-ia.vercel.app](https://campo-ia.vercel.app)

---

## Qué es

Una página single-file que funciona como campo de exploración interactivo. Seis nodos, cada uno una zona de conocimiento distinta. Haz click en cualquier nodo para profundizar.

| Zona | Contenido |
|------|-----------|
| ⚡ El Paradigma | MoE, RLVR, Test-time Compute, MLA — los conceptos que cambiaron el juego |
| 👑 Los Titanes | Gemini 3.1 · Claude 4.6 · GPT-5.4 — stats, precios, para quién |
| 🔥 Los Disruptores | DeepSeek V3.2 · Qwen 3.5 · GLM-5 — open-weight, fracción del costo |
| 🎯 ¿Cuál Usar? | Recomendaciones tácticas por tipo de tarea y contexto geográfico |
| 💰 La Economía | Precios en USD / MXN / CAD — cuándo vale pagar, cuándo no |
| 🤖 Orquestación | Stack multi-agente óptimo y matriz de decisión final |

---

## Stack

- HTML + CSS + JS vanilla — sin frameworks, sin dependencias
- Fuentes: Orbitron · Space Mono · Syne (Google Fonts)
- Deploy: Vercel (static)

---

## Correr localmente

```bash
# Cualquiera de estas opciones funciona
npx serve .
python3 -m http.server 8080
# O simplemente abre index.html en el navegador
```

---

## Deploy

El proyecto se despliega automáticamente en Vercel con cada push a `main`.

```bash
# Manual si necesitas
vercel --prod
```

---

## Estructura

```
campo-ia/
└── index.html   # Todo el proyecto — HTML + CSS + JS en un solo archivo
```

---

## Licencia

MIT
