# Selección de casos para el próximo lote (vídeos de 70 min)

Canal: faceless, en inglés, sobre cold cases **resueltos** de EE. UU. Modelo: Cold Case Reopened (CCR, UCHF9iZLaa0d3kRYNKtXrlrw).
Fecha del análisis: 11-oct-2026. Fuentes de datos: NexLev (`youtube_search`, `search_videos`, `faceless_outliers_videos`, `youtube_channel_videos`) y 5 búsquedas web, usadas para verificar el estado judicial.

---

## 0. Hallazgos previos que cambian la selección

**Vídeos nuevos de CCR** (las 2 páginas más recientes, 60 vídeos) que no estaban en la lista de excluidos:
- *OHIO 1989 … Justice for the Avery Family*: los asesinatos de la secta de Jeffrey Lundgren en Kirtland. 7,9K vistas.
- *MICHIGAN 1985 … Justice for David Tyll & Brian Ognjan*. 33K vistas.
- Entre junio y julio de 2026, CCR subió vídeos con título genérico ("STATE YEAR Cold Case Solved — Arrest Shocks Community"). Por año y estado, lo más probable es que cubran estos casos:
  - Helene Pruszynski: *Colorado's First Cold Case SOLVED After 40 Years Using Genetic Genealogy*.
  - Joyce McLain: *The Maine Cold Case That Was SOLVED 36 Years Later* (1980 + 36 = arresto de 2016).
  - Sarah Yarborough: *The First Cold Case Solved to Use Genetic Genealogy for New Leads (WASHINGTON 1991)*. Además hay un vídeo colaborativo "Cold Case Solved and Cold Case Reopened" de hace 3 semanas, *FEDERAL WAY 1991 … Justice for Sarah Yarborough*.
  - Irene Garza: *TEXAS 1960 Cold Case Solved*.
  - Jessica Baggen: *Alaska 1996*.
  - Marise Chiverella: *Pennsylvania's Oldest Cold Case Solved Through Genetic Genealogy*.

  **Por eso Pruszynski, McLain y Yarborough quedan fuera del top**, y Garza queda solo como reserva, a confirmar abriendo el vídeo de CCR.

**Competidor directo nuevo: Cold Case Redemption** (UCTIySjLA2XBB47jSZP4rdpQ). Usa el mismo formato de título y vídeos de 50 a 58 min, y en los últimos 2 meses ha cubierto casos de nuestra lista y del pool:

| Caso | Vistas en Cold Case Redemption |
|---|---|
| Medgar Evers | 242K |
| Irene Garza | 167K |
| Jane Britton | 138K |
| Mary Catherine Edwards | 60K |
| Christy Mirack ("PA 1992 … Famous DJ") | 66K |
| Joseph Newton Chandler | 37K, hace 2 semanas |
| Dana Ireland | 36K, hace 1 mes |

**Errores en el pool de partida** (ya corregidos en este informe):
- **Julie Ann Hanson** fue asesinada en **1972**, no en 1981. Además el acusado, Barry Lee Whelpley, **murió en la cárcel en 2024 antes del juicio**, así que no hay condena.
- **Roxanne Wood** es de **Niles, Michigan**, no de Indiana. El asesino es **Patrick Wayne Gilham**: se declaró *no contest* por asesinato en segundo grado y lo condenaron en 2022.
- **Mary Catherine Edwards** es un caso de **1995**, no de 1986.

**Señal de mercado.** Usé `search_videos` con el título exacto "Cold Case Solved", 12 meses, más de 15 min y más de 30K vistas: 157 vídeos. El formato "STATE YEAR Cold Case Solved" funciona, pero en cuanto un caso se hace viral salen entre 10 y 20 clones en pocas semanas (pasó con Yolanda Herrera, Roxanne Wood y Carla Walker). Los casos sin clones y con demanda probada son la oportunidad.

---

## 1. Método de puntuación (0–10 por factor)

| Factor | Qué mide | Peso |
|---|---|---|
| **D – Demanda** | Vistas del top 3 en YouTube (búsqueda por vistas) y si algún vídeo de los últimos 12 meses pasó de 100K | 30 % |
| **C – Competencia** | 10 = casi ningún vídeo largo en los últimos 12 meses; 0 = saturado (más de 15 clones o un competidor directo reciente) | 25 % |
| **H – Historia** | Giro, objeto clave, condena errónea o sospechoso equivocado, ángulo familiar, nombre famoso, material suficiente para 70 min | 25 % |
| **L – Claridad legal** | 10 = condena firme; 5 = identificado pero fallecido y sin cargos; ≤3 = acusado sin juicio o condena anulada | 10 % |
| **S – Seguridad** | 10 = víctima adulta sin violencia sexual explícita; ≤3 = víctima menor con abuso sexual | 10 % |

**Total** = 0,30·D + 0,25·C + 0,25·H + 0,10·L + 0,10·S, sobre 10.

**Veto:** con L ≤ 2 el caso no es apto para el formato "Solved", sea cual sea su total.

"Largos 12m" = número aproximado de vídeos de más de 8 min sobre el caso publicados en los últimos 12 meses (`youtube_search` con `upload_date=year`; la primera página da 20 resultados como máximo, de ahí el "20+").

---

## 2. Tabla de todos los candidatos (ordenada por total)

| # | Caso (estado, año) | Top 3 vídeos (vistas) | >100K en 12m | Largos 12m | D | C | H | L | S | **Total** | Estado |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 1 | **Sister Margaret Ann Pahl** (OH 1980) | WTOL11 153K (58 min, hace 5 meses) · Lights Out 141K (2h07) · WTOL11 51K | Sí (153K) | ~8, casi todos de la TV local WTOL; **0 clones faceless** | 7 | 9 | 10 | 8 | 8 | **8,45** | ✅ TOP |
| 2 | **Sophie Sergie** (AK 1993) | "don't look at me" 1,07M (recopilatorio) · Mysterious 5 425K (recopilatorio) · Murder With My Husband 229K (50 min); dedicado: Misery Machine 189K | No | ~8, todos con menos de 700 vistas | 8 | 8 | 8 | 10 | 8 | **8,20** | ✅ TOP |
| 3 | **Tina Faelz** (CA 1984) *(propuesta propia)* | A&E clip 2,14M (12 min) · Criminally Listed 73K (36 min) · Under The Ash Tree 7K | No | ~3, mínimos | 7 | 10 | 8 | 9 | 6 | **8,10** | ✅ TOP |
| 4 | **Roxanne Wood** (MI 1987) | 48 Hours 4,53M · 48 Hours maratón 601K (hace 1 mes) · podcast checo 90K | Sí (601K) | 20+ clones, todos por debajo de 2,2K | 10 | 4 | 9 | 9 | 8 | **7,95** | ✅ TOP |
| 5 | **Mary Catherine Edwards** (TX 1995) | 48 Hours 2,52M · ABC13 452K (hace 4 meses) · Othram Studios 254K (hace 3 días) | Sí (2) | 15+, incluido Cold Case Redemption (60K) | 10 | 3 | 9 | 10 | 8 | **7,80** | ✅ TOP (urgente) |
| — | Maria Ridulph (IL 1957) | Matt Orchard 3,15M (58 min) · 48 Hours 1,18M (hace 5 meses) · this is MONSTERS 127K | Sí | ~3 | 10 | 7 | 9 | **1** | 6 | 7,70 | ⛔ VETO: condena de McCullough anulada (2016), declarado inocente; el caso no está resuelto |
| 6 | Irene Garza (TX 1960) *(propia)* | Danelle Hallan 268K · Cold Case Redemption 167K (ago-2026) · A&E 50K | Sí | ~4 + probable vídeo de CCR | 8 | 3 | 10 | 10 | 7 | **7,35** | ⚠️ Probablemente cubierto por CCR ("TEXAS 1960"). Reserva |
| 7 | **Rick & Gail Brink** (MI 1987) *(propia)* | True Crime Fix 138K (hace 5 meses) · Crime Narrator 94K (hace 6 meses) · canal ucraniano 75K | Sí | 12+ | 8 | 3 | 9 | 10 | 9 | **7,30** | ✅ TOP |
| 8 | April Tinsley (IN 1988) | Kendall Rae 3,7M · Casefile 150K · A&E 62K | No (máx. 62K) | ~8 (Caught Years Later 11,8K) | 9 | 6 | 8 | 9 | 1 | **7,20** | ⚠️ Niña de 8 años con abuso sexual: prioridad baja |
| 9 | Michella Welch (WA 1986) | FilmRise 559K · Casefile 233K · DoctorOz 111K | Dudoso (Casefile, hace ~1 año) | ~7 | 8 | 6 | 8 | 9 | 3 | **7,10** | ⚠️ Niña de 12 años con abuso sexual: reserva |
| — | Sarah Yarborough (WA 1991) | 48 Hours 2,88M · 48 Hours 388K · Mollie Westbrook 75K | Sí | ~8 + colaboración CCR | 10 | 2 | 8 | 10 | 6 | 7,10 | ⛔ Ya cubierto (vídeo de "Cold Case Solved and Cold Case Reopened", hace 3 semanas) |
| 10 | **Jane Mixer** (MI 1969) *(propia)* | JR Erickson 9K (51 min) · Two Avg. Joes 1K · otros mínimos | No | ~6, todos por debajo de 150 vistas | 3 | 9 | 9 | 8 | 8 | **7,00** | ✅ TOP (apuesta de océano azul) |
| 11 | **Jane Britton** (MA 1969) *(propia)* | Crime Zone 349K · Cold Case Redemption 138K (hace 2 meses) · Time of Crime 49K | Sí | ~10 | 8 | 4 | 9 | 5 | 8 | **6,95** | ✅ TOP (con matiz legal) |
| 12 | **Medgar Evers** (MS 1963) *(propia)* | Cold Case Redemption 242K (hace 2 meses) · Smithsonian 89K (clip) · Casebook 99 20K | Sí | 15+ (clones del último mes) | 7 | 2 | 9 | 10 | 9 | **6,75** | ✅ TOP 10 (nombre famoso; competencia alta) |
| 13 | Helene Pruszynski (CO 1980) | heavy casefiles 379K · Scary Mysteries 119K · this is MONSTERS 117K | No (máx. 36K) | 18+ clones | 7 | 3 | 7 | 10 | 8 | **6,40** | ⛔ Probablemente cubierto por CCR |
| 14 | Christine Jessop (Canadá 1984) | Dr. Todd Grande 94K · Global News 44K · The Crime Reel 41K | No | ~4 | 5 | 7 | 9 | 5 | 2 | **6,20** | ❌ Fuera de EE. UU.; niña de 9 años con abuso sexual |
| 15 | **Rita Curran** (VT 1971) | True Crime Files 67K · NBC 62K (clip) · Gray Hughes 5K | No | ~8, todos por debajo de 450 vistas | 5 | 6 | 7 | 6 | 8 | **6,15** | ✅ TOP 10 (puesto 10) |
| 16 | Joyce McLain (ME 1980) | True Crime w/ Meghan 123K · Cold Case Files 67K (hace 5 meses) · LordanARTS 12K | No | ~6 | 6 | 3 | 8 | 9 | 6 | **6,05** | ⛔ Probablemente cubierto por CCR |
| 17 | Julie Ann Hanson (IL **1972**) | Faces of the Forgotten 464K (8 min) · Southern Girl 79K · Criminal Core 40K | No | ~2 | 6 | 9 | 6 | 2 | 2 | **5,95** | ⛔ VETO: acusado muerto antes del juicio |
| 18 | Stephanie Isaacson (NV 1989) | FilmRise 329K · Merc 97K (recopilatorio) · heavy casefiles 48K | No | ~6 | 7 | 6 | 6 | 5 | 3 | **5,90** | ❌ Niña de 14 años con abuso sexual; identificado y fallecido |
| 19 | Yolanda Herrera (TX 1981) | Root of Crime 275K (hace 1 mes) · colaboración 187K (hace 1 mes) · canal en español 10K | Sí (2) | 20+ en un mes | 10 | 1 | 6 | 3 | 8 | **5,85** | ⏸️ Esperar: acusado el 29-ago-2026, sin juicio |
| 20 | Buckskin Girl / Marcia King (OH 1981) | Danelle Hallan 282K · gabulosis 100K · Inside Edition 99K | No | ~5 | 6 | 7 | 5 | 2 | 8 | **5,80** | ❌ Solo se resolvió la identidad; el asesinato sigue sin resolver |

> Candidatos propios (6) salidos de `faceless_outliers_videos`, de "solved cold case DNA arrest decades later" y de `search_videos` con "Cold Case Solved": Tina Faelz, Irene Garza, Rick & Gail Brink, Jane Mixer, Jane Britton y Medgar Evers.
>
> Outliers que confirman la demanda del nicho:
> - Yolanda Herrera (Root of Crime): 270K con 4,2K suscriptores, outlier 3,6×.
> - "New York Oldest Cold Case Solved After 61 Years": 337K y 155K.
> - CCR "CALIFORNIA 1991": 462K, outlier 11×.
> - Bogle/Kalitzke: 220K, outlier 21×.
> - Jody Loomis (nuestro): 384K, outlier 19×.

---

## 3. TOP 10 recomendado para el próximo lote

### 1. Sister Margaret Ann Pahl — Ohio, 1980
**Por qué:** es la mejor relación entre demanda y competencia del análisis. Hay 153K recientes (documental de WTOL), pero **ningún clon faceless** con el formato "Cold Case Solved", y el giro es de primer nivel: el asesino era un sacerdote.
**Título:** `OHIO 1980 Cold Case Solved After 24 Years — Justice for Sister Margaret Ann Pahl`
**Brief:**
- **Víctima:** Sister Margaret Ann Pahl, 71 años, monja.
- **Lugar y fecha:** capilla/sacristía del Mercy Hospital, Toledo (Ohio), 5-abr-1980 (Sábado Santo). Estrangulada y apuñalada (unas 31 veces).
- **Condenado:** Father Gerald Robinson, capellán del hospital. Arrestado en abril de 2004 por la unidad de casos fríos de Lucas County; condenado el 11-may-2006, de 15 años a cadena perpetua. Murió en prisión en 2014.
- **Pruebas clave:** un abrecartas en forma de espada que encajaba con las heridas, y la transferencia de sangre en el mantel del altar (análisis de patrones, no ADN).
- **Resuelto:** 2004 (arresto) / 2006 (condena).
- **Para el guionista:** WTOL documenta dudas públicas sobre la condena y acusaciones de encubrimiento de la diócesis. Contarlas como "preguntas que persisten", atribuidas a su fuente; la condena se mantuvo en apelación. Evitar el detalle ritual gráfico.

### 2. Sophie Sergie — Alaska, 1993
**Por qué:** demanda probada (189K y 229K en vídeos dedicados, más de 1M en recopilatorios) y **ningún vídeo largo reciente con más de 700 vistas**. Condena firme y un giro fuerte: el asesino vivía en la residencia y acabó siendo enfermero en Maine.
**Título:** `ALASKA 1993 Cold Case Solved After 26 Years — Justice for Sophie Sergie`
**Brief:**
- **Víctima:** Sophie Sergie, 20 años, yup'ik de Pitkas Point.
- **Lugar y fecha:** encontrada en la bañera de un baño de la residencia Bartlett Hall, University of Alaska Fairbanks, 26-abr-1993.
- **Condenado:** Steven Harris Downs (18 años en 1993, residente de esa residencia). Identificado por genealogía genética (ADN de una tía en una base de datos). Arrestado en Auburn (Maine) en febrero de 2019; declarado culpable por un jurado en febrero de 2022; condenado el 27-sep-2022 a 75 años (67 por asesinato y 8 por agresión sexual).
- **Resuelto:** 2019.
- **Ángulo extra:** mujeres indígenas desaparecidas y asesinadas (MMIW).

### 3. Tina Faelz — California, 1984 *(propuesta propia)*
**Por qué:** es el mayor hueco del análisis. Un clip de A&E de 12 min tiene **2,14M**, pero en 12 meses solo hay 3 vídeos largos y mínimos. La historia es muy emocional (una chica que esquivaba a los acosadores, asesinada por un compañero de clase) y hay libro de referencia (*Murder in Pleasanton*, Joshua Suchon).
**Título:** `CALIFORNIA 1984 Cold Case Solved After 27 Years — Justice for Tina Faelz`
**Brief:**
- **Víctima:** Tina Marie Faelz, 14 años, Foothill High School.
- **Lugar y fecha:** apuñalada el 5-abr-1984 en el atajo de una alcantarilla bajo la I-680, Pleasanton (California).
- **Condenado:** Steven John Carlson, compañero de instituto (16 años entonces). Arrestado en 2011 (ADN en el bolso de Tina; verificar detalle). Pasó por el tribunal de menores y fue juzgado como adulto. Declarado culpable de asesinato en primer grado el 30-oct-2014; condenado en enero de 2015 a 26 años–perpetua, rebajados en apelación a 16–perpetua. En 2020 confesó por carta a la familia.
- **Resuelto:** 2011 (arresto) / 2014 (condena).
- **Seguridad:** víctima menor **sin** agresión sexual en el expediente público. Evitar el recuento gráfico de heridas.

### 4. Roxanne Wood — Michigan, 1987
**Por qué:** la demanda más alta del pool (48 Hours 4,5M; maratón de 601K hace un mes) y el mejor giro: el marido fue sospechoso durante 35 años. Está saturado de clones pequeños (más de 20), pero ninguno pasa de 2,2K. Un vídeo de 70 min bien producido puede ganarles. Combina bien con nuestro Angie Dodge, que comparte el maratón de 48 Hours.
**Título:** `MICHIGAN 1987 Cold Case Solved After 35 Years — Justice for Roxanne Wood`
**Brief:**
- **Víctima:** Roxanne Leigh Wood, 30 años.
- **Lugar y fecha:** asesinada en su casa de Niles Township (Berrien County, Michigan) la noche del 19 al 20-feb-1987, al volver antes de la bolera. Su marido, Terry Wood, la encontró y fue el principal sospechoso durante décadas.
- **Condenado:** Patrick Wayne Gilham, identificado por genealogía genética (con apoyo del programa de casos fríos de Western Michigan University) y confirmado con el ADN de una colilla que tiró. Se declaró *no contest* por asesinato en segundo grado; condenado en abril de 2022 a 23–50 años.
- **Resuelto:** 2022.

### 5. Mary Catherine Edwards — Texas, 1995
**Por qué:** demanda máxima (48 Hours 2,5M; ABC13 452K y Othram 254K en los últimos meses) y giro icónico: fue dama de honor en la boda de su asesino. La competencia es alta, incluido Cold Case Redemption, así que **conviene publicarlo ya**, mientras Othram vuelve a disparar las búsquedas.
**Título:** `TEXAS 1995 Cold Case Solved After 26 Years — Justice for Mary Catherine Edwards`
**Brief:**
- **Víctima:** Mary Catherine Edwards, 31 años, maestra de primaria.
- **Lugar y fecha:** sus padres la encontraron en la bañera de su casa de Beaumont (Texas), esposada, el 14-ene-1995.
- **Condenado:** Clayton Bernard Foreman (ella había sido dama de honor en su boda). Identificado en 2021 por genealogía genética y por el ADN de su basura en Ohio. Condenado en 2024 por asesinato capital a cadena perpetua; la condena fue confirmada en apelación (2026).
- **Resuelto:** 2021.

### 6. Rick & Gail Brink — Michigan, 1987 *(propuesta propia)*
**Por qué:** demanda reciente fuerte (138K y 94K en los últimos 6 meses), condena firme, víctimas adultas y un giro familiar muy potente: el asesino era el hermano de la novia. Hay competencia (más de 12 vídeos); el ángulo diferencial es el secreto familiar.
**Título:** `MICHIGAN 1987 Cold Case Solved After 26 Years — Justice for Rick & Gail Brink`
**Brief:**
- **Víctimas:** los recién casados Rick Brink y Gail Brink.
- **Lugar y fecha:** asesinados a tiros en su casa de Park Township / Holland (Ottawa County, Michigan) el 21-nov-1987, al volver de una boda.
- **Condenado:** Ryan Wyngarden, hermano de Gail. Arrestado en 2013; condenado en 2014 a cadena perpetua.
- **Resuelto:** 2013.
- **Pendiente de verificar:** la prueba exacta que lo vinculó (se cita una huella y la reevaluación de pruebas).

### 7. Jane Mixer — Michigan, 1969 *(propuesta propia, apuesta)*
**Por qué:** casi no hay competencia (ningún vídeo pasa de 9K) y la historia es excelente para 70 min. Se la atribuyeron al asesino en serie John Norman Collins ("Michigan Murders"), pero el ADN señaló a otro hombre... y también a un niño de 4 años, por contaminación del laboratorio. La demanda directa es baja, así que hay que **titular con el gancho**, no con el nombre.
**Título:** `MICHIGAN 1969 Cold Case Solved After 35 Years — Justice for Jane Mixer`
- Alternativa con más clic: `… — DNA Named Her Killer and a 4-Year-Old Boy`
**Brief:**
- **Víctima:** Jane Louise Mixer, 23 años, estudiante de Derecho en la University of Michigan.
- **Hallazgo:** su cuerpo apareció el 21-mar-1969 en Denton Cemetery (cerca de Ypsilanti) tras pedir que la llevaran en coche a casa desde un tablón de la universidad.
- **Condenado:** Gary Earl Leiterman (su ADN estaba en una base de datos por una falsificación de recetas). Identificado en 2004; condenado en julio de 2005 a cadena perpetua.
- **El giro:** la coincidencia con John Ruelas, que tenía 4 años en 1969, se explicó como contaminación. Aún alimenta un debate.
- **Resuelto:** 2004/2005.

### 8. Jane Britton — Massachusetts, 1969 *(propuesta propia)*
**Por qué:** demanda probada (Crime Zone 349K; Cold Case Redemption 138K hace 2 meses), una gran historia (Harvard, ocre rojo, un profesor sospechoso durante 50 años, el libro *We Keep the Dead Close*) y víctima adulta.
**Riesgo legal:** el asesino fue identificado, había muerto y nunca se le acusó.
**Título:** `MASSACHUSETTS 1969 Cold Case Solved After 49 Years — Justice for Jane Britton`
**Brief:**
- **Víctima:** Jane Sanders Britton, 23 años, doctoranda de Antropología en Harvard.
- **Lugar y fecha:** asesinada en su apartamento de Cambridge (Massachusetts) el 7-ene-1969.
- **Identificado:** Michael Sumpter, por ADN, en noviembre de 2018. Había muerto en 2001; la fiscalía de Middlesex cerró el caso sin juicio.
- **Para el guionista:** el profesor Karl Lamberg-Karlovsky fue objeto de rumores y quedó exculpado por el ADN. **No insinuar su culpa.**
- **Resuelto:** 2018.

### 9. Medgar Evers — Mississippi, 1963 *(propuesta propia)*
**Por qué:** el nombre más famoso del pool, con condena firme 31 años después y material de sobra (dos jurados bloqueados, la película *Ghosts of Mississippi*).
**Aviso:** Cold Case Redemption hizo 242K hace 2 meses y salieron más de 15 clones; además, el vídeo de derechos civiles de CCR (Dee/Moore) solo llegó a 2,6K. Conviene programarlo **más adelante en el lote**.
**Título:** `MISSISSIPPI 1963 Cold Case Solved After 31 Years — Justice for Medgar Evers`
**Brief:**
- **Víctima:** Medgar Evers, 37 años, secretario de campo de la NAACP.
- **Lugar y fecha:** asesinado de un disparo en la entrada de su casa en Jackson (Mississippi) el 12-jun-1963, delante de su mujer, Myrlie, y sus hijos.
- **Condenado:** Byron De La Beckwith. En 1964 hubo dos juicios con jurado bloqueado; el caso se reabrió con el fiscal Bobby DeLaughter y lo condenaron el 5-feb-1994 a cadena perpetua. Murió en 2001.
- **Resuelto:** 1994.

### 10. Rita Curran — Vermont, 1971
**Por qué:** competencia débil (los vídeos recientes no pasan de 450 vistas), historia sólida (el vecino de arriba, la coartada falsa de la esposa, el rumor sobre Ted Bundy, la colilla) y víctima adulta. La demanda es moderada (67K).
**Riesgo legal:** el asesino fue identificado, había muerto y nunca se le acusó. Narrar "según la policía de Burlington".
**Título:** `VERMONT 1971 Cold Case Solved After 51 Years — Justice for Rita Curran`
**Brief:**
- **Víctima:** Rita Curran, 24 años, maestra de segundo de primaria en Milton.
- **Lugar y fecha:** asesinada en su apartamento de Burlington (Vermont) la noche del 19 al 20-jul-1971.
- **Identificado:** William DeRoos, vecino de arriba, por ADN de una colilla de la escena, en febrero de 2023. Había muerto en 1986; nunca hubo cargos. Su esposa le había dado coartada en 1971.
- **Resuelto:** 2023.

**Reservas, por orden:**
1. Irene Garza (TX 1960), si se confirma que el "TEXAS 1960" de CCR es otro caso.
2. Michella Welch (WA 1986). Víctima menor: tratar sin detalle sexual.
3. April Tinsley (IN 1988). Víctima menor: tratar sin detalle sexual.
4. Yolanda Herrera (TX 1981), cuando haya veredicto.

---

## 4. Validación de los 20 casos ya elegidos

Datos medidos con `youtube_search` (últimos 12 meses) y outliers de NexLev. Donde dice "no medido" no hay dato propio.

| Caso | Diagnóstico | Recomendación |
|---|---|---|
| **Joseph Newton Chandler** | **El más débil.** Cold Case Redemption lo sacó hace 2 semanas (37K, 55 min) y han salido 5 clones en 14 días. La demanda máxima histórica es baja (Red Web 7K). No hay crimen ni justicia que contar (es un caso de identidad robada), así que encaja mal con "Justice for". | **Sustituir.** Por ejemplo, por Pahl o Faelz. |
| **Lori Ruff** | No medido. Tiene la misma debilidad estructural que Chandler: identidad resuelta, sin asesino ni condena. | Bajar de prioridad o sustituir. |
| **Boy in the Box** | No medido. La identidad se resolvió en 2022 (Joseph Augustus Zarelli), pero el asesinato **sigue sin resolver**. Es el mismo problema que Buckskin Girl. | Mantener solo si se enfoca en la identificación. Riesgo: título "Solved" sin culpable. |
| **Jeanne Childs** | Demanda casi nula: la búsqueda no devuelve ni un vídeo dedicado. Competencia cero, pero tampoco hay señal de interés. | Mantener como apuesta, pero no lanzarlo pronto. |
| **Dana Ireland** | Cold Case Redemption hace 1 mes (36K), más unos 8 clones. Historia excelente (3 condenas erróneas). | Mantener, con un ángulo diferencial claro: los 3 exonerados. No lanzarlo inmediatamente. |
| **Christy Mirack** | Cold Case Redemption lo cubrió hace 2 meses ("PA 1992 … The Killer Was a Famous DJ", 66K). | Mantener, con menor prioridad. |
| **Carla Walker** | Demanda enorme (Othram 1,62M hace 4 meses; Crimewatch Central 68K) pero **más de 18 clones** en el último año. | Mantener. Hay audiencia; diferenciarse con la duración y el ángulo "el sospechoso ya estaba en el expediente en 1974". |
| **Tent Girl** | Kallmekris 1,59M hace 10 meses, poca competencia faceless. El sospechoso (el marido, George Earl Taylor) murió sin cargos. | Mantener. Cuidar el lenguaje legal. |
| **Brown's Chicken** | this is MONSTERS 93K (hace 9 meses), Anna Templeton 22K; unos 12 vídeos pequeños. Condenas firmes. | Mantener. Es sólido. |
| **Angie Dodge** | 48 Hours (maratón con Roxanne Wood) 601K hace 1 mes. Demanda fuerte; giro de condena errónea (Christopher Tapp). | Mantener. Encadenarlo con Roxanne Wood. |
| **Jody Loomis** | Outlier de CrimeWatch con 384K (mayo de 2026): demanda probada, con un competidor reciente. | Mantener. |
| **Adam Walsh** | Probablemente es el "Florida 1981 Cold Case Solved" de Crimewatch Central (1M, julio de 2026): demanda altísima. **Riesgo legal:** Ottis Toole nunca fue acusado ni condenado; la policía lo declaró responsable en 2008. Víctima menor (6 años). | Mantener por demanda. Narrar estrictamente "según la policía de Hollywood (FL)". |
| **Golden State Killer, Green River Killer, Grim Sleeper, Boston Strangler (Mary Sullivan)** | No medidos uno a uno. Son megacasos con saturación altísima, pero la demanda es inagotable y nuestros 70 min superan los 40 de CCR. | Mantener. Repartirlos a lo largo del lote, sin juntar dos seguidos. |
| **Kristin Smart** | No medido. Condena de 2022 (Paul Flores). Muy saturado (podcast *Your Own Backyard*), pero con alta demanda. | Mantener. |
| **Martinko, Schnee/Oberholtzer, Canal Killer (Brosso/Bernas)** | No medidos uno a uno. Tienen condena y genealogía genética, encajan con el formato y no aparecieron entre los competidores directos. | Mantener. |

**Resumen de la validación:**
- **Sustituir:** Joseph Newton Chandler.
- **Revisar el enfoque o bajar la prioridad:** Lori Ruff, Boy in the Box y Jeanne Childs.
- **Retrasar en el calendario, porque Cold Case Redemption los hizo hace 1–2 meses:** Dana Ireland y Christy Mirack.

Riesgo estratégico: Cold Case Redemption está avanzando sobre el mismo catálogo. Hay que priorizar casos sin clones (Pahl, Sergie, Faelz, Mixer) antes de que también los cubra.

---

## Fuentes web (verificación legal)
- Roxanne Wood / Gilham: [WNDU](https://www.wndu.com/2022/04/25/patrick-gilham-sentenced-minimum-23-years-prison-murder-roxanne-wood), [CBS Detroit](https://www.cbsnews.com/detroit/news/man-pleads-no-contest-in-michigan-womans-1987-slaying/)
- Julie Ann Hanson / Whelpley fallecido antes del juicio: [CBS Chicago](https://www.cbsnews.com/chicago/news/chicago-naperville-barry-lee-whelpley-dead-julie-ann-hanson-murder-cold-case/), [Patch](https://patch.com/illinois/naperville/napervilles-notorious-murder-defendant-dies-inside-will-county-jail)
- Tina Faelz / Carlson: [CBS SF](https://www.cbsnews.com/sanfrancisco/news/man-convicted-in-1984-murder-of-tina-faelz-in-pleasanton-confesses-to-family-after-years-of-denials), [Pleasanton Weekly](https://www.pleasantonweekly.com/news/2020/10/23/36-years-later-former-classmate-confesses-to-murder-of-pleasantons-tina-faelz)
- Yolanda Herrera / Brower acusado en 2026: [KATV](https://katv.com/news/nation-world/murder-suspect-arrested-after-45-years-at-large-after-positive-dna-match)
- Sophie Sergie / Downs, 75 años: [Alaska's News Source](https://www.alaskasnewssource.com/2022/09/27/downs-sentenced-75-years-murder-assault-sophie-sergie), [Alaska Public](https://alaskapublic.org/news/2022-09-27/man-sentenced-to-75-years-in-prison-for-1993-murder-and-sexual-assault-of-sophie-sergie-at-uaf)

*Los datos de los briefs marcados "verificar", y las fechas que no vienen de las fuentes anteriores, salen de los metadatos de los vídeos o de conocimiento previo. El guionista debe confirmarlos con fuentes primarias antes de escribir.*
