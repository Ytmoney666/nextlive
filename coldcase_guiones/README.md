# 10 guiones de 1 h 10 min estilo Cold Case Reopened

Canal de referencia principal: [Cold Case Reopened](https://www.youtube.com/@ColdCaseReopened01) (`UCHF9iZLaa0d3kRYNKtXrlrw`).
Secundarios: Root of Crime (`UCL8zagq4oOtCLsp1GOcvtWw`) y Crimewatch Central (`UCU3bje7O_BFzvCQZ5X4eRCw`).
Datos de NexLev consultados el 9 de octubre de 2026.

## 1. ¿Coincide NexLev con tu investigación previa?

| Dato | Tu investigación (`investigacion_previa/canales_true_crime.csv`) | NexLev hoy | ¿Coincide? |
|---|---|---|---|
| Suscriptores CCR | 15.400 | 16.300 | Sí (+900, ha seguido creciendo) |
| Vistas medias CCR | 42.360 | 41.435 | Sí |
| RPM CCR | 4,24 USD | 4,05 USD | Sí |
| Monetizado / faceless | sí / sí | sí / sí (confianza 0,98) | Sí |
| Duración media CCR | 40–49 min | 43,1 min | Sí |
| Root of Crime | 4.430 subs, 64.612 vistas medias | 4.600 subs, 62.097 vistas medias, RPM 5,42 | Sí |
| Crimewatch Central | 27.100 subs, 105.596 vistas medias, viral 1,1 M (Florida 1981) | 27.100 subs, 107.154 vistas medias, RPM 6,38; el viral es el caso Adam Walsh | Sí |
| Cold Case Uncovered | 15.600 subs, 74.431 vistas medias | 75.269 vistas medias, RPM 3,56 | Sí |
| CrimeWatch | 5.850 subs, 20.082 vistas medias | 20.314 vistas medias, RPM 5,46 | Sí |

**Donde NO coincido:** tu nota decía que el formato nuevo de CCR (40–49 min con miniatura «UNSOLVED») solo hacía de 3.000 a 14.000 vistas. Eso ya cambió. En el último mes los vídeos largos de CCR son los que más vistas tienen:

| Vídeo largo de CCR (sept. 2026) | Duración | Vistas |
|---|---|---|
| MARYLAND 1975 — Lyon Sisters | 47:05 | 151 K |
| NEW HAMPSHIRE 1985 — Bear Brook | 41:07 | 144 K |
| NEW JERSEY 1971 — John List Family | 47:23 | 140 K |
| WYOMING 1980 — Uden Family | 46:11 | 138 K |
| CALIFORNIA 2010 — McStay Family | 44:21 | 100 K |
| WISCONSIN 1980 — Hack & Drew | 46:57 | 71 K |
| KANSAS 1974 — Otero Family (BTK) | 45:52 | 64 K |

Los vídeos de la última semana (del 1 al 8 de octubre) están todavía entre 2.000 y 24.000 vistas, pero tienen pocos días. **Conclusión: el formato largo funciona. Lo que más rinde son las familias, los casos famosos y los giros fuertes.** Los casos poco conocidos y sin gancho en el título son los que se quedan bajos.

**Lecciones para títulos y miniaturas:**
- CCR usa `STATE YEAR Cold Case Solved After N Years — Justice for NAME`, con miniatura roja «UNSOLVED-YEAR» y dos líneas de gancho.
- Los virales de Root of Crime (274 K y 210 K) añaden un **giro** al título: «Her Killer Was Never a Suspect» o «A Dark Pickup Held the Clue for 33 Years». Cada guion trae 2 títulos alternativos con ese giro, para hacer pruebas A/B.
- El RPM del nicho es bajo (de 4 a 6,4 USD), así que el negocio está en el volumen. Que los vídeos duren 70 minutos sube el tiempo de visualización y deja poner más anuncios mid-roll.

## 2. Cómo se eligieron los 10 casos

- **No repetir** ningún caso que CCR ya haya publicado: Lyon, Bear Brook, List, Uden, McStay, Hack/Drew, BTK, Freeman/Bible, Etan Patz, Bennett, Stayner, Spangler, Ruth Terry, Olanick, Carlina White, Garecht, Dee/Moore, Jaycee Dugard, Yogurt Shop, Clouse, Rogers, Evelyn Colon, Girl Scouts de Oklahoma, Eastburn, Freund/Buckley, Laci Peterson, Gacy, Durham, Atkinson/Henry, Cook/Van Cuylenborg, Bogle/Kalitzke… Y, a juzgar por sus títulos sin nombre, probablemente también Sherri Rasmussen («The Killer Was a Detective»), Linda O'Keefe («California 1973») y Lindy Sue Biechler («Lancaster County, 1975»).
- Casos **resueltos o identificados**, con mucha información pública verificable para llenar 70 minutos.
- Mezcla de **giros virales**: un error judicial (Dodge, Ireland), un objeto ignorado que acabó resolviendo el caso (la servilleta de Childs, el chicle de Mirack), un podcast que rompió el caso (Smart), un nombre recuperado después de 65 años (Boy in the Box) y un caso famoso con mucho volumen de búsqueda (Golden State Killer).
- Variedad de estados y épocas, para no canibalizarse entre sí.

## 3. Los 10 guiones

Cada carpeta contiene:
- `guion.txt`: la narración en inglés, en 10 partes de 1.200 palabras o más (12.000+ en total ≈ 70 min a 170 palabras por minuto, que es el ritmo real de CCR). Va lista para el TTS.
- `investigacion.md`: el dossier en español, con título, miniatura, línea de tiempo, citas, cifras, puntos dudosos, fuentes con URL y la verificación del guion.
- `research_brief.json`: la plantilla «Research Brief» de la guía, rellenada.

| # | Carpeta | Caso |
|---|---|---|
| 1 | `01_iowa_1979_michelle_martinko` | Michelle Martinko, Cedar Rapids |
| 2 | `02_colorado_1982_schnee_oberholtzer` | Annette Schnee y Bobbie Jo Oberholtzer, Breckenridge |
| 3 | `03_idaho_1996_angie_dodge` | Angie Dodge, Idaho Falls (Christopher Tapp exonerado) |
| 4 | `04_hawaii_1991_dana_ireland` | Dana Ireland, Big Island (3 condenados por error) |
| 5 | `05_texas_1974_carla_walker` | Carla Walker, Fort Worth |
| 6 | `06_minnesota_1993_jeanne_childs` | Jeanne Childs, Minneapolis (la servilleta del hockey) |
| 7 | `07_california_golden_state_killer` | Golden State Killer, 1974–1986 |
| 8 | `08_california_1996_kristin_smart` | Kristin Smart, Cal Poly (el podcast) |
| 9 | `09_pennsylvania_1957_boy_in_the_box` | El niño de la caja, identificado después de 65 años |
| 10 | `10_pennsylvania_1992_christy_mirack` | Christy Mirack, Lancaster (el DJ) |

Los títulos finales y los textos de las miniaturas están al principio de cada `investigacion.md`.

### Estado final: 30 historias

Las 30 historias están completas. Cada una tiene 10 partes de 1.200 palabras o más, 2 llamadas a la acción, ni corchetes ni encabezados, y un JSON válido. Cada carpeta trae 4 archivos: `guion.txt` (en inglés), `investigacion.md` (en español, con fuentes), `research_brief.json` y `seo.txt`. **`SEO_30_videos.txt`** junta en un solo archivo el título, los títulos alternativos, la descripción con hashtags, las etiquetas y el texto de miniatura de los 30 vídeos.

| # | Título | Palabras | Duración (170 ppm) |
|---|---|---|---|
| 1 | IOWA 1979 Cold Case Solved — Her Attacker Bled in the Car. and DNA Named Him 39 Years Later | 12.570 | ~74 min |
| 2 | COLORADO 1982 Cold Case Solved After 39 Years — Justice for Annette and Bobbie Jo | 12.288 | ~72 min |
| 3 | IDAHO 1996 Cold Case Solved After 23 Years — Justice for Angie Dodge | 12.383 | ~73 min |
| 4 | HAWAII 1991 Cold Case — DNA Identified the Killer After 32 Years \\| Dana Ireland | 12.583 | ~74 min |
| 5 | TEXAS 1974 Cold Case Solved After 46 Years — Justice for Carla Walker | 12.658 | ~74 min |
| 6 | MINNESOTA 1993 Cold Case Solved After 25 Years — Justice for Jeanie Childs | 12.469 | ~73 min |
| 7 | CALIFORNIA 1975 Cold Case Solved After 43 Years — Justice for the Golden State Killer's Victims | 12.852 | ~76 min |
| 8 | CALIFORNIA 1996 Cold Case Solved After 26 Years — Justice for Kristin Smart | 12.457 | ~73 min |
| 9 | PENNSYLVANIA 1957 Cold Case Identified After 65 Years — The Boy in the Box Finally Has a Name | 12.681 | ~75 min |
| 10 | PENNSYLVANIA 1992 Cold Case Solved After 25 Years — Justice for Christy Mirack | 12.383 | ~73 min |
| 11 | WASHINGTON 1982 Cold Case Solved After 19 Years — Justice for the Green River Victims | 12.576 | ~74 min |
| 12 | CALIFORNIA 1985 Cold Case Solved After 25 Years — Justice for the Lost Women of South LA | 12.433 | ~73 min |
| 13 | MASSACHUSETTS 1964 Cold Case: Killer Identified After 49 Years — Justice for Mary Sullivan | 12.397 | ~73 min |
| 14 | FLORIDA 1981 Cold Case — Police Named Adam Walsh's Killer After 27 Years | 12.567 | ~74 min |
| 15 | ILLINOIS 1993 Cold Case Solved After 9 Years — Justice for the Brown's Chicken Seven | 12.538 | ~74 min |
| 16 | WASHINGTON 1972 Cold Case Solved After 48 Years — Justice for Jody Loomis | 12.506 | ~74 min |
| 17 | ARIZONA 1992 Cold Case Solved After 22 Years — Justice for Angela Brosso and Melanie Bernas | 12.530 | ~74 min |
| 18 | OHIO 1980 Cold Case Solved After 24 Years — Justice for Sister Margaret Ann Pahl | 12.454 | ~73 min |
| 19 | TEXAS 2010 Cold Case Identified After 6 Years — The Woman Who Lived as Lori Ruff | 12.691 | ~75 min |
| 20 | KENTUCKY 1968 Cold Case Identified After 30 Years — The Tent Girl Was Barbara Taylor | 12.386 | ~73 min |
| 21 | ALASKA 1993 Cold Case Solved After 26 Years — Justice for Sophie Sergie | 12.496 | ~74 min |
| 22 | CALIFORNIA 1984 Cold Case Solved After 27 Years — Justice for Tina Faelz | 12.440 | ~73 min |
| 23 | MICHIGAN 1987 Cold Case Solved After 35 Years — Justice for Roxanne Wood | 12.477 | ~73 min |
| 24 | TEXAS 1995 Cold Case Solved After 26 Years — Justice for Mary Catherine Edwards | 12.482 | ~73 min |
| 25 | MICHIGAN 1987 Cold Case Solved After 26 Years — Justice for Rick & Gail Brink | 12.340 | ~73 min |
| 26 | MICHIGAN 1969 Cold Case Solved After 35 Years — Justice for Jane Mixer | 12.513 | ~74 min |
| 27 | MASSACHUSETTS 1969 Cold Case — DNA Identified Her Killer After 49 Years \\| Jane Britton | 12.478 | ~73 min |
| 28 | Medgar Evers: How a Widow and Secret Files Solved a 31-Year Cold Case \\| Mississippi 1963 | 12.392 | ~73 min |
| 29 | VERMONT 1971 Cold Case — DNA Identified Her Killer After 51 Years \\| Rita Curran | 12.744 | ~75 min |
| 30 | WASHINGTON 1986 Cold Case Solved After 32 Years — Justice for Michella Welch | 12.429 | ~73 min |

- Del 1 al 10: la primera entrega.
- Del 11 al 20: casos con demanda comprobada. Joseph Newton Chandler se sustituyó por la hermana Pahl, porque los datos mostraron que estaba saturado.
- Del 21 al 30: el TOP elegido con datos de NexLev (`_nicho/seleccion_casos.md`).
- Los casos 4, 9, 13, 14, 19, 20, 27 y 29 dicen «Identified» o «Police Named» en vez de «Solved», porque nadie fue condenado.

**Informes del nicho (`_nicho/`):**
- `investigacion_nicho_miniaturas.md`: los 15 vídeos virales de la competencia, con descripción completa, hashtags y etiquetas; las fórmulas de título y de miniatura; si las caras de las miniaturas de CCR son reales (casi seguro que no todas); los riesgos legales y de YouTube, y 17 reglas para el canal.
- `seleccion_casos.md`: el ranking de 22 candidatos con datos de NexLev y la validación de los casos elegidos.

**Orden de publicación sugerido** (según `seleccion_casos.md`):
- Primero, los casos sin copias de la competencia: Pahl, Sergie, Faelz y Mixer.
- No publiques seguidos dos megacasos como Golden State, Green River o Grim Sleeper.
- Retrasa Dana Ireland y Christy Mirack: Cold Case Redemption los publicó hace 1–2 meses.

**Aviso importante sobre las fuentes:** la red del entorno bloqueó la descarga de páginas y las búsquedas web tenían un cupo. Por eso los datos se verificaron con los extractos del buscador (de 18 a 69 fuentes por caso) y no con los artículos completos. Antes de publicar cada vídeo, revisa la sección «pendiente de verificar» de su `investigacion.md`.

**Caso 4 (Dana Ireland):** Albert Lauro Jr. nunca fue acusado ni condenado; murió en 2024. Por eso el título se cambió (11 oct 2026) a «HAWAII 1991 Cold Case — DNA Identified the Killer After 32 Years | Dana Ireland», sin «Solved».

## 4. Método aplicado (tu guía)

1. **Estilo JSON**: `_base/estilo_ccr_70min.json`. Junta tu `estilo_cold_case_reopened.json` con tu `estilo_cold_case_viral_mix.json` y lo ajusta a 70 minutos: 10 partes de 1.200 palabras o más, con un plan de qué va en cada parte.
2. **Research Brief JSON**: `_base/plantilla_research_brief.json`, la plantilla de la lección. Cada sub-agente la rellenó solo con datos verificados y con la fuente de cada uno.
3. **Prompt mágico**: estilo + brief → guion. Hay un cambio respecto al prompt de la lección: se quitan los encabezados de sección, porque tu guía `El_guion_perfecto.md` pide narración continua para el TTS. Las 10 partes quedan separadas por una línea en blanco.

Antes de subir cada vídeo, revisa la lista del paso 10 de tu guía: las fuentes, las reglas del canal, la etiqueta en las imágenes IA y la casilla de contenido sintético.
