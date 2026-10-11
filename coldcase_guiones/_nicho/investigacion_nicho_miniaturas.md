# Investigación del nicho: virales, metadatos, miniaturas y riesgo de las caras con IA

Canal de referencia: **Cold Case Reopened (CCR)**, `@ColdCaseReopened01`, `UCHF9iZLaa0d3kRYNKtXrlrw`.
Datos de NexLev consultados el **11 de octubre de 2026**. Las vistas son las de `youtube_video_details` de ese día. Los suscriptores, las vistas medias y el *outlier score* (vistas del vídeo ÷ vistas medias del canal) salen del índice `faceless_outliers_videos`. Cuando el índice no traía el outlier, lo calculé yo y lo marco con «calc.».

**Límites de esta investigación (léelos antes de usar las conclusiones):**
- La red bloquea `i.ytimg.com`, así que **no he visto ninguna miniatura**. `get_similar_thumbnails` solo devuelve metadatos (título, vistas, canal) y no describe la imagen.
- Lo único visual que he podido comprobar son los **primeros 20 segundos de 4 vídeos**, que analicé con `watch_youtube_video_and_ask` (Gemini). Eso es el vídeo, no la miniatura, y el juicio de Gemini sobre «real o IA» es orientativo, no pericial.
- La parte legal sale de 8 búsquedas web y de conocimiento general. **No es asesoramiento jurídico.** Si un caso concreto te preocupa, consúltalo con un abogado de medios en EE. UU.

---

## Resumen en 10 líneas

1. Los mayores virales recientes del nicho **no son de CCR**. Son de formatos de **ironía dramática** («X Has No Idea Police Already Matched Her DNA», «Killer Realizes He's Been Caught N Years Later»), con material de interrogatorio real: Red File tiene 14,9 M y TCD 1,28 M. También destacan los documentales emocionales de Othram Studios (1,6 M, 1,16 M y 1,13 M).
2. **El mismo caso puede dar 14,9 M o 18 K.** Sherri Rasmussen hizo 14,9 M en Red File («"Friendly" Cop Has No Idea…») y 18 K en CCR («Cold Case Solved After 23 Years The Killer Was a Detective»). Lo que mueve las vistas es el **ángulo** y el material real, no el caso.
3. La fórmula de CCR `STATE YEAR Cold Case Solved — Arrest Shocks Community` ya la copian por lo menos 3 canales: Crimewatch Central (1,13 M), Crime Narrator y Cold Case Files. El viral de CCR (462 K, Jaycee Dugard) usa esa fórmula corta. Sus vídeos largos «Justice for NAME» se quedan entre 2,7 K y 160 K.
4. **Descripciones:** las que mejor funcionan llevan un gancho en la primera línea, un resumen narrativo, **las fuentes con URL**, enlaces a otros vídeos, un aviso legal con **el estado judicial real** y de 3 a 10 hashtags.
5. **Etiquetas:** importan poco. CCR usa solo 2. Red File mete nombres de la competencia y de famosos que no tienen nada que ver con el vídeo: eso no hay que copiarlo, porque se arriesga a la política de spam y metadatos engañosos.
6. **Miniaturas de CCR:** es casi seguro que **no todas las caras son de las víctimas reales**. Oklahoma 1977 muestra 4 caras de niñas cuando hubo 3 víctimas. NexLev marca a CCR como contenido IA. En el vídeo de Jaycee, Gemini ve la foto de apertura «coloreada o restaurada con IA». En el de Carolina del Sur aparece una página de anuario con nombres (según Gemini, «Pat Burke» y «Aubrey Gentry») que no coinciden con las víctimas, Pamela Buckley y James Freund.
7. **Los titulares de CCR exageran el estado de los casos.** Oklahoma 1977 sigue **oficialmente abierto**: Hart fue absuelto en 1979. En Carolina del Sur 1976, lo que se resolvió en 2021 fue **la identidad de las víctimas**; según la cobertura de 2021, no se acusó a nadie. Los dos títulos dicen «Solved» («resuelto»).
8. **Riesgo para nosotros si copiamos eso:** política de contenido alterado o sintético, política de acoso (desde enero de 2024 prohíbe simular de forma realista a víctimas fallecidas), política de miniaturas y metadatos engañosos, quejas de privacidad por imagen generada con IA, difamación o falsa luz si sale una persona viva equivocada, y copyright de las fotos de archivo.
9. **Regla de oro para el canal:** solo fotos de archivo reales con crédito, o imágenes que no identifiquen a nadie. La IA, solo para lugares y objetos, y etiquetada. **Nunca** una cara hecha con IA presentada como víctima o sospechoso. Y lo que diga la miniatura tiene que coincidir con el estado judicial del caso.
10. **Lo que sí conviene copiar:** el ángulo de ironía o del objeto diminuto con «N Years Later», el banner con el año, las fuentes en la descripción, la línea de estado legal y el material real (interrogatorios, bodycam, ruedas de prensa).

---

# PARTE A: los virales del nicho y sus metadatos

## A.1 Tabla de los 15 vídeos analizados

| # | Canal (suscr.) | Vídeo | Vistas | Outlier | Duración | Publicado | Subnicho |
|---|---|---|---|---|---|---|---|
| 1 | Red File (101 K) | `rJYy0pHZDxA` | **14.930.598** | ~12,2 (calc., media 1,22 M) | 41:40 | 12-08-2026 | Interrogatorio + ADN (Rasmussen) |
| 2 | Othram Studios (60,6 K) | `jgCpG47IwuE` | 1.622.148 | 15,8 | 52:57 | 28-05-2026 | Resuelto por genealogía (Carla Walker) |
| 3 | TCD (80 K) | `P9E-AG52x4k` | 1.280.332 | 3,28 | 57:19 | 18-02-2026 | Interrogatorio + genealogía |
| 4 | Othram Studios | `c5b_pWreoQc` | 1.159.615 | 11,4 | 26:12 | 16-04-2026 | Identificación de una Jane Doe |
| 5 | Crimewatch Central (27 K) | `zeEbnTdxWGE` | 1.132.093 | ~10,7 (calc.) | 33:18 | 13-06-2026 | Caso famoso (Adam Walsh) |
| 6 | Othram Studios | `HNVA9dOvrQ4` | 1.125.436 | ~11,3 (calc.) | 24:25 | 26-03-2026 | Identificación de una Jane Doe |
| 7 | Nexcrime (5,47 K) | `sk5agcwXZBE` | 1.026.084 | 8,84 | 20:11 | 01-05-2026 | «Killer realizes» (Martinko) |
| 8 | DT Scofield (2,27 K) | `yiYu-i-4G9c` | 780.858 | 11,3 | 14:52 | 18-07-2026 | Bodycam: un control de tráfico destapa un caso frío |
| 9 | Interrogation Core (181 K) | `Fr4v0U03ieA` | 662.630 | 1,67 | 69:39 | 02-02-2026 | Interrogatorio a un asesino en serie |
| 10 | Cold Case Reopened (17,2 K) | `iz80aDNZ0Ig` | 462.609 | 10,95 | 22:59 | 28-05-2026 | Secuestro resuelto (Jaycee Dugard) |
| 11 | Crime Narrator (26,9 K) | `kLZ9iZ1ajl8` | 459.061 | 14,3 | 24:45 | 27-03-2026 | El caso más antiguo resuelto por ADN (Candy Rogers) |
| 12 | CrimeWatch (5,85 K) | `xSumtxrxZCw` | 384.026 | 18,9 | 19:48 | 05-05-2026 | El objeto diminuto (la bota de Jody Loomis) |
| 13 | Root of Crime (4,21 K) | `55gSeWBgWJk` | 275.127 | 3,64 | 20:42 | 29-08-2026 | Giro: «Never a Suspect» (Yolanda Herrera) |
| 14 | Crime Files Unlocked (4,63 K) | `D9Unqw1oivI` | 219.974 | 20,8 | 12:11 | 26-04-2026 | El objeto diminuto (Bogle y Kalitzke) |
| 15 | Cold Case Reopened | `N7gTtuW-kQE` | 153.185 | ~3,6 (calc.) | 47:04 | 29-08-2026 | Formato largo de CCR (Lyon Sisters) |

Otros datos útiles de NexLev que no están en la tabla:
- Red File también tiene `_TcTHe0JHFI`, «Killer Realizes DNA Finally Caught Him After 23 Years», con 2,35 M.
- Othram tiene `2iYYx8E4kWo`, «For 37 Years, She Was Only "Baby Girl". Until Now.», con 635 K, y `WklFZaQZl9g` con 404 K.
- Crimewatch Central tiene `oNm_gJxwheI`, «New York Oldest Cold Case Was Just SOLVED After 61 Years», con 337 K. CrimeWatch tiene un vídeo con el mismo título exacto (`lxMbZoTeK7U`, 155 K).
- NexLev marca como contenido IA (`isAiContent: true`) a **CCR (iz80aDNZ0Ig)** y a **Crime Files Unlocked**. Al resto no.

**El dato más revelador del canal CCR** (lista «popular», 64 vídeos, 17,2 K suscriptores):
- Sus 3 vídeos más vistos usan la fórmula corta «— Arrest Shocks Community» y duran entre 17 y 27 minutos: Jaycee 462 K, Alabama 1999 269 K y California 1973 189 K.
- Los largos de septiembre, de 41 a 49 minutos y con «Justice for…», hacen entre 67 K y 160 K cuando el caso es una familia o un caso famoso, y entre 2,6 K y 45 K en los demás.
- CCR **volvió a publicar el caso Jaycee** en formato largo (`cFT-d8rkqHI`): **2,7 K**, frente a los 462 K del original.
- Sherri Rasmussen en CCR (`IHlrvs5VjqU`) tiene **18 K**. El mismo caso en Red File tiene **14,9 M**.

## A.2 Ficha de cada vídeo (título, fórmula, descripción completa, hashtags, etiquetas y miniatura)

### 1. Red File: `rJYy0pHZDxA` (14,9 M)
- **Título:** `"Friendly" Cop Has No Idea Police Already Matched Her DNA After 23 Years`
- **Fórmula:** `"[Adjetivo irónico]" [Rol] Has No Idea [la policía ya sabe X] After N Years`. Es ironía dramática: el espectador sabe algo que el protagonista no sabe.
- **Categoría:** Entertainment · 127.837 likes
- **Miniatura:** https://i.ytimg.com/vi/rJYy0pHZDxA/maxresdefault.jpg (YouTube la sirve como `.webp`)
- **Etiquetas (25):** Killer Cop Realizes Police Just Connected Her DNA to a 1986 Murder, lindsay clancy case, lindsey clancy, lawyer you know, lindsay clancy, true crime daily, surviving the survivor, unsolved mysteries, christina randall, murders documentary, elisa true crime, annie elise, joe budden, lindsay clancy trial, partners in crime, crimenes imperfectos, red taylor swift, law by mike, law and order, the interview room, dr insanity, brian entin, criminal network, crime, red file. **Ojo:** mete nombres de competidores y de famosos que no tienen relación con el vídeo. No hay que copiarlo.
- **Hashtags:** #TrueCrime #StephanieLazarus #SherriRasmussen #LAPD #ColdCase #DNAEvidence #PoliceInterrogation #MurderCase #TrueCrimeCommunity
- **Descripción completa:**
```
😱 Killer Cop Realizes Police Just Connected Her DNA to a 1986 Murder 😱

For 23 years, Stephanie Lazarus worked as an LAPD detective.

She questioned suspects.
Investigated crimes.
And built a career on the other side of the interrogation table.

But there was one thing her own department didn't know.

DNA from a murder committed decades earlier was about to point directly at her.

And when detectives invited Stephanie into an interview room...

She had no idea they already knew.

Here's the chilling case of Sherri Rasmussen.

💀 A Murder Staged as a Burglary

On February 24, 1986, 29-year-old Sherri Rasmussen was found dead inside her Van Nuys home.

She had been shot 3 times after a violent struggle.

The house appeared disturbed.

Electronics looked like they had been targeted.

And Sherri's BMW was missing.

At first, investigators believed a burglary had gone horribly wrong.

🧬 One Bite Mark Changed Everything

During the struggle, Sherri had suffered a deep human bite wound on her arm.

Investigators collected a swab.

But DNA technology in 1986 couldn't reveal what detectives needed.

So the evidence sat untouched for decades.

Until science finally caught up.

😨 The DNA Pointed to a Police Officer

In 2009, investigators tested the old bite-mark evidence.

The profile indicated something shocking.

The killer was a woman.

And detectives soon focused on one of their own:

LAPD detective Stephanie Lazarus.

💔 A Relationship From the Past

Stephanie had previously been involved with Sherri's husband, John Ruetten.

Witnesses described tension after John became engaged to Sherri.

Investigators also discovered Stephanie had owned a .38-caliber revolver — the same caliber used to kill Sherri.

Just 13 days after the murder, Stephanie reported the gun stolen.

🚔 Her Own Department Secretly Followed Her

Detectives couldn't simply ask a fellow officer for DNA.

So they placed Stephanie under surveillance.

They waited until she discarded a cup and straw...

Then secretly tested them.

The result matched DNA from Sherri's bite wound and evidence beneath her fingernails.

Detectives already had their answer before Stephanie ever entered the interrogation room.

🧠 She Thought It Was Just a Conversation

Detectives slowly tightened the questions while pretending they were still trying to understand what happened.

⛓️ She Never Walked Out

The interview appeared to end normally.

Stephanie stood up and left the room.

But officers were waiting in the hallway.

She was arrested before she could leave the building.

⚖️ Justice After 23 Years

In 3/2012, Stephanie Lazarus was convicted of 1st-degree murder.
She was sentenced to 27 years to life.

More than a decade later, during a 2023 parole hearing, she finally admitted killing Sherri.

One tiny DNA sample that had been sitting in evidence while the killer worked inside the same police department.

🔥 WATCH NOW 🔥

Genius Detective Tricks Guilty Suspect Into Confession
https://youtu.be/IQxrxZFNAc0?si=4WwvGjZOl27rpgGa

Cold Cases Solved DECADES Later | Episode 1
https://youtu.be/9J34AE3drlM?si=9eM4pZuQCqOODydb

"Friendly" Wife Has No Idea Police Are About To Arrest Her For Murder
https://youtu.be/V41lG3kxbwU?si=EfphDScLzPVqGe2T

Disclaimer:

This video was independently researched, written, narrated, edited, and produced as an original documentary work. Any public-record, evidentiary, archival, or third-party materials included in this video were independently sourced from lawful and authoritative sources and are presented with original commentary, analysis, editorial context, and narrative structure.

This video is provided for documentary, commentary, educational, and informational purposes. The individuals shown or discussed are presumed innocent unless and until proven guilty in a court of law, unless stated otherwise based on official case outcomes. Nothing in this video should be interpreted as legal advice, and this presentation may not include every fact, allegation, procedural development, or final disposition in a case.

To the extent copyrighted material appears in this video, it is used in a transformative manner for purposes such as criticism, comment, news reporting, research, and documentary analysis, and may rely on applicable copyright exceptions, including fair use under Section 107 of the U.S. Copyright Act, where applicable.

All original elements of this video—including its script, narration, edit, graphics, selection, arrangement, and overall presentation—are original creative works protected under applicable copyright law. Any included public-record, archival, or third-party materials remain subject to their respective rights and sources, where applicable. Unauthorized copying, downloading for reupload, redistribution, or reuse of this video's original creative elements is prohibited without prior written permission.

#TrueCrime #StephanieLazarus #SherriRasmussen #LAPD #ColdCase #DNAEvidence #PoliceInterrogation #MurderCase #TrueCrimeCommunity
```

### 2. Othram Studios: `jgCpG47IwuE` (1,62 M)
- **Título:** `Her Killer Hid in Plain Sight for 47 Years`
- **Fórmula:** `[Pronombre de la víctima] Killer Hid in Plain Sight for N Years`. Sin nombre, sin estado y sin año: todo es hueco de curiosidad.
- **Categoría:** Entertainment · 31.459 likes · **Etiquetas:** ninguna
- **Miniatura:** https://i.ytimg.com/vi/jgCpG47IwuE/maxresdefault.jpg
- **Hashtags:** #TrueCrime #ColdCase #DNA
- **Descripción completa:**
```
Trace Identity: Season 1, Episode 4.

In 1974, 17-year-old Carla Walker was kidnapped from a Fort Worth bowling alley parking lot and murdered. Despite decades of investigation, the case remained unsolved for nearly half a century.

In this episode of Trace Identity, investigators, forensic scientists, prosecutors, and the family and friends closest to the case explain how advances in DNA and forensic genetic genealogy finally identified Carla Walker's killer and helped deliver answers after generations of uncertainty.

But the impact of the case extended far beyond a single investigation.

The Carla Walker case became one of the first major forensic genetic genealogy cases in Texas to face intense courtroom scrutiny, helping establish the credibility of the science in court. The case would later inspire the introduction of the Carla Walker Act during National Police Week, cementing its lasting impact on forensic investigations and the pursuit of justice for violent crimes.

Produced, filmed, and directed by Chris Rowe
Produced and edited by Vinny Roccanova
Executive Producer: David Mittelman
Additional editing by Ray Tiburzi and Carissa Jimenez
Reenactment Actress: Georgia Rowe
Reenactment Actor: Sean Rowe

#TrueCrime #ColdCase #DNA
```
> Nota: Othram **acredita a los actores de la recreación** en la descripción. Es el estándar de transparencia que deberíamos seguir: si algo no es real, se dice. Además, nuestro guion 05 (Carla Walker, Texas 1974) compite directamente con este vídeo de 1,6 M.

### 3. TCD: `P9E-AG52x4k` (1,28 M)
- **Título:** `57 Year Old Man Has No Idea His DNA Just Connected Him to A 1985 Murder...`
- **Fórmula:** `[Edad] Year Old [Rol] Has No Idea His DNA Just Connected Him to A [Año] Murder...`. Ironía dramática, con puntos suspensivos al final.
- **Categoría:** Entertainment · 16.984 likes
- **Miniatura:** https://i.ytimg.com/vi/P9E-AG52x4k/maxresdefault.jpg
- **Etiquetas:** interrogation, investigation, cold cases solved, TCD
- **Hashtags:** #TCD #truecrimedocumentary (están al principio de la descripción)
- **Descripción completa:**
```
#TCD #truecrimedocumentary 
In 1985, 23-year-old Tonya McKinley was found strangled and sexually assaulted on the side of a Pensacola road on New Year's Day. For 35 years, her killer walked free — until one discarded cigarette changed everything. Using genetic genealogy and familial DNA testing, detectives built a family tree from scratch, tracked down 57-year-old Daniel Wells, and confirmed he was the killer. Just two weeks after his arrest, before he could ever face a judge, Wells was found dead in his jail cell. Justice was finally within reach — then gone in an instant.
In this video, we break down the full story of one of Pensacola's most haunting cold cases — how a mother was murdered, how her killer hid in plain sight for decades, and how a single cigarette butt brought the truth to light.

CONTACT US:
 Video submissions? Sponsorships? Collabs? Business inquires? 
Email us at tcdtruecrime@gmail.com. 

Disclaimer:
This video was created for educational and informational purposes only. The content is presented to provide genuine footage of real incidents in order to promote transparency, public awareness, and government accountability. All material is fact-checked and sourced from authoritative, credible, and publicly available records.
The individuals appearing in this video are legally presumed innocent unless proven guilty in a court of law. Nothing presented in this video should be interpreted as legal counsel or legal advice. The analysis and commentary offered represents personal observations only and may not reflect all circumstances, details, or final charges in each case.
All footage and materials featured in this video were lawfully obtained through public records and are available to the general public. This content is produced strictly for journalistic, documentary, and educational purposes and is protected under the Fair Use doctrine as outlined in Section 107 of the U.S. Copyright Act.
```

### 4. Othram Studios: `c5b_pWreoQc` (1,16 M)
- **Título:** `She Left Them Behind... 60 Years Later, DNA Revealed Why`
- **Fórmula:** `[Acción misteriosa]... N Years Later, DNA Revealed Why`
- **Categoría:** Entertainment · 20.209 likes
- **Miniatura:** https://i.ytimg.com/vi/c5b_pWreoQc/maxresdefault.jpg
- **Etiquetas:** Jane Doe, True Crime, Forensic Genetic Genealogy, Cold Case, DNA solves
- **Hashtags:** #TrueCrime #ColdCase #DNA
- **Descripción completa:**
```
Trace Identity: Season 1, Episode 2.

Separated for 60 years.
No contact. No answers.
Until a cold case changed everything.

In 1971, a young woman was found barely alive in a quiet Maryland field. She had no identification, no witnesses, and no way to tell her story. She would later die, and for decades, her case went cold.

For 54 years, her identity remained unknown, until advances in forensic genetic genealogy and a determined investigation finally uncovered the truth.

What investigators discovered went beyond a murder case. It revealed a family torn apart for decades and reunited two siblings who had not seen each other in 60 years.

This is Episode 2 of Trace Identity, a new series from Othram Studios exploring how DNA can transform uncertainty into identity and change lives in ways no one expects.

Produced, filmed, and directed by Chris Rowe
Produced and edited by Vinny Roccanova
Executive Producer: David Mittelman

#TrueCrime #ColdCase #DNA
```

### 5. Crimewatch Central: `zeEbnTdxWGE` (1,13 M)
- **Título:** `Florida 1981 Cold Case Solved — Arrest Shocks Community`
- **Fórmula:** `[Estado] [Año] Cold Case Solved — Arrest Shocks Community`. Es la misma plantilla que CCR. **Ojo:** en el caso Adam Walsh nunca hubo detención; la policía nombró a Ottis Toole en 2008, cuando ya había muerto. El título es engañoso, aunque la descripción lo corrige.
- **Categoría:** People & Blogs · 40.238 likes
- **Miniatura:** https://i.ytimg.com/vi/zeEbnTdxWGE/maxresdefault.jpg
- **Etiquetas (22):** Adam Walsh, Adam Walsh murder, Adam Walsh case, Adam Walsh 1981, Adam Walsh cold case, Adam Walsh solved, Ottis Toole, Ottis Toole confession, Jeffrey Dahmer, did Dahmer kill Adam Walsh, John Walsh, John Walsh son murdered, cold case solved, true crime documentary, murder investigation, cold case files, missing children 1980s, Florida 1981 true crime, CrimewatchCentral, cold case documentary 2024, Code Adam origin, deathbed confession murder
- **Hashtags (23):** #TrueCrime #ColdCase #MurderInvestigation #AdamWalsh #ColdCaseFiles #ColdCaseSolved #CrimewatchCentral #SolvingCrime #ForensicScience #DNAEvidence #TrueCrimeDocumentary #CrimeAnalysis #RealCrime #TrueCrimeCommunity #ColdCaseInvestigation #CrimeAwareness #JohnWalsh #Justice #MissingChildren #Florida1981 #DetailedAnalysis #OttisToole #truecrimeinvestigation
- **Descripción completa:**
```
On July 27th, 1981, Reve Walsh took her six-year-old son to a Sears in Hollywood, Florida. She left him for fifteen minutes. He never came home. Four suspects. One killer. Twenty-seven years of nothing.

In 2008, a cold case detective reviewing 98 never-developed crime scene photographs closed the most mishandled murder investigation in American history through solving crime.

SOURCES & FURTHER READING:
All details are drawn from verified public records and mainstream reporting. Key sources:

NBC News — 2008 case closure press conference and AP file reporting (https://www.nbcnews.com/id/wbna28257294);
CBS News Miami — 40th anniversary murder investigation retrospective (https://cbsnews.com/miami/news/adam-walsh-case-40-years-later);
ABC News Primetime — 2007 cold case files investigative broadcast on DNA evidence (https://abcnews.com/Primetime/story?id=3473665&page=1);
ABC News — John and Reve Walsh re-live the full investigation (https://abcnews.com/US/adam-walsh-murder-john-reve-walsh-live-investigation/story?id=13037931);
Wikipedia case summary — consolidated court records and verified reporting (https://en.wikipedia.org/wiki/Adam_Walsh_child_murder_case).

▶ More Solved Cold Cases on Crimewatch Central:
Washington 1987 Cold Case  Solved —  The First Ever Cold Case Solved by a Stranger's Family Tree
https://youtu.be/Pg2q3Shimts
Texas 1974 Cold Case Solved — Her Killer Hid In Plain Sight For 47 Years
https://youtu.be/NscR9miuvIs

🕵️‍♂️ Welcome to Crimewatch Central — where no case stays cold forever. New here? Hit subscribe and turn on notifications 🔔.

⚠️ DISCLAIMER:
Created for educational and informational purposes only, based on publicly available information and verified public records. Ottis Elwood Toole was officially named the perpetrator of Adam Walsh murder on December 16th, 2008, by Hollywood Police Chief Chad Wagner following an independent cold case review of the files. No criminal charges were ever filed in connection with this murder investigation. All details drawn from authenticated public sources including Hollywood Police Department records, Broward County Medical Examiner findings, and mainstream media reporting. Viewer discretion is advised.

#TrueCrime #ColdCase #MurderInvestigation #AdamWalsh #ColdCaseFiles #ColdCaseSolved #CrimewatchCentral #SolvingCrime #ForensicScience #DNAEvidence #TrueCrimeDocumentary #CrimeAnalysis #RealCrime #TrueCrimeCommunity #ColdCaseInvestigation #CrimeAwareness #JohnWalsh #Justice #MissingChildren #Florida1981 #DetailedAnalysis #OttisToole #truecrimeinvestigation
```

### 6. Othram Studios: `HNVA9dOvrQ4` (1,13 M)
- **Título:** `The 14 Year Old Girl Who Finally Got To Go Home`
- **Fórmula:** `The [Edad] Year Old [Persona] Who Finally [Final emocional]`. Es un título de identificación, con tono de duelo y alivio.
- **Categoría:** Entertainment · 18.995 likes
- **Miniatura:** https://i.ytimg.com/vi/HNVA9dOvrQ4/maxresdefault.jpg
- **Etiquetas:** #truecrime, #JaneDoe, #Othram, #DNA, #ColdCase (las pone como etiquetas con almohadilla)
- **Hashtags:** #TrueCrime #ColdCase #DNA
- **Descripción completa:**
```
Trace Identity: Season 1, Episode 1.

She was 14 years old. For more than four decades, her identity was unknown.

In 1980, a young girl was found murdered along a rural road in Texas. Despite extensive investigation, she remained unidentified and became known as Walker County Jane Doe.

This case remained unresolved for over 40 years, until advances in forensic genetic genealogy made an identification possible. Using a process that enables investigators to identify individuals from DNA, even when no known reference exists, investigators were able to restore her identity and move the case forward.

Produced by Othram Studios, this is the first episode of Trace Identity,  a series exploring how biological evidence and disciplined analysis can transform uncertainty into identification.

Produced, filmed, and directed by Chris Rowe
Edited by Vinny Roccanova
Executive Producer: David Mittelman

#TrueCrime #ColdCase #DNA
```

### 7. Nexcrime: `sk5agcwXZBE` (1,03 M)
- **Título:** `Killer Realizes He's Been Caught 40 Years Later`
- **Fórmula:** `Killer Realizes He's Been Caught N Years Later`. Es una plantilla clonada en varios canales: DT Scofield (14 años), Interrogation Core (30) y Red File (23).
- **Categoría:** Entertainment · 17.334 likes · **Etiquetas:** ninguna
- **Miniatura:** https://i.ytimg.com/vi/sk5agcwXZBE/maxresdefault.jpg (YouTube la sirve como `.webp`)
- **Hashtags (15):** #TrueCrime #ColdCase #MichelleMartinko #JusticeServed #DNAEvidence #ColdCaseSolved #TrueCrimeDocumentary #CrimeStory #ForensicScience #UnsolvedMystery #MurderCase #RealCrime #Investigation #CedarRapids #IowaCrime
- **Descripción completa:**
```
On December 19, 1979, 18-year-old Michelle Martinko was found stabbed to death in her car in the parking lot of Westdale Mall in Cedar Rapids, Iowa, after a Christmas shopping trip. The case went unsolved for nearly 40 years until advances in DNA and genetic genealogy identified the killer, leading to the arrest and conviction of Jerry Lynn Burns, bringing long-awaited justice to one of Iowa's most infamous cold cases.


⚠️ Viewer Discretion Advised: This video contains  discussion of a real violent crime and may be disturbing to some viewers.

📌 Disclaimer: This content is intended strictly for educational, documentary, and informational purposes. All information is based on publicly available reports, court records, and other lawful public sources. It does not promote, glorify, or condone violence or criminal behavior. Any materials used are obtained through public records requests or other publicly accessible sources. This presentation is transformative in nature and is provided under fair use (Section 107 of the U.S. Copyright Act) for purposes such as education, commentary, journalism, and research.



#TrueCrime #ColdCase #MichelleMartinko #JusticeServed #DNAEvidence #ColdCaseSolved #TrueCrimeDocumentary #CrimeStory #ForensicScience #UnsolvedMystery #MurderCase #RealCrime #Investigation #CedarRapids #IowaCrime
```
> Nota: es el mismo caso que nuestro guion 01 (Martinko). Este vídeo dura 20 minutos, usa material real del interrogatorio de Burns y supera el millón de vistas. Lo que deberíamos tomar de él es **el ángulo del interrogatorio**.

### 8. DT Scofield: `yiYu-i-4G9c` (781 K)
- **Título:** `Killer Realizes He's Been Caught 14 Years Later`
- **Fórmula:** la misma que Nexcrime, pero con material de bodycam real (un control de tráfico en 2024).
- **Categoría:** People & Blogs · 7.530 likes · **Etiquetas:** ninguna · **Hashtags:** ninguno
- **Miniatura:** https://i.ytimg.com/vi/yiYu-i-4G9c/maxresdefault.jpg
- **Descripción completa:**
```
On January 17th, 2024, a police officer spotted a pickup truck running a red light and initiated a routine traffic stop. At first, it seemed like nothing more than a simple traffic violation. But within minutes, deputies would uncover evidence connected to a cold case murder that had remained unsolved since 2010.

This video was made for educational purposes only.

The video is presented to provide genuine footage of police incidents to promote transparency in government while providing educational, informative and newsworthy content allowing viewers to examine and assess public safety material. This is a fact-checked documentary using authoritative sources.

All content featured on this channel is sourced from public records requests and other publicly accessible materials. The use of this content complies with fair use under Section 107 of the U.S. Copyright Act, as it is transformative in nature and presented for educational, documentary, and journalistic purposes — consistent with other verified channels such as Explore With Us, Dr Insanity, and Code Blue Cam.

This channel adheres to YouTube's violent or graphic content policies by censoring or blurring any potentially disturbing imagery. The intention is not to shock or disgust viewers, but to inform and analyze.

All individuals depicted are presumed innocent until proven guilty in a court of law. The outcomes of some incidents may be unknown or pending at the time of publication. This channel is not affiliated with, endorsed by, or representative of any law-enforcement agency.

Nothing in these videos should be interpreted as legal advice or guidance on how to interact with law enforcement. Our purpose is to promote transparency and foster informed public dialogue through the presentation of real-world law-enforcement encounters.
```

### 9. Interrogation Core: `Fr4v0U03ieA` (663 K)
- **Título:** `Serial Killer Realizes He's Been Caught 30 Years Later`
- **Fórmula:** la de «Killer Realizes», con el rol agravado («Serial Killer»).
- **Categoría:** People & Blogs · 8.075 likes
- **Miniatura:** https://i.ytimg.com/vi/Fr4v0U03ieA/maxresdefault.jpg
- **Etiquetas (17):** jcs inspired, interrogation, interrogation analysis, interrogation jcs inspired, interrogation jcs style, interrogation ewu, interrogation psychology, interrogation psychology jcs inspired, new interrogations, interrogation breakdown, police interrogation psychology, criminal psychology interrogation, police interrogation 2026, killer realizes he's been caught years later, cold case solved, cold case interrogation, serial killer interrogation
- **Hashtags:** #interrogation #interrogationpsychology
- **Descripción completa:**
```
In the early 1990s, a disturbing pattern began to surface in a small Midwestern town—one that would take years to fully grasp. It started quietly, when police began discovering bodies. One after another. Over time, four adult women were found dead. Their remains had been discarded like refuse—hidden inside containers, wooden boxes, dumpsters. One was even discovered stuffed inside a trash bin.

Most of the victims had been strangled or smothered. But what unsettled investigators most wasn't just how they died—it was what was missing. There were no witnesses. No weapons. No fingerprints. Not a single usable clue. The only evidence recovered was DNA. But at the time, forensic technology wasn't advanced enough to link it to anyone. And so the cases went cold, leaving investigators with nothing but unanswered questions.

#interrogation #interrogationpsychology
```

### 10. Cold Case Reopened: `iz80aDNZ0Ig` (463 K): el viral de CCR
- **Título:** `CALIFORNIA 1991 Cold Case Solved — Arrest Shocks Community`
- **Fórmula:** `[ESTADO] [AÑO] Cold Case Solved — Arrest Shocks Community`, sin nombre de la víctima.
- **Categoría:** People & Blogs · 4.047 likes · **NexLev: `isAiContent: true`**
- **Miniatura:** https://i.ytimg.com/vi/iz80aDNZ0Ig/maxresdefault.jpg (YouTube la sirve como `.webp`)
- **Etiquetas:** Cold Case Files, Cold Case
- **Hashtags:** **ninguno** en este vídeo. En los vídeos largos posteriores sí pone `#ColdCaseFiles #ColdCase`.
- **Descripción completa:**
```
CALIFORNIA 1991 Cold Case Solved — Arrest Shocks Community

Eighteen years ago, an 11yearold girl in Meyers, California disappeared while walking to her school bus stop just a few dozen meters from her house. She was abducted right in front of her stepfather, leaving her family devastated and the entire South Lake Tahoe community in shock. Law enforcement searched everywhere but found no reliable clues leading to the kidnapper—while the perpetrator, a sex offender on federal parole for kidnapping and rape, kept Jaycee hidden in his backyard. He was never discovered despite his parole officer checking his house 60 times over the following years. 

1. The Bizarre 1991 Abduction of Jaycee Lee Dugard in Calif. Ends With Her Return
A detailed Washington Post narrative published days after the 2009 discovery, reconstructing the sequence of events from Dugard's 1991 abduction to her rescue. The report questions why parole officers visiting Garrido's home for years never detected the hidden captive.
Source: https://www.washingtonpost.com/wp-dyn/content/article/2009/08/28/AR2009082803849.html

2. $20 Million Settlement for California Captive Approved
NBC News coverage of the California legislature's unanimous approval of a $20 million state settlement with Jaycee Dugard and her two daughters. The settlement acknowledged repeated failures by the state Department of Corrections and Rehabilitation in supervising convicted sex offender Phillip Garrido, who had been on parole since 1999.
Source: https://www.nbcnews.com/id/wbna38041109

3. Jaycee Lee Dugard Expresses Relief After Phillip and Nancy Garrido Plead Guilty
CBS News report on the surprise April 2011 guilty pleas entered by both Phillip and Nancy Garrido. Phillip accepted a deal carrying more than 430 years to life in prison; Nancy received 36 years to life. The plea spared Dugard and her daughters from having to testify at trial.
Source: https://www.cbsnews.com/news/jaycee-lee-dugard-expresses-relief-after-philip-and-nancy-garrido-plead-guilty/

4. Dugard Details Ordeal; Kidnappers Sentenced
NBC News court report from June 2, 2011 covering the El Dorado County Superior Court sentencing hearing. Judge Douglas Phimister imposed the maximum sentence on Phillip Garrido, calling his conduct a modern form of slavery. Dugard's victim impact statement, read by her mother, declared that her abductors had stolen her life.
Source: https://www.nbcnews.com/id/wbna43253444

5. Court Rejects Lawsuit by Kidnapping Survivor Jaycee Dugard
NBC News report on the 9th U.S. Circuit Court of Appeals' 2016 ruling, which rejected Dugard's federal lawsuit alleging that parole officials should have revoked Phillip Garrido's parole before he kidnapped her. The court ruled 2-1 that federal authorities had no duty to protect members of the general public from Garrido.
Source: https://www.nbcnews.com/news/us-news/court-rejects-lawsuit-kidnapping-survivor-jaycee-dugard-n539526
```

### 11. Crime Narrator: `kLZ9iZ1ajl8` (459 K)
- **Título:** `The Oldest Cold Case Solved by a Single Drop of DNA`
- **Fórmula:** `The [Superlativo] Cold Case Solved by a Single [Objeto diminuto]`
- **Categoría:** Entertainment · 15.058 likes
- **Miniatura:** https://i.ytimg.com/vi/kLZ9iZ1ajl8/maxresdefault.jpg
- **Etiquetas:** video, sharing, camera phone, video phone, free, upload. Son **las etiquetas por defecto de un programa de subida**: este canal no trabaja las etiquetas y aun así hizo 14 veces su media.
- **Hashtags:** #TrueCrime #ColdCase #Documentary #Investigation #DNA #CandyRogers #MysterySolved
- **Descripción completa:**
```
On a cold Friday in March 1959, 9-year-old Candy Rogers stepped out to sell 7 small boxes of mints—and never came home. For 62 years, the city of Spokane was haunted by this mystery. Detectives spent decades chasing the wrong leads and the wrong men. But the truth wasn't lost; it was waiting inside a small glass mason jar, sealed by an unknown investigator who had no idea they were preserving the key to the future.

In this investigative documentary, we uncover the "25-Quintillion-to-One" DNA miracle that finally named the monster. It took 62 years, three generations of detectives, and a forensic breakthrough to finally stop the clock.
----------
Watch More Episoded Of Mysterious Solved Cold Cases

A Young Couple Killed in Their Quiet Ranch Home — 25 Years Later, a Tiny Caliber Detail Ended the Mystery
https://youtu.be/hiuS3ELTtYg

The Yogurt Shop 34-Year Mystery | How Science Finally Caught a Serial Killer
https://youtu.be/26NzTGZOLVE

She Left the Kitchen and Never Came Back — 23 Years Later, a Cigarette Revealed the Monster
https://youtu.be/II7H9JLiv6I
------------
If you believe every victim deserves their name back, please take a second to:

Subscribe – Help us reach more people with these forgotten stories.
Like – It tells the algorithm this case matters.
Comment – What do you think about the "25-Quintillion-to-One" DNA match?

Your engagement is the only reason we can keep digging for the truth.

#TrueCrime #ColdCase #Documentary #Investigation #DNA #CandyRogers #MysterySolved
.......
🔴DISCLAIMER:
This video is intended for informational and storytelling purposes only.
Certain narrative elements may be added to enhance storytelling; however, all case details are drawn from verified public records and authentic sources.
No claims of guilt are made. All individuals are presumed innocent unless proven guilty in a court of law.
This content is not an official investigative or legal document.
Viewer discretion is advised.
```

### 12. CrimeWatch: `xSumtxrxZCw` (384 K)
- **Título:** `How a Trace of DNA on a Hiking Boot Solved Jody Loomis Murder`
- **Fórmula:** `How a [Rastro mínimo] on a [Objeto cotidiano] Solved [Nombre] Murder`
- **Categoría:** People & Blogs · 6.351 likes
- **Miniatura:** https://i.ytimg.com/vi/xSumtxrxZCw/maxresdefault.jpg
- **Etiquetas:** #truecrime, #coldcase, #crime, #crimewatch
- **Hashtags:** #truecrime #coldcase #crime #crimewatch #jodyloomis
- **Descripción completa:**
```
On a sunny afternoon in 1972, a 20-year-old woman in Washington state borrowed her little sister's boots, climbed onto a bicycle, and never made it to the horse stable six miles away. A stain on the outside of the left boot sat unnoticed for 36 years while investigators at multiple agencies examined the evidence. When a crime lab technician finally found it in 2008, it contained the killer's DNA. The man who left it had been living five miles from the crime scene the entire time, running a ceramics shop out of his garage.

Make sure you subscribe to get your regular crime fix: https://www.youtube.com/@911CrimeWatch?sub_confirmation=1

Check old cases that has been solved recently: https://youtube.com/playlist?list=PLlppVTLMNIYmKRZhc54n2paCYwgIj3Vh6&si=tWx7Un460SLsiTaC

#truecrime #coldcase #crime #crimewatch #jodyloomis
```

### 13. Root of Crime: `55gSeWBgWJk` (275 K)
- **Título:** `Texas 1981 Yolanda Herrera Cold Case Solved - Her Killer Was Never a Suspect`
- **Fórmula:** `[Estado] [Año] [Nombre] Cold Case Solved - [Giro]`
- **Categoría:** People & Blogs · 4.761 likes
- **Miniatura:** https://i.ytimg.com/vi/55gSeWBgWJk/maxresdefault.jpg
- **Etiquetas:** Yolanda Herrera cold case, Texas cold case, Universal City cold case, Johnny's Inn, Kelly Lee Brower Sr, cold case solved, DNA cold case, DNA solves cold case, genetic genealogy cold case, Othram cold case, solved cold cases, true crime cold case. Varias tienen un salto de línea dentro: son errores de copiar y pegar.
- **Hashtags:** #ColdCase #TrueCrime #YolandaHerrera
- **Descripción completa:**
```
In April 1981, 23-year-old Yolanda Herrera left Johnny's Inn in the
Universal City area of Texas and was believed to be walking home.

She never made it.

Two days later, children walking to school found Yolanda off East
Aviation Drive. Her murder would remain unsolved for more than four
decades.

Investigators preserved crucial biological evidence, but even when
advances in DNA testing finally produced the profile of an unknown man,
they still had no name. Then the case reached an unusual turning point:
with very little evidence remaining, investigators were advised to stop
testing and wait for technology to improve.

That decision would eventually help change the case.

Advanced DNA testing and forensic genetic genealogy later led
investigators to Kelly Lee Brower Sr. in Arizona. Authorities say a
direct DNA comparison tied Brower to evidence from Yolanda's case, and
Universal City Police say he confessed during an interview with
investigators.

On August 19, 2026, Brower was arrested and charged with capital murder.
He has not been convicted, and the case remains subject to the court
process.

In this Root of Crime documentary, we follow Yolanda Herrera's 1981
Texas cold case from her final known movements, through decades of
unanswered questions, to the DNA evidence and investigative work that
finally led police to a suspect 45 years later.

Subscribe to Root of Crime for carefully researched cold cases,
long-unsolved murders, DNA breakthroughs and the stories behind the
investigations.

#ColdCase #TrueCrime #YolandaHerrera
```
> **Buena práctica que hay que copiar:** «Authorities say…», «He has not been convicted, and the case remains subject to the court process». Dice el estado judicial con exactitud. Aun así, el título («Solved», «Her Killer») va más allá de lo que dice la descripción.

### 14. Crime Files Unlocked: `D9Unqw1oivI` (220 K)
- **Título:** `Montana 1956 Cold Case Solved — A Single Glass Slide Named the Killer 65 Years Later`
- **Fórmula:** `[Estado] [Año] Cold Case Solved — A Single [Objeto] Named the Killer N Years Later`
- **Categoría:** People & Blogs · 2.360 likes · **NexLev: `isAiContent: true`**
- **Miniatura:** https://i.ytimg.com/vi/D9Unqw1oivI/maxresdefault.jpg (YouTube la sirve como `.webp`)
- **Etiquetas:** true crime, true crime documentary, true crime stories, crime stories, real crime stories, true crime cases, true crime case files, missing persons, criminal psychology, unsolved mysteries
- **Hashtags:** #TrueCrime #ColdCase #ColdCaseSolved #ForensicGenealogy #DNAEvidence #TrueCrimeDocumentary #Montana #GreatFalls #PatriciaKalitzke #CrimeFiles
- **Descripción completa:**
```
On the night of January 2nd, 1956, two teenagers left a drive-in in Great Falls, Montana and drove out toward the Sun River. By the next morning, one was dead beside the car with his hands bound behind his back. She was gone. 

For 65 years, investigators built a file that reached 35 suspects — including one of the most notorious criminals in American history. None of them were the right name. The right name was never in the file at all. It was somewhere else entirely. Waiting.

🔔 65 years. 35 suspects. The right name was never in the file. Subscribe for investigations that follow the evidence wherever it leads.

👍 A coroner sealed that glass slide in 1956 with no way of knowing it would outlast everyone including the victims, the investigators, and ultimately the killer himself. Hit like for every person who preserved something they didn't fully understand yet.

💬 The engine was still running. The radio still played. Go to the comments and type their names — Lloyd Bogle and Patricia Kalitzke. 65 years is long enough for the world to have forgotten them. This is how we make sure it doesn't.

────────────────────────────────────
📂 WATCH MORE COLD CASE INVESTIGATIONS
────────────────────────────────────

Illinois 1976 Cold Case Solved — DNA Named Her Killer 44 Years Later
https://youtu.be/iSQD0QRcHao

Michigan 1997 Cold Case Solved — A Woman's 23andMe Test Exposed Her Own Grandmother As a Killer
https://youtu.be/wNdTW_nyhIE

Illinois 1979 Cold Case Solved — A Wet Vacuum Found His DNA 44 Years Later
https://studio.youtube.com/video/GqQ4MG-0y_Y/edit

────────────────────────────────────
⚠️  DISCLAIMER
────────────────────────────────────

This documentary is produced for educational purposes only. All information is sourced from publicly available law enforcement press releases, court documents, and verified news reporting. 

Crime Files Unlocked does not speculate beyond established facts and does not sensationalize the experiences of victims or their families. The names and details of individuals mentioned are part of the public record. This content is intended to inform — not to exploit.

Thank you for watching. Stay informed, stay respectful.

#TrueCrime #ColdCase #ColdCaseSolved #ForensicGenealogy #DNAEvidence #TrueCrimeDocumentary #Montana #GreatFalls #PatriciaKalitzke #CrimeFiles
```
> Este vídeo tiene un error: uno de los enlaces apunta a `studio.youtube.com/.../edit` (el panel de edición del creador), que no funciona para los espectadores. Lo bueno es la CTA de «type their names» en comentarios, que empuja la participación y además respeta a las víctimas.

### 15. Cold Case Reopened: `N7gTtuW-kQE` (153 K): el formato largo de CCR
- **Título:** `MARYLAND 1975 Cold Case Solved After 42 Years — Justice for the Lyon Sisters`
- **Fórmula:** `[ESTADO] [AÑO] Cold Case Solved After N Years — Justice for [NOMBRE]`
- **Categoría:** People & Blogs · 3.966 likes
- **Miniatura:** https://i.ytimg.com/vi/N7gTtuW-kQE/maxresdefault.jpg
- **Etiquetas:** Cold Case Files, Cold Case · **Hashtags:** #ColdCaseFiles #ColdCase
- **Descripción completa:**
```
MARYLAND 1975 Cold Case Solved After 42 Years — Justice for the Lyon Sisters 

On the morning of March 25, 1975, Sheila Lyon, 12 years old, and her younger sister Katherine, 10 years old, left their family home in Kensington, Maryland, and walked half a mile to Wheaton Plaza to look at Easter decorations and eat pizza with friends. In the two girls' pockets were 4 dollars. On the bedroom walls at home, posters of John Denver and Kenny Loggins were still taped up. Their savings were still inside the piggy banks on the desk. Their mother, Mary, told them to be home by 4 o'clock in the afternoon. Their older brother Jay saw the two girls eating pizza in the shopping center—that was the last time anyone in the family ever saw Sheila and Katherine alive. 4 o'clock came. Then 5 o'clock. Then it grew dark. The two girls never came home. Montgomery County police launched the largest search in the history of the Washington metropolitan area. Hundreds of people combed the woods around Wheaton. Not a single trace. Not a scrap of clothing. Not a single credible witness. Two children vanished in broad daylight, half a mile from home, in a neighborhood where neighbors watched one another's children and no one had ever heard of the concept of "stranger danger." But this was America in 1975, and sometimes the innocence of an entire era had to be paid for with the lives of children.

#ColdCaseFiles #ColdCase
```

**Miniaturas de CCR citadas en la Parte C:**
- OKLAHOMA 1977 (`u_6TCZwBlew`, 9,8 K vistas en 4 días, 40:38): https://i.ytimg.com/vi/u_6TCZwBlew/maxresdefault.jpg
- SOUTH CAROLINA 1976 (`lPQ1HHoATKU`, 21 K vistas en 2 días, 38:39): https://i.ytimg.com/vi/lPQ1HHoATKU/maxresdefault.jpg

## A.3 Patrones

### Fórmulas de título, de mayor a menor techo observado

| Fórmula | Ejemplos (vistas) | Por qué funciona |
|---|---|---|
| **Ironía dramática:** `"[Adjetivo]" [Rol] Has No Idea [la policía/el ADN ya sabe]…` | Red File 14,9 M; TCD 1,28 M | El espectador sabe más que el protagonista y quiere ver el momento en que se entera. Exige **material real** de interrogatorio o de bodycam. |
| **«Killer Realizes He's Been Caught N Years Later»** | Nexcrime 1,03 M; DT Scofield 781 K; Interrogation Core 663 K; Red File 2,35 M | La misma promesa: la cara del asesino al darse cuenta. Ya está muy copiada entre canales. |
| **Emocional sin nombres** (Othram): `Her Killer Hid in Plain Sight for N Years`, `The 14 Year Old Girl Who Finally Got To Go Home`, `She Left Them Behind... N Years Later, DNA Revealed Why` | 1,62 M; 1,13 M; 1,16 M | Hueco de curiosidad y final emocional. Funciona porque hay producción propia y entrevistas detrás. |
| **Geo-año + choque genérico:** `STATE YEAR Cold Case Solved — Arrest Shocks Community` | Crimewatch Central 1,13 M; CCR 462 K, 269 K y 189 K | Se busca bien por estado y año, y no revela el caso. **Ojo:** a menudo es falso (en el caso Walsh no hubo detención). |
| **Objeto diminuto + N años:** `A Single Glass Slide Named the Killer 65 Years Later`, `How a Trace of DNA on a Hiking Boot Solved…`, `…by a Single Drop of DNA` | 220 K (20,8×); 384 K (18,9×); 459 K (14,3×) | Son los **outliers más altos en canales pequeños**. La pista concreta da curiosidad sin necesidad de material real. |
| **Geo-año + nombre + giro:** `Texas 1981 Yolanda Herrera Cold Case Solved - Her Killer Was Never a Suspect` | 275 K | Junta la búsqueda por nombre con la sorpresa. |
| **Geo-año + «Justice for NAME»** (los largos de CCR) | de 2,6 K a 160 K | Funciona solo con casos famosos o familias enteras. Sin giro, se queda corto. |

**Constantes:**
1. **Siempre aparece el tiempo** («N Years Later» o «After N Years»).
2. Casi nunca sale el nombre de la víctima en los virales grandes. Va en la descripción y en los hashtags.
3. Un único giro concreto: un objeto, una ironía o «never a suspect».
4. Mayúsculas, como mucho, en una palabra («SOLVED») o en el estado (CCR).

### Estructura de la descripción

La plantilla destilada de los mejores vídeos:
1. **Línea 1, el gancho.** Puede repetir el título (CCR, Red File) o ser una frase fuerte («Four suspects. One killer. Twenty-seven years of nothing.»).
2. **El resumen narrativo**, de 80 a 300 palabras: quién, cuándo, dónde, la pista y el desenlace. Red File lo divide en secciones con emojis. Es largo, pero se lee bien y le da a YouTube mucho texto relevante.
3. **Fuentes con URL.** Lo hacen Crimewatch Central y CCR en `iz80`. Da credibilidad y protege ante reclamaciones.
4. **Enlaces a 2 o 3 vídeos propios o a una lista** con títulos que siguen la misma fórmula (Red File, Crimewatch Central, Crime Narrator, Crime Files Unlocked, CrimeWatch).
5. **La CTA:** suscribirse o comentar. Crime Narrator y Crime Files Unlocked la ligan a la víctima («type their names»).
6. **Aviso legal:** fines educativos, presunción de inocencia, fair use (§107) y, en los mejores, **la línea del estado judicial real**. Crimewatch Central dice «No criminal charges were ever filed» y Root of Crime dice «He has not been convicted».
7. **Créditos** cuando hay recreación. Othram pone «Reenactment Actress/Actor».
8. **Hashtags al final:** entre 3 y 23.

### Práctica con hashtags y etiquetas

| Canal | Etiquetas | Hashtags |
|---|---|---|
| CCR | **Solo 2:** «Cold Case Files, Cold Case» | `#ColdCaseFiles #ColdCase`. El viral `iz80` no lleva ninguno. |
| Othram | De 0 a 5 temáticas | `#TrueCrime #ColdCase #DNA` |
| Red File | 25, con nombres de la competencia y temas ajenos | 9: genéricos más nombres del caso |
| Crimewatch Central | 22 sobre el caso | 23 |
| Nexcrime y DT Scofield | 0 | 15 y 0 |
| Crime Narrator | Las de por defecto («video, sharing…») | 7 |

**Conclusión:** las etiquetas **no explican** el éxito. Hay virales de un millón con 0 etiquetas y con etiquetas basura. Los hashtags que se repiten en todos son `#TrueCrime` y `#ColdCase`, más `#ColdCaseSolved`, `#DNAEvidence`, el nombre de la víctima y el lugar. YouTube muestra encima del título los 3 primeros hashtags de la descripción.

### Qué copiar para nuestro canal

1. **Título:** mantener el SEO de CCR (`STATE YEAR`) pero **añadir el giro** y el tiempo. Plantilla: `STATE YEAR Cold Case — [Objeto o ironía] [Verbo exacto según el estado judicial] After N Years`. Ejemplos:
   - Martinko: «IOWA 1979 — The Killer Smiled at Detectives for 40 Years. Then His DNA Came Back».
   - Childs: «MINNESOTA 1993 — A Napkin at a Hockey Game Convicted Her Killer 25 Years Later».
   - Para hacer A/B, preparar una versión de ironía dramática si hay vídeo real del interrogatorio.
2. **Ángulo:** si existe un interrogatorio o una bodycam publicados (como en Martinko, Burns, Lazarus o Daniel Wells), **construir el vídeo alrededor de ese momento**. Es la diferencia entre 18 K y 14,9 M.
3. **Descripción:** gancho, resumen, **fuentes con URL**, **línea de estado judicial**, divulgación de la IA si la hay, 2 o 3 vídeos enlazados, CTA con el nombre de la víctima, aviso legal y de 4 a 8 hashtags (`#TrueCrime #ColdCase #ColdCaseSolved #[Victima] #[Ciudad] #[Estado]Crime`).
4. **Etiquetas:** de 8 a 15, todas relevantes (víctima, autor condenado, ciudad, «cold case solved», «genetic genealogy», el laboratorio). **Nunca** nombres de otros canales ni de famosos ajenos al caso.
5. **Créditos de transparencia** al estilo Othram: «Photos: [fuente]. Scenes of places and objects marked "AI illustration" are AI-generated.»

---

# PARTE B: Miniaturas

## B.1 Qué se ha verificado y qué no

| Fuente | Resultado |
|---|---|
| Descargar las miniaturas | **No se pudo.** La red bloquea `i.ytimg.com`. |
| `get_similar_thumbnails` (por URL, sobre la miniatura de CCR `iz80`) | Solo devuelve metadatos. Las miniaturas más parecidas visualmente son de **Cold Case Files** (7,38 K suscr.): «Montana 1996…» (9,9 K vistas) y «Texas 1995 Cold Case Solved — Arrest Shocks Community» (2,9 K). También salen de **Vanished Women and Children** (11,4 K): «The First Cold Case Solved by Ohio Police…» y «Missing Daughter FOUND ALIVE After 42 Years». Es decir, **el estilo de CCR ya se está clonando**, y los clones rinden poco. |
| `watch_youtube_video_and_ask`, primeros 20 s, en 4 vídeos | Esto describe **el vídeo, no la miniatura**. Los resultados están abajo. |
| Captura de 3 miniaturas de CCR (la aportó el usuario) | Es la única evidencia directa de las miniaturas. Está en la Parte C. |

**Lo que Gemini vio en los primeros 20 segundos:**

- **CCR `iz80aDNZ0Ig` (Jaycee):**
  - De 0 a 16 s, una foto a color de una niña rubia sacando la lengua. Gemini la describe como **«colorized or AI-restored»**: tiene grano vintage, pero la piel es «exceptionally smooth» y la iluminación muy uniforme.
  - De 16 a 20 s, una foto en blanco y negro de un policía que sostiene una foto de la niña. Parece archivo auténtico.
  - Subtítulos blancos. **No aparece ninguna etiqueta de IA.**
- **CCR `lPQ1HHoATKU` (Carolina del Sur 1976):**
  - Camino de tierra con niebla, texto «9 August 1976», cabina de un camión Mack y una señal verde «INTERSTATE 95 EXIT». Todo tiene «el aspecto HD de producción moderna»: puede ser IA o puede ser stock.
  - **Una página de anuario con dos fotos que parecen auténticas, rotuladas (según Gemini) «Pat Burke» y «Aubrey Gentry».**
  - Un hombre con un microscopio (recreación moderna) y un documento «Case Number ME-78-396, White Female, 19 +/- 3».
  - **No aparece ninguna etiqueta de IA ni de recreación.**
- **Red File `rJYy0pHZDxA`:**
  - **Vídeo real del interrogatorio** de Stephanie Lazarus, granulado.
  - Su foto de uniforme rotulada «STEPHANIE LAZARUS, LAPD Detective (25-Years)».
  - Un primer plano en blanco y negro con efecto VHS y un texto **rojo semitransparente**, «CASE FROM OVER TWENTY YEARS AGO».
  - Una foto real de la pareja rotulada «Ex-Boyfriend's Wife» y «Ex-Boyfriend».
  - **Sin IA.**
- **Crimewatch Central `zeEbnTdxWGE`:**
  - Una pantalla de aviso en rojo y blanco sobre negro.
  - Un gráfico de noticiario («KDBG 4», «POLICE DETERMINE WALSH MURDERER»).
  - **El retrato real** de Adam Walsh, un retrato robot y el vídeo de CBS de John Walsh.
  - **Sin IA.**

## B.2 Miniatura por vídeo: lo que se sabe y lo que se deduce

Ninguna de estas miniaturas se ha visto. Lo que sigue se deduce del título, del arranque del vídeo y del estilo del canal.

| Vídeo | Descripción probable (no verificada) | Base |
|---|---|---|
| Red File `rJYy0pHZDxA` | Un fotograma real de la sospechosa en la sala de interrogatorios, tratamiento en blanco y negro o VHS, texto rojo y el logo «RED FILE». | El primer minuto del vídeo usa exactamente esa estética. |
| TCD, Nexcrime, DT Scofield, Interrogation Core | Un fotograma real del sospechoso (interrogatorio o bodycam), con una flecha o un círculo rojo, 2 a 4 palabras y quizá la foto de la víctima en un recuadro. | Es el estilo habitual de los canales «Killer Realizes» y bodycam (inferencia). |
| Othram (×3) | Fotografía cinematográfica propia (recreación con actores acreditados, lugares, familiares) y poco texto. | Las descripciones acreditan recreación y rodaje propio. |
| Crimewatch Central `zeEbnTdxWGE` | Probablemente la foto real de Adam Walsh y estética de noticiario. | Los primeros segundos usan fotos y noticiarios reales. |
| CCR (todos) | Banner rojo «UNSOLVED-[AÑO]» o «[ESTADO] [AÑO]», 2 líneas de gancho, caras en blanco y negro, objetos del caso (señal de la I-95, camión). **Las caras pueden no ser reales** (ver la Parte C). | La captura del usuario y el flag de IA de NexLev. |
| Crime Narrator, CrimeWatch, Crime Files Unlocked | El objeto del título (frasco, bota, portaobjetos) más la foto de la víctima. Crime Files Unlocked está marcado como IA. | Inferencia a partir de los títulos. |

## B.3 Las fórmulas de miniatura del nicho, y la nuestra

**Composición (la que funciona en el nicho):**
- A la izquierda, en el 50–60 % del ancho, una **cara**: la víctima en foto real de archivo, o el sospechoso en un fotograma real.
- A la derecha, **un objeto o lugar** que es la «pista»: la bota, la servilleta, el portaobjetos, la señal de la autopista.
- Arriba, un **banner** con estado y año.
- Abajo o a la derecha, **de 3 a 5 palabras** con el gancho.

**Texto:**
- Como máximo 2 líneas y 5 palabras por línea, en sans-serif condensada y gruesa.
- Debe completar el título, no repetirlo. Si el título dice «N Years Later», la miniatura puede decir «HE WORKED 5 MILES AWAY».

**Colores:**
- La foto en blanco y negro o desaturada.
- Acento **rojo** (#C1121F o similar) para el banner y los subrayados.
- Texto blanco o amarillo con sombra negra y viñeta oscura.
- En el subnicho de interrogatorios, efecto VHS o scanlines.

**Caras o objetos:**
- Las caras reales dan CTR.
- Los objetos dan el **giro** y son **seguros** desde el punto de vista legal.
- Lo ideal es combinar las dos cosas: una cara real con crédito y el objeto, o una cara no identificable (silueta, de espaldas, desenfocada) más el objeto.

**El banner «UNSOLVED-AÑO»:**
- Es el sello visual de CCR, un rectángulo rojo con el año.
- Recomendación: **convertirlo en un sello de estado judicial**: `UNSOLVED 1979 → SOLVED 2019`, `CONVICTED`, `IDENTIFIED`, `DNA LINKED · NEVER TRIED`.
- Así seguimos el patrón que el público ya reconoce, pero **el sello dice la verdad jurídica** (ver la tabla de vocabulario en C.5).

---

# PARTE C: ¿Las personas de las miniaturas de Cold Case Reopened son las víctimas reales?

## C.1 La respuesta corta

**Probablemente no, al menos no todas. En la de Oklahoma 1977 es seguro que no todas lo son.**

Las pruebas apuntan a caras generadas, compuestas o «restauradas» con IA, y a fotos reales de personas ajenas al caso usadas como relleno. **No se puede afirmar al 100 % sin ver los archivos de imagen.**

## C.2 Las pruebas

| # | Prueba | Peso | Qué demuestra |
|---|---|---|---|
| 1 | La miniatura de **OKLAHOMA 1977** («Justice for Lori, Michelle & Doris») muestra **4 caras de niñas**. Las víctimas de Camp Scott fueron **3** (Lori Farmer, Michelle Guse y Doris Milner). | **Fuerte** | Por lo menos una cara **no puede ser una víctima**. Es una cara inventada o de otra persona. Las otras 3 también quedan en duda. |
| 2 | La miniatura de **SOUTH CAROLINA 1976** tiene 2 caras jóvenes en blanco y negro, hiperlisas y con luz de estudio, más una señal de la I-95 y un camión. | Media | Es el aspecto típico de un compuesto hecho con IA. Por sí sola no prueba nada. |
| 3 | NexLev marca el vídeo `iz80aDNZ0Ig` de CCR con `isAiContent: true`. | Media | El clasificador detecta contenido generado con IA en el canal, aunque no dice en qué parte del vídeo. |
| 4 | En `iz80` (Jaycee Dugard, **una superviviente viva**), Gemini describe la foto de apertura como «colorized or AI-restored», con piel «exceptionally smooth». No hay ninguna etiqueta. | Media | CCR altera fotos reales de personas reales sin avisar. |
| 5 | En `lPQ1HHoATKU` (Carolina del Sur), Gemini lee en la página de anuario los nombres **«Pat Burke» y «Aubrey Gentry»**. Las víctimas son **Pamela Buckley y James Freund**, identificados en enero de 2021 por el DNA Doe Project. | Media (Gemini puede leer mal) | Si la lectura es correcta, CCR muestra **fotos reales de terceros** como si fueran las víctimas. Eso es peor que la IA: es la cara de una persona real que puede seguir viva. |
| 6 | **Estado judicial.** Oklahoma 1977: Gene Leroy Hart fue **absuelto en 1979** y murió ese mismo año en prisión por otra causa. El caso **sigue oficialmente abierto**. El sheriff Mike Reed dijo que el ADN «strongly suggests» que fue Hart y que los resultados se conocían desde 2019. Esto se difundió en 2022 (fecha que no he podido confirmar en esta búsqueda). | **Fuerte** | La frase «45 YEARS LATER, DNA NAMED THE KILLER» y el título «Cold Case Solved» **exageran** el caso: un jurado absolvió a la única persona acusada. |
| 7 | Carolina del Sur 1976: lo que se resolvió en 2021 fue **la identidad** de las víctimas. La cobertura de 2021 no recoge ninguna acusación; la oficina del sheriff tenía «una lista de posibles sospechosos». | Media (puede haber novedades después de 2021) | El título «Cold Case Solved After 45 Years — Justice for Freund & Buckley» también podría exagerar. |
| 8 | Comparación: los competidores grandes (Red File, Crimewatch Central) usan **fotos y vídeos reales**. Gemini no detectó IA en ellos. | Contexto | La IA en las caras **no es necesaria** para hacerse viral en este nicho. |

## C.3 Análisis de riesgo

### 1) La política de YouTube sobre contenido alterado o sintético
- Desde marzo de 2024 hay que **declarar en YouTube Studio** el contenido realista que el espectador pueda tomar por una persona, un lugar o un suceso reales cuando se ha creado o alterado con medios sintéticos. Ejemplos de la política: hacer que una persona real parezca hacer o decir algo que no hizo, alterar imágenes de hechos o lugares reales, o generar escenas realistas.
- **Quedan exentos** el contenido claramente irreal o animado y la ayuda en la producción (guion, subtítulos). Los retoques menores, como el color, en principio también. Una «restauración» con IA que **inventa rasgos de la cara** ya no es un retoque menor.
- **Cómo se aplica a CCR:** una cara de víctima generada con IA es una representación realista de una persona real, así que **requiere la divulgación**. No hemos visto ninguna etiqueta en los primeros segundos y no podemos ver si marcaron la casilla en Studio.
- **Sanción por no declararlo:** retirada del contenido o **suspensión del YPP** (la monetización). YouTube también puede poner la etiqueta por su cuenta.
- La divulgación se refiere al vídeo. Las miniaturas, por su parte, **tienen que cumplir las Normas de la comunidad** igual que el vídeo.
- De memoria, sin búsqueda de hoy: desde julio de 2025, el YPP llama «inauthentic content» a lo que antes era «repetitious content». Es el criterio que se usa contra el contenido masivo de baja originalidad. Un canal faceless que clona plantillas y caras IA está más expuesto a perder la monetización.

### 2) Acoso: las víctimas fallecidas
- **Desde el 16 de enero de 2024**, la política de acoso de YouTube **prohíbe el contenido que simula de forma realista a menores fallecidos o a víctimas de sucesos mortales o violentos bien documentados describiendo su muerte o la violencia que sufrieron.** Nació por los vídeos de true crime con IA que «daban voz» a niños asesinados, como James Bulger.
- Se castiga con strikes: con **3 en 90 días se cierra el canal**, y el primero bloquea las subidas durante una semana.
- Una miniatura estática con caras IA de **niñas asesinadas** (Camp Scott, de 8 a 10 años) no «narra» su muerte, así que probablemente queda fuera de la letra de la norma. Pero está **en la zona que YouTube vigila**. Si dentro del vídeo esas caras IA se animan o «hablan», el riesgo de strike es directo.

### 3) Miniaturas y metadatos engañosos
- La política de *Spam, deceptive practices & scams* prohíbe **usar el título, la miniatura o la descripción para hacer creer que el contenido es algo que no es**.
- En CCR hay tres problemas:
  - (a) caras que no son las víctimas, presentadas como si lo fueran («Justice for Lori, Michelle & Doris»);
  - (b) «Solved» o «DNA NAMED THE KILLER» en un caso oficialmente abierto, con el único acusado absuelto;
  - (c) «Arrest Shocks Community» en casos donde no hubo detención (Walsh, en el clon de Crimewatch Central).
- Las tres son argumentables como metadatos engañosos. YouTube ha anunciado mano dura con el clickbait «flagrante», sobre todo en temas de actualidad. Las miniaturas que infringen la norma se retiran y pueden suponer un strike.

### 4) Sucesos sensibles, privacidad y la queja por imagen generada con IA
- **Cualquier persona identificable** (o su tutor legal) puede pedir la retirada de contenido **generado o alterado con IA que simule su cara o su voz** mediante el formulario de privacidad de YouTube.
- YouTube valora varias cosas: si el contenido es sintético, si la persona es identificable, si es realista, si tiene interés público, sátira o parodia, y si está etiquetado. **Etiquetarlo no garantiza que no se retire.**
- Al que subió el vídeo se le avisa y tiene unas **48 horas** para quitarlo o editarlo (recortar o desenfocar).
- **Para CCR, el caso más claro es Jaycee Dugard: está viva**, y su foto aparece «restaurada con IA». También lo son las personas reales del anuario si la lectura de Gemini es correcta, y los familiares vivos que se reconozcan.
- Para víctimas fallecidas, las guías de privacidad prevén solicitudes de familiares directos o representantes legales en algunos supuestos. **Hay que comprobarlo en la página de ayuda vigente.**
- Las quejas de privacidad repetidas pueden acabar en medidas contra el canal.
- Aparte de esto, el contenido violento o gráfico (escenas, autopsias) puede tener **restricción de edad**, y eso hunde la distribución y los anuncios.

### 5) Derecho estadounidense
- **Difamación:**
  - En la mayoría de los estados, **los muertos no pueden ser difamados** y la acción no pasa a los herederos. Por eso Hart, ya fallecido, no puede demandar.
  - El riesgo real está en **los vivos**:
    - (a) una persona real cuya foto se usa por error como víctima o, peor, **como «asesino»**;
    - (b) un sospechoso **acusado pero no condenado**, como Brower en el vídeo de Root of Crime, al que se llama «killer» en el título;
    - (c) una cara IA de un «sospechoso» que **se parezca** a alguien real;
    - (d) un exonerado o un inocente al que se vuelve a señalar, como Christopher Tapp en nuestro guion 03 o los condenados por error en el 04.
  - Con un particular basta con probar **negligencia** para cobrar los daños reales. Con figuras públicas o asuntos de interés público se aplica el estándar más exigente de *actual malice* (*Sullivan*, *Gertz*).
- **Falsa luz** (*false light*):
  - Es presentar a alguien bajo una luz falsa y muy ofensiva, por ejemplo un familiar o superviviente en una escena inventada.
  - **No la reconocen todos los estados.** Nueva York y Texas, por ejemplo, no la admiten, y Florida la rechazó en 2008.
  - Es una acción personal y en general se extingue con la muerte.
- **Derecho de imagen** (*right of publicity*):
  - Protege el uso **comercial** del nombre o la imagen. Las excepciones de noticias, documental y asuntos públicos suelen cubrir el true crime con fotos reales.
  - **Las réplicas digitales hechas con IA son la excepción que está creciendo:**
    - **California (AB 1836)** creó responsabilidad por producir o distribuir sin consentimiento una réplica digital de la voz o la imagen de una *deceased personality*, con una indemnización de 10.000 USD o los daños reales, lo que sea mayor.
    - **Nueva York** tiene una ley post mortem de réplicas, con excepciones para noticias, comentario y documental.
    - Los derechos post mortem duran **entre 10 y 100 años** según el estado, y en 2026 varios estados están ampliándolos.
  - Normalmente estas leyes exigen que la persona tuviera **valor comercial** en vida, cosa que la mayoría de las víctimas no tenían, así que el riesgo jurídico directo es **bajo pero no nulo y va en aumento**. Además, las excepciones documentales **podrían no cubrir** una réplica que el público tome por auténtica. Esto conviene confirmarlo con un abogado.
- **Daño emocional a las familias:**
  - La demanda por *intentional infliction of emotional distress* exige una conducta «extrema y escandalosa», y la Primera Enmienda protege mucho el discurso sobre asuntos de interés público (*Snyder v. Phelps*). Ganar esa demanda es difícil.
  - Pero el Supremo ha reconocido el **interés de la familia en la intimidad de la imagen de sus muertos** (*NARA v. Favish*, 2004, en el contexto de la FOIA).
  - En la práctica, el daño se traduce en **quejas a YouTube, presión mediática y comentarios** antes que en pleitos. La madre de James Bulger calificó los vídeos con IA de su hijo de «absolutely disgusting», y eso empujó el cambio de política de 2024.

### 6) Copyright de las fotos de archivo reales
- Que la foto de una víctima sea real **no significa que sea libre**. Los derechos pueden ser del fotógrafo, del periódico, de la agencia (AP, Getty), de la familia o del estudio del anuario.
- **El fair use no está garantizado:**
  - En *Fitzgerald v. CBS* (2007) se negó el fair use por fotos de un acusado emitidas en un noticiario: el uso era comercial y el recorte no lo hacía transformador.
  - En *Chosen Figure v. Kevin Frazier Prods.* (C.D. Cal. 2025) los 4 factores fueron en contra del medio.
  - En cambio, en un juicio de Nueva York se consideró **probablemente fair use** que ABC usara la foto del sospechoso del ataque con camión.
- **El uso en la miniatura es el más arriesgado**, porque es promocional y poco transformador. Dentro del vídeo, con comentario, poco tiempo en pantalla y crédito, el riesgo baja. **El crédito no equivale a una licencia**, pero demuestra buena fe.
- **Fuentes más seguras:**
  - Las fotos de **comunicados oficiales**: policía, fiscalía, FBI, NamUs, DNA Doe Project, Othram. Las obras del gobierno **federal** son de dominio público (17 U.S.C. §105). Las estatales y locales dependen de cada estado.
  - Los **anuarios publicados antes de 1978 sin aviso de copyright**, que suelen estar en dominio público, aunque hay que comprobarlo en cada caso.
  - Las fotos con licencia o las cedidas por la familia.
- **Consecuencias prácticas:** Content ID, strikes de copyright (3 strikes cierran el canal) y reclamaciones de agencias.

### 7) Riesgo de reputación
- En este nicho el público es muy sensible a la falta de respeto a las víctimas. Una cara IA que «no es ella» se descubre en los comentarios y destroza la credibilidad del canal.
- Los laboratorios, las fiscalías y las familias son **fuentes y aliados**, y pueden negarse a colaborar o denunciar públicamente al canal.
- Los anunciantes evitan el contenido marcado como engañoso.
- Ya existen clones del estilo de CCR (Cold Case Files, Vanished Women and Children) y no rinden. **Diferenciarnos como el canal «verificado y real»** es a la vez una ventaja competitiva y una defensa.

**Matriz de riesgo para nuestro canal si copiáramos la práctica de CCR:**

| Riesgo | Probabilidad | Impacto | Nivel |
|---|---|---|---|
| Perder el YPP o que retiren vídeos por no declarar contenido sintético | Media | Alto | **Alto** |
| Strike por acoso, si la cara IA de la víctima aparece animada o narrando | Baja o media | Muy alto (cierre) | **Alto** |
| Retirada o strike por metadatos o miniaturas engañosos («Solved» falso) | Media | Medio | Medio |
| Queja de privacidad por imagen IA (un superviviente o un familiar vivo) | Media | Medio | Medio |
| Difamación o falsa luz por una persona viva mal identificada o un acusado no condenado | Baja | Muy alto | **Medio o alto** |
| Derecho de imagen por réplicas digitales (CA y NY) | Baja | Medio | Bajo, pero sube |
| Strike de copyright por una foto de archivo en la miniatura | Media | Medio o alto | Medio |
| Daño de reputación, pérdida de fuentes y comentarios negativos | Alta | Medio | **Alto** |

## C.4 Reglas para nuestro canal

**Imágenes de personas**
1. **Solo fotos de archivo reales y verificadas** de la víctima o del autor, con la fuente comprobada. Si no podemos confirmar que la foto es de esa persona, **no se usa**.
2. **Cada foto lleva su crédito**, en pantalla («Photo: Sumter County Sheriff's Office») y en la descripción. Por orden de preferencia: comunicados oficiales, dominio público, licencia o cesión de la familia, y por último fair use con comentario.
3. Si no hay foto real, usamos **imágenes que no identifiquen a nadie**: silueta, de espaldas, fuera de foco, manos, objetos personales genéricos o un retrato robot oficial rotulado como tal.
4. **Nunca usamos una cara generada con IA presentada como víctima, sospechoso, familiar o testigo**, ni en la miniatura ni en el vídeo. Tampoco «restauramos» caras con IA. Un ajuste de contraste o de color sí se permite; inventar rasgos no.
5. **Nunca animamos ni damos voz a una víctima** (política de acoso de 2024).
6. **Un rostro por persona real.** Si el caso tiene 3 víctimas, la miniatura muestra como mucho 3 caras y todas reales. Si no, ninguna.

**Uso de la IA**
7. La IA se usa **solo para lugares, objetos y ambientes** (una carretera de 1976, una sala de pruebas, un frasco), nunca para recrear una escena concreta del crimen con personas.
8. Toda imagen IA lleva el rótulo **«AI illustration»** en una esquina, se menciona en la descripción y, si es realista, se marca la casilla de contenido alterado o sintético en Studio.
9. En la descripción va siempre la línea de transparencia: «Archival photos credited on screen. Places and objects marked "AI illustration" are AI-generated; no AI images of real people are used.»

**Títulos y miniaturas según el estado judicial**
10. Lo que dicen la miniatura y el título **tiene que coincidir con el estado legal** en la fecha de publicación (ver la tabla C.5). Una vez por cada guion se revisa el estado en una fuente primaria: la fiscalía, el sheriff o el tribunal.
11. «Killer» o «asesino» **solo para condenados** o confesos con condena, o para personas nombradas oficialmente que hayan muerto, y en ese caso hay que decirlo así: «named by police», «never charged».
12. Para acusados no condenados: «charged», «accused» y la línea «has not been convicted» en la descripción y en la narración.
13. Nada de «Arrest Shocks Community» si no hubo detención.

**Metadatos**
14. Etiquetas y hashtags siempre relevantes. Nunca nombres de otros canales ni de famosos ajenos al caso.
15. En la descripción: fuentes con URL, la línea de estado judicial y el aviso de fair use y presunción de inocencia.

**Proceso**
16. Si un familiar o un afectado pide que retiremos su imagen: se responde en menos de 48 horas, se retira o se desenfoca, y queda registrado.
17. Antes de publicar, la lista del paso 10 de la guía más esta comprobación: cuántas caras hay, quién es cada una, la fuente y el crédito, si hay IA y si está rotulada, y si las palabras del título y la miniatura coinciden con la tabla C.5.

## C.5 Vocabulario permitido según el estado judicial

| Estado real del caso | Palabras permitidas (miniatura y título) | Palabras prohibidas | Ejemplo |
|---|---|---|---|
| Condena o declaración de culpabilidad firme | SOLVED, CONVICTED, KILLER, JUSTICE | — | «IOWA 1979 — CONVICTED 42 YEARS LATER» |
| Acusado y pendiente de juicio | CHARGED, ARRESTED, ACCUSED, SUSPECT | SOLVED, KILLER, JUSTICE | «TEXAS 1981 — ARRESTED 45 YEARS LATER» |
| La policía o el ADN señalan a alguien que murió sin juicio | DNA LINKED, NAMED BY POLICE, NEVER TRIED | SOLVED, CONVICTED, «DNA NAMED THE KILLER» | Oklahoma 1977: «DNA POINTS TO THE MAN A JURY ACQUITTED» |
| Solo se identificó a la víctima | IDENTIFIED, FINALLY HAS A NAME | SOLVED, JUSTICE FOR | Carolina del Sur 1976: «I-95 DOES IDENTIFIED AFTER 45 YEARS» |
| Exoneración o condena errónea | EXONERATED, WRONGLY CONVICTED | Insinuar la culpa del exonerado | Idaho 1996 (Tapp) |

**Cómo afecta esto a nuestros guiones** (los títulos actuales están en el `README.md`):
- **03, Angie Dodge:** hubo condena del verdadero autor. Hay que cuidar que Tapp aparezca siempre como exonerado.
- **04, Dana Ireland:** el ADN identificó a Albert Lauro Jr., que murió en 2024 sin juicio. Hay que poner «DNA IDENTIFIED», no «Solved».
- **14, Adam Walsh:** la policía nombró a Toole en 2008 y no hubo cargos. Hay que poner «NAMED BY POLICE», no «Arrest».
- **18, 19 y 20 (Chandler, Lori Ruff, Tent Girl):** son identificaciones. Hay que poner «IDENTIFIED».
- **09, Boy in the Box:** «Identified» ya es correcto.
- Hay que comprobar también el estado exacto de los guiones 11 a 17 antes de fijar sus miniaturas.

---

## Fuentes

**Datos de NexLev** (11-10-2026): `youtube_video_details` de los 15 vídeos, `faceless_outliers_videos`, `youtube_channel_videos` (CCR, ordenado por popularidad, 60 vídeos), `get_similar_thumbnails` sobre la miniatura `iz80aDNZ0Ig` y `watch_youtube_video_and_ask` (0–20 s) sobre `lPQ1HHoATKU`, `iz80aDNZ0Ig`, `rJYy0pHZDxA` y `zeEbnTdxWGE`.

**Búsquedas web (8):**
- Divulgación de contenido sintético: [NPR](https://www.npr.org/2023/11/14/1212986395/youtube-will-label-ai-generated-videos-that-look-real), [Newsshooter](https://www.newsshooter.com/2024/03/19/youtube-is-introducing-a-tool-in-creator-studio-that-requires-creators-to-disclose-when-their-content-has-been-altered-in-ways-that-seem-realistic/), [minimatters](https://minimatters.com/youtube-altered-or-synthetic-content-disclosure/)
- Queja de privacidad por IA: [formulario de YouTube](https://support.google.com/youtube/contact/YT_privacy_AI_complaint), [YouTube Privacy Guidelines](https://support.google.com/youtube/answer/7671399), [Protecting your identity](https://support.google.com/youtube/answer/2801895), [The Decoder](https://the-decoder.com/youtube-cracks-down-on-ai-deepfakes-with-new-privacy-removal-process/), [Shelly Palmer](https://shellypalmer.com/2024/07/you-can-ask-youtube-to-take-down-ai-generated-content-that-simulates-your-face-or-voice/)
- Política de acoso de 2024 (víctimas fallecidas): [TechCrunch](https://techcrunch.com/2024/01/08/youtube-cracks-down-ai-generated-content-realistically-simulates-deceased-children-or-victims-of-crimes), [MediaNama](https://www.medianama.com/2024/01/223-youtube-ai-generated-content-crime-victims/), [Gigazine](https://gigazine.net/gsc_news/en/20240109-youtube-ai-deepfakes)
- Metadatos y miniaturas engañosos: [YouTube: Spam, deceptive practices & scams](https://support.google.com/youtube/answer/2801973), [Fast Company ME](https://fastcompanyme.com/technology/youtube-has-a-new-plan-to-combat-clickbait/)
- Camp Scott (Oklahoma 1977): [Wikipedia](https://en.wikipedia.org/wiki/Oklahoma_Girl_Scout_murders), [Fox News](https://www.foxnews.com/entertainment/kristin-chenoweth-1977-girl-scout-murders-true-crime-hulu.amp), [Cherokee Phoenix](https://www.cherokeephoenix.org/news/dna-testing-in-girl-scout-killings-inconclusive/article_7192fbc4-3995-5515-b9e1-263b6a15fa0a.html)
- Freund y Buckley (Carolina del Sur 1976): [KKTV](https://www.kktv.com/2021/01/21/colorado-springs-woman-identified-as-one-victim-in-a-44-year-old-cold-case-out-of-south-carolina), [Live 5 News](https://www.live5news.com/2021/01/22/investigators-identify-victims-cold-case-out-sumter-county/), [The Item](https://theitem.com/stories/names-of-sumter-countys-1976-john-jane-doe-murder-mystery-released,357953)
- Derecho de imagen y réplicas digitales: [CDAS, California AB 1836](https://cdas.com/california-expands-its-post-mortem-right-of-publicity-law-to-cover-ai-digital-replicas/), [MultiState](https://www.multistate.ai/updates/vol-89-state-digital-replica-laws-post-mortem-rights), [NYSBA](https://nysba.org/the-modern-east-west-divide-ai-and-publicity-rights-in-new-york-and-california/), [Right of Publicity Roadmap](https://rightofpublicityroadmap.com/news_commentary/california-considers-a-digital-replica-law-for-the-dead/)
- Fair use de fotos de noticias: [Copyright Office: Chosen Figure v. Kevin Frazier (2025)](https://www.copyright.gov/fair-use/summaries/Chosen-Figure-LLC-v-Kevin-Frazier-Prods-795-F-Supp-3d-1232-CD-Cal-2025.pdf), [Copyright Office: Fitzgerald v. CBS (2007)](https://www.copyright.gov/fair-use/summaries/fitzgerald-cbsbroad-dmass2007.pdf), [Courthouse News: ABC y la foto del sospechoso](https://courthousenews.com/photo-suspect-nyc-truck-attack-likely-fair-use/), [Loeb & Loeb](https://www.loeb.com/zh-hans/insights/publications/2019/01/courts-limiting-use-of-copyrighted-photos-for-news-media)

**De conocimiento general, sin búsqueda en esta sesión** (verificar si son decisivos): que los muertos no pueden ser difamados en la mayoría de los estados; el reconocimiento estatal de la falsa luz; *NYT v. Sullivan* y *Gertz*; *Snyder v. Phelps*; *NARA v. Favish*; 17 U.S.C. §105; las reglas de aviso de copyright antes de 1978 y 1989; el cambio de nombre del YPP a «inauthentic content» (julio de 2025); y que YouTube muestra los 3 primeros hashtags encima del título.
