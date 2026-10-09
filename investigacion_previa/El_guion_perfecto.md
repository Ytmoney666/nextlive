# Guía: el guion perfecto (para cualquier canal)

*Explicaciones en español. Los prompts van en inglés porque la IA escribe mejor el guion en el idioma del video. Cada recuadro gris tiene su botón de copiar.*

Es el método de los canales grandes, y sirve para cualquier nicho (crimen, historia, finanzas, misterio, ciencia…):

1. Tomas los guiones de videos que **ya funcionan** en tu nicho.
2. Los conviertes en un **estilo JSON**: una ficha de cómo escriben (tono, estructura, gancho, ritmo, recursos), sin copiar ningún tema ni ningún nombre.
3. Con ese JSON y la investigación de un tema nuevo, la IA escribe un **guion original** con el mismo estilo.

**Dónde vive cada cosa:**
- **Estilos JSON:** `Z:\NexaTube\guiones\estilos\<nicho>\`, más la plantilla vacía `_plantilla_estilo.json`.
- **Investigación de cada nicho:** `docs\NICHO_<nicho>.md` (en el Studio, Guías) y sus datos crudos en `research\nichos\<nicho>\`.
- **Ejemplo completo:** [Nicho: true crime](NICHO_TRUE_CRIME.md), con 42 canales analizados y 7 estilos JSON de crimen.

## El flujo completo

| Paso | Qué haces | Prompt |
|---|---|---|
| 1 | Elegir 3–5 canales de referencia | Nexlev, o la instrucción para Claude Code |
| 2 | Sacar sus guiones | Nexlev (transcripciones) |
| 3 | Crear el estilo JSON | «JSON Generation» |
| 4 | Elegir el tema del video | «Topic finder» |
| 5 | Investigar el tema | «Research dossier» |
| 6 | Escribir el guion | «Script from style JSON» |
| 7 | Título y miniatura | «Title rewrite» y «Thumbnail concepts» |
| 8 | Imágenes para Flow Studio | «Cinematic Image Generation» |
| 9 | Voz y video | Tu mp3 y **Nuevo video** |
| 10 | Revisar antes de subir | Lista del final |

Los pasos 1 a 3 se hacen **una vez por canal**; luego se repiten del 4 al 10 en cada video. Los prompts se pegan en Claude (claude.ai o Claude Code). Para el paso 6 usa un modelo grande, porque el guion ronda las 8.000 palabras. Si se corta, escribe `Continue exactly where you stopped, same style, no recap.`

## Paso 1 · Elegir los canales de referencia

**Buenos canales de referencia:**
- Hacen **el mismo formato** que vas a hacer tú (faceless, misma duración, mismo tipo de imágenes).
- Están **monetizados** y son recientes (creados en el último año).
- Tienen vistas constantes **y** algún video viral.

**De cada canal toma 1 o 2 virales y 1 o 2 normales:** los virales enseñan el gancho y los normales el estilo de base.

**Que Claude Code lo haga por ti** (dentro de NexaTube, con Nexlev conectado):

```text
Research the YouTube niche "[NICHE, e.g. solved cold cases in the USA]" with Nexlev: find 5 faceless English channels of the format "[FORMAT, e.g. 40-60 minute narrated documentaries with photos and stock]" that are monetized and growing. For each one give subscribers, average views, monthly views and estimated revenue, and pick 1 viral and 1 regular video. Fetch the transcripts of those videos with get_bulk_video_transcripts, save them as text in Z:\NexaTube\research\nichos\[niche]\guiones_competencia\, then run the "JSON Generation" prompt of docs\GUIA_SCRIPT_PERFECTO.md over them and save the style as Z:\NexaTube\guiones\estilos\[niche]\estilo_[name].json. Finally write docs\NICHO_[NICHE].md in Spanish with what you found, like NICHO_TRUE_CRIME.md, and add it to GUIAS in nexatube_api.py.
```

## Paso 2 · Sacar los guiones

- **Con Nexlev:** `get_bulk_video_transcripts` saca hasta 10 transcripciones a la vez.
- **A mano:** en YouTube, abajo del video, «Mostrar transcripción», y copias el texto.
- **Junta de 3 a 5 guiones completos.** Con uno solo, la IA copia sus manías y no el estilo.

## Paso 3 · Crear el estilo JSON

Pega los guiones debajo de este prompt:

```text
Analyze the provided YouTube scripts and create a "script style profile" in the form of a JSON object.

This profile should extract and describe the voice, structure, tone, pacing, and narrative techniques used in the script, in a way that allows an AI to recreate similar scripts in the same style, but for entirely different topics.

Do not include or reference any specific names, brands, events, characters, or subject matter from the original script.

Your job is to isolate and document the writing style, emotional tone, pacing, structure, rhetorical devices, and storytelling flow so that this same essence can be applied to different content while maintaining the exact same style.

The JSON should include (but not be limited to):

Tone of Voice: casual / dramatic / inspirational / comedic / informative / sarcastic / emotional / etc.

Narrative Structure: linear / non-linear / mystery reveal / chronological / flashbacks / cliffhangers / etc.

Characters

Dialogue

Humor (if any)

Pacing: fast-paced / slow-burn / punchy / rhythmic / etc.

Hook Style: question / shocking fact / emotional statement / cinematic build-up / dialogue snippet / etc.

Sentence Style: short & snappy / long & descriptive / rhetorical / casual / poetic / etc.

Visual Cue Prompts (if any): transitions, visual metaphors, on-screen text, cut timing, etc.

Common Devices: repetition, analogies, metaphors, irony, open loops, suspense, etc.

Emotional Tone: optimistic / tense / dramatic / hopeful / humorous / dark / uplifting / etc.

Point of View: first-person / second-person / third-person / omniscient / etc.

Language Style: simple / technical / poetic / edgy / motivational / street-smart / etc.

Audience Addressing Style: directly addressing viewer / narration without reference / conversational / character-based / etc.

General Style Tags: genre/feel, e.g., "motivational documentary", "true crime storytelling", "YouTube essayist", "inspirational short film", etc.

Also include a clear section defining script formatting rules, specifying that:

The final script must be sectioned into 10 parts, each part being at least 800+ words

The full script must be 8000+ words total

The script should include no section headings, no line breaks, no underscores, no comments, and no introductory or closing statements

The output should be sent in one batch, with only the script text (no surrounding instructions)
```

Guarda el resultado en `Z:\NexaTube\guiones\estilos\<nicho>\estilo_<nombre>.json`.

**Consejos:**
- Haz **un JSON por formato**: un caso por video, varios casos, etc.
- Además del JSON fiel, conviene uno **«mezcla viral»**: la estructura del canal principal con los ganchos de los virales de la competencia. Así es `crimen\estilo_cold_case_viral_mix.json`.
- Añade a mano lo que el prompt no saca: `best_for` (para qué videos sirve), `safety_and_compliance` (las reglas de tu canal) y `call_to_action_style` con el nombre de tu canal. La plantilla `_plantilla_estilo.json` tiene todos los campos.

**Formatos más largos o más cortos:** cambia las reglas del JSON. Para 2 horas, 14 partes y 16.000+ palabras, generadas en dos tandas de 7 partes. Para 20 minutos, 6 partes de 500 palabras.

## Paso 4 · Elegir el tema del video

```text
You are a YouTube content strategist for a faceless channel about [NICHE].
Suggest 20 video topics that fit this STYLE PROFILE and this audience: [AUDIENCE].
Rules:
- Each topic must have enough verifiable public information for a [LENGTH]-minute video.
- Prefer topics with a surprising turn, a clear human story and a strong visual.
- Avoid topics that 5+ big channels already covered in the last 12 months, unless you give a new angle.
- Respect these channel rules: [RULES, e.g. no minors, no medical claims].
For each topic give: a working title (max 100 characters), the hook in one sentence, why it can perform, and 3 sources to start the research.
STYLE PROFILE JSON: [PASTE THE JSON]
```

## Paso 5 · Investigar el tema

Para historias reales, la IA **solo** puede usar los hechos de este dossier. Así no inventa.

```text
You are a meticulous researcher. Build a research dossier for a [LENGTH]-minute YouTube documentary about: [TOPIC].
Use only verifiable public sources and give a link for every fact. Output in this order:
1. One-paragraph summary.
2. Full timeline with exact dates (and times if relevant), each line with its source link.
3. People involved: who they are, ages, roles, documented personal details. Mark anyone under 18 with [MINOR].
4. Places: what they are like, population, geography, era.
5. Context of the period: mood, economy, culture, headlines (5 bullet points).
6. The key mechanism or turning point explained step by step in plain words.
7. Documented quotes only (who, where, date, link). Never invent quotes.
8. Current status or outcome, with precise wording (legal, scientific, financial…).
9. Numbers that make the story vivid (counts, distances, money, years).
10. Public photos and footage available: what each shows and where it was published.
11. Uncertain or disputed points, clearly flagged.
Do not write the script yet.
```

## Paso 6 · Escribir el guion

Pega el estilo JSON y el dossier debajo del prompt.

```text
You are an expert YouTube scriptwriter for a faceless channel called [CHANNEL NAME].
Write a completely original narration script about the topic in the RESEARCH DOSSIER, following the STYLE PROFILE JSON exactly: its tone, point of view, structure and beats, hook style, pacing, sentence style, devices, call-to-action lines and emotional arc.
Rules:
- Use only facts from the dossier for anything presented as real. If something is uncertain, say so.
- Do not copy sentences from any existing video; only the style.
- Follow the safety_and_compliance rules of the JSON and these channel rules: [RULES].
- Follow the script_formatting_rules of the JSON exactly (parts, minimum words, no headings, no line breaks, no underscores, no bullet points, no brackets, no visual cues, no comments, no intro or outro outside the narration, everything in one batch).
STYLE PROFILE JSON:
[PASTE THE JSON]
RESEARCH DOSSIER:
[PASTE THE DOSSIER]
```

**Para videos cortos (10–12 min)**, usa este otro prompt:

```text
AI Documentary Scripting Prompt

You are an expert YouTube researcher, documentary writer, and visual director specializing in AI-generated educational storytelling.

When I give you a topic (for example, "Titanic Deck D"), your task is to:

🧠 1. Research & Analyze

• Gather accurate, in-depth, and engaging information about the topic.
• Focus on lesser-known details, human stories, and emotional depth to make it compelling.
• Maintain factual tone with storytelling flow — like a Netflix or National Geographic-style documentary.

🏗️ 2. Build a Script Structure

• Title suggestion (catchy yet factual).
• Intro hook (sets the emotional or mysterious tone within 100–150 words).
• 3–5 main sections — chronological or thematic, each at least 400–600 words.
• Reflection/ending that leaves the viewer thinking or emotional.

🎙️ 3. Narration Style

• Write in second-person or omniscient narrative tone, cinematic and descriptive.
• Use smooth transitions and sensory language to keep pacing natural.
• Keep the total script 10–12 minutes long (~1,500–1,700 words).

Topic: [INSERT YOUR TOPIC HERE]
```

## Paso 7 · Título y miniatura

Toma un título que funcione en tu nicho y reescríbelo:

```text
Please, rewrite the following title(s) so it doesn't look copied, keep the same structure and make it maximum 100 characters to comply with YouTube Limits
```

**Miniaturas:** cada una distinta, con un solo foco fuerte, tres palabras como máximo y un único elemento fijo de marca. Que no prometan nada que el video no muestre.

```text
You are a YouTube thumbnail strategist for a faceless channel about [NICHE].
For the video below, propose 5 different thumbnail concepts. Each concept must:
- Have one strong focal point (a face, an object, a place or a contrast).
- Carry at most 3 words of text.
- Keep one fixed brand element in the same corner: [BRAND ELEMENT].
- Follow these channel rules: [RULES, e.g. no blood, no minors].
- Never claim anything the video does not show.
- Be visually different from the other 4 concepts (layout, colour, subject).
For each concept give: layout description, the exact text, colours, and an image prompt in English to generate the background.
Video: [TITLE + ONE-PARAGRAPH SUMMARY]
```

## Paso 8 · Imágenes para Flow Studio

```text
Cinematic Image Generation from Script

You are an expert cinematic visual director and prompt engineer.

When I provide you with a full YouTube script (in text format), you will:

1. Read and analyze the script completely.

2. Automatically detect key scenes, emotional beats, and transitions across the story timeline — without me describing them.

3. Generate [X] realistic cinematic image prompts (replace X with any number I specify, e.g. 20).

4. Maintain visual continuity across all prompts (the same main characters, outfits, settings, and tone throughout).

5. Use a consistent realistic photo style, avoiding AI-artifacts or cartoon looks.

6. Write prompts optimized for Ideogram / Leonardo / Midjourney / etc., with a natural cinematic aesthetic.

Script: [INSERT YOUR SCRIPT HERE]
Number of images needed: [INSERT NUMBER]
```

**Si la historia es real y hay personas reales**, añade al final las reglas de tu canal, por ejemplo: víctimas nunca recreadas con IA, nada de menores, nada de gore, las recreaciones con rótulo. La versión ya hecha para crimen está en [Nicho: true crime](NICHO_TRUE_CRIME.md). Las imágenes IA que parezcan reales llevan el rótulo «AI recreation» o «Dramatization», y al subir marcas la casilla de contenido alterado o sintético.

## Paso 9 · Voz y video en NexaTube

1. Graba el guion con tu TTS (mp3).
2. En **Nuevo video**:
   - pega el guion y sube tu mp3;
   - elige el estilo del canal;
   - decide si usas **Clips de YouTube** e **Imágenes con mi Flow Studio**.
3. Si el estilo lo pide, abre con un plano 3D del motor three.js: lugares y ambiente, no personas.

Más detalle en [Hacer un video](GUIA_HACER_VIDEO.md) y [Contenido curado](GUIA_CONTENIDO_CURADO.md).

## Paso 10 · Antes de subir

- [ ] Todo lo que se presenta como real tiene fuente en el dossier.
- [ ] El guion respeta las reglas del canal (menores, IA, gore, afirmaciones médicas o financieras…).
- [ ] Imágenes IA realistas con rótulo, y la casilla de contenido sintético marcada al subir.
- [ ] Informe de curación sin avisos rojos (material ajeno corto y comentado).
- [ ] Miniatura distinta a las anteriores y fiel al video.

## Otros prompts

**Ebook Generator.** Sirve, por ejemplo, para un PDF de regalo, Patreon o un producto del canal.

```text
You are an expert ebook author and designer. Create a professional, visually polished 30-page PDF ebook on the topic of [X TOPIC].

Structure Requirements
Title page with ebook title, subtitle, and author name placeholder
Table of contents (page 2)
8-10 chapters, each 2-4 pages long
A conclusion/final thoughts chapter
A "Resources / Further Reading" page at the end

Content Requirements
Write in a conversational but authoritative tone — not robotic or generic
Each chapter should open with a hook (story, stat, or bold claim)
Include actionable takeaways at the end of every chapter
Use real-world examples, case studies, or analogies to illustrate points
Avoid filler — every paragraph should earn its place
Target audience: [DEFINE AUDIENCE HERE, e.g., "beginners curious about investing" or "entrepreneurs scaling to $10k/mo"]

Design & Formatting Requirements
Clean, modern layout with consistent margins and spacing
Use a professional font pairing (e.g., a serif for headings, sans-serif for body)
Include pull quotes or highlighted key insights per chapter
Use subtle color accents for headings and dividers (suggest a primary color: [e.g., #1A1A2E or #2563EB])
Add page numbers on every page except the title page
Chapter title pages should feel distinct (larger typography, minimal layout)

Output
Generate this as a complete, downloadable PDF file
Aim for ~300-400 words per page to hit 30 pages naturally
Read the PDF skill before starting to ensure maximum output quality

Replace [X TOPIC] with the desired subject before running.
```

## Biblioteca de estilos

| Nicho | Estilos | Investigación |
|---|---|---|
| Crimen / true crime (EE. UU.) | 7 en `guiones\estilos\crimen\`: casos fríos (mezcla viral ⭐ y sobrio), caso con 911, asesino en serie, varios casos de 1–2 h, regional y encubrimientos, interrogatorios reales | [Nicho: true crime](NICHO_TRUE_CRIME.md) |

Para un nicho nuevo:
1. Crea la carpeta `guiones\estilos\<nicho>\`.
2. Guarda ahí sus JSON.
3. Escribe `docs\NICHO_<nicho>.md` con lo encontrado.
4. Añade su fila a esta tabla.

La instrucción del paso 1 hace los cuatro pasos sola.

## Anexo · Plantilla vacía de estilo JSON

{{incluir: guiones/estilos/_plantilla_estilo.json}}
