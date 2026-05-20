# Katala — Agente Literario

Herramienta de análisis narrativo para *Katala: La sangre no miente* de Arlete Sam.

Una aplicación web de una sola página que actúa como agente literario avanzado: lee tu manuscrito, detecta agujeros de trama, analiza personajes, verifica continuidad y edita gramática — todo con IA.

---

## Qué hace

- **Carga el manuscrito** — por archivo (.txt), pegando texto, o desde Google Drive
- **Análisis completo** — agujeros de trama, escenas faltantes, personajes, ritmo y tensión
- **Continuidad** — detecta contradicciones, personajes olvidados, subtramas abiertas
- **Arcos de personaje** — analiza si cada personaje evoluciona de manera coherente
- **Editor gramatical** — corrige ortografía, gramática y puntuación sin cambiar la voz
- **Descripciones** — enriquece el ambiente sin frenar el ritmo
- **Memoria del proyecto** — personajes, capítulos y subtramas guardados en el navegador

---

## Cómo usar

### Opción 1 — Directamente en el navegador

1. Descarga o clona este repositorio
2. Abre `index.html` en tu navegador (Chrome o Firefox recomendado)
3. Configura tu API key de Anthropic (botón "Configurar" arriba a la derecha)
4. Carga tu manuscrito y empieza a analizar

### Opción 2 — GitHub Pages (acceso desde cualquier dispositivo)

1. Haz fork de este repositorio en tu cuenta de GitHub
2. Ve a Settings → Pages → Source: rama `main`, carpeta `/root`
3. GitHub te dará una URL pública donde siempre estará disponible
4. Solo tú la usas — la API key se guarda en tu navegador, nunca se sube a ningún servidor

---

## API Key

Necesitas una API key de Anthropic:
1. Crea cuenta en [console.anthropic.com](https://console.anthropic.com)
2. Ve a API Keys → Create Key
3. Cópiala y pégala en la app (botón "Configurar")

**Coste aproximado:** analizar un manuscrito completo cuesta entre 0.01€ y 0.05€. Para uso habitual (edición de escenas, análisis puntuales) el coste mensual es mínimo.

La API key se guarda solo en tu navegador (`localStorage`). Nunca sale de tu dispositivo.

---

## Instrucción crítica para el análisis

La app está configurada para verificar el texto real antes de señalar problemas. Esto evita el error de sugerir escenas que ya están escritas. Cuanto más completo esté el contexto (personajes, capítulos, subtramas), más preciso será el análisis.

---

## Estructura

```
katala-app/
└── index.html    # Toda la aplicación en un solo archivo
```

No requiere servidor, instalación ni dependencias. Funciona directamente en el navegador.

---

*Arlete Sam © 2025 — uso privado*
