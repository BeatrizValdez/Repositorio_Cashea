# Metodología del corpus documental del caso Cashea

Documento metodológico completo del estudio de caso exploratorio sobre Cashea. En el capítulo se informa únicamente lo esencial; este archivo desarrolla el procedimiento en detalle para su revisión por pares.

## 1. Diseño

Estudio de caso único, exploratorio y revelador, desarrollado mediante **netnografía documental**: observación sistemática de trazas públicas en línea —documentos corporativos, cobertura periodística y publicaciones en redes sociales— sin interacción directa con los participantes (Kozinets, 2002), en la tradición de los métodos digitales (Rogers, 2013) y de los métodos de interfaz (Marres & Gerlitz, 2016).

La elección del caso se justifica por: (i) su carácter extremo —la mayor plataforma BNPL de América Latina operando en el país con el crédito bancario más restringido de la región—; (ii) la disponibilidad de un **experimento natural documentado**: la modificación unilateral de las reglas del 13-16 de octubre de 2025, seguida de protesta pública y reversa parcial en 72 horas, todo ello trazable en fuentes públicas; y (iii) un segundo episodio de contestación documentado: la suspensión de la escalera punitiva tras los terremotos de junio de 2026, precedida de peticiones de usuarios en redes.

## 2. Construcción del corpus

El corpus se construyó ex profeso entre septiembre y octubre de 2026 y se sistematizó en cuatro capas:

- **Capa A — Fuentes corporativas primarias (n = 12)**: términos y condiciones, páginas de preguntas frecuentes, centro de ayuda (Intercom), página del Club Cashea Más y comunicados de la sección Novedades —incluido el informe técnico oficial de la filtración de datos de febrero de 2026—. Fijan la gramática oficial del sistema de clasificación: umbrales de nivel, reglas de ascenso y descenso, escalera punitiva, cláusulas de mutabilidad.
- **Capa B — Hitos corporativos y de contexto (n = 15)**: trayectoria 2022-2026, escala y financiamiento, la primera producción académica y divulgativa sobre la empresa (UNIMET 2025; UNY 2026) y la filtración de datos de febrero de 2026, según declaraciones a medios y documentos oficiales.
- **Capa C — Cobertura de prensa (n = 17)**: el conflicto de octubre de 2025 y los acontecimientos asociados (rondas de inversión, emergencia de junio-julio de 2026, filtración de datos de febrero de 2026, verificación de rumores). Es la columna vertebral empírica del caso: documenta el cambio unilateral, la protesta y la reversa parcial con fechas y citas.
- **Capa D — Publicaciones públicas en redes sociales (n = 14)**: Instagram, Facebook, TikTok, Reddit y X; producidas por usuarios, medios y cuentas corporativas.

### Criterios de inclusión

1. **Publicidad**: fuentes abiertas, sin cercos de pago ni de sesión para su localización.
2. **Identificabilidad**: autor o cuenta y fecha determinables.
3. **Relevancia directa** para el sistema de clasificación de usuarios.
4. **Verificabilidad**: ninguna fuente entra al corpus sin superar el procedimiento de verificación (sección 4).

### Criterios de exclusión

Contenido tras cercos de pago o de sesión sin copia pública localizable; publicaciones no datables; rumores sin cobertura periodística ni documento corporativo que los respalde; capturas de pantalla sin URL de origen.

## 3. Procedencia de la búsqueda

La literatura académica se localizó mediante búsquedas académicas sistemáticas (octubre de 2026) con estas consultas y ventanas:

- «ranking rank valuation sociology» (2020-2026)
- «buy now pay later» (2022-2026)
- «fintech financial inclusion stratification Global South» (2022-2026)
- «netnography social media research ethics» (2022-2026)
- «algoritmos percepción narrativas América Latina» (2022-2026)
- «crédito digital Brasil / México financiarización» (2022-2026)
- «Cashea Venezuela BNPL» (2022-2026; consulta específica sobre la empresa, sin resultados en bases académicas)

La consulta específica sobre la empresa se complementó con búsqueda web dirigida (16-10-2026), que localizó la única producción académica existente sobre Cashea: un artículo arbitrado (Tovar Gutiérrez & Arévalo Molina, 2026, *Decisiones*, UNY, 3(1), 28-46; metadatos OJS verificados) y un análisis financiero-divulgativo (Sanabria Rotondaro, 2025, UNIMET / FACES Business Review). Ambos trabajos se incorporaron al corpus y a las referencias del capítulo. Ninguno aborda el sistema de clasificación de usuarios ni el conflicto de octubre de 2025, de modo que el vacío empírico que el capítulo identifica se precisa —la literatura sobre Cashea es incipiente y proviene de otras disciplinas— pero no desaparece: la clasificación como forma de poder y su contestación pública siguen sin literatura.

Las fuentes primarias y la prensa se localizaron mediante búsqueda web dirigida (documentos oficiales de cashea.app e intercom.help/cashea; cobertura del evento del 13-16 de octubre de 2025 en 2001online, Radio Miraflores, El Nacional, Correo del Caroní y Hora Crítica; cobertura de contexto en Forbes Colombia, Banca y Negocios, Finanzas Digital, Contrapunto, Caracas Chronicles, Startupeable, Endeavor, Latam Fintech, Bloomberg y El Estímulo; posts públicos en Instagram, Facebook, TikTok, Reddit y X).

## 4. Verificación de enlaces (15-10-2026)

Doble vía:

1. **Solicitud automatizada** con agente de usuario de navegador. Resultado esperado: HTTP 200.
2. **Vía alternativa** cuando el portal bloquea robots (403/429/sin respuesta): apertura directa del contenido o verificación del DOI contra la base Crossref (`api.crossref.org/works/{DOI}`).

Ninguna fuente entró al corpus sin superar una de las dos vías. El resultado completo está en `verificacion/registro_verificacion_enlaces.csv`. La verificación detectó y corrigió tres DOI erróneos que circulan en la literatura (Kozinets, 2002; Marres & Gerlitz, 2016; Bucher, 2017) y precisó los datos de volumen y páginas de ocho referencias vía Crossref.

Adicionalmente, cada pieza periodística fue sometida a **verificación de autoría** (metadatos `author` de la página, esquema JSON-LD y firma visible), conforme a los requisitos de APA 7. El procedimiento reveló dos particularidades: (i) las piezas publicadas por Correo del Caroní son contenido republicado de otros medios del grupo —la del 15-10-2025 firmada por *La Verdad* y las de 16-10-2025 y 23-02-2026 por *El Nacional*—; (ii) la pieza de Correo del Caroní del 16-10-2025 y la de El Nacional del mismo día son el mismo artículo (C. Silva), por lo que en las referencias del capítulo se conserva únicamente la versión original. La autoría de cada pieza consta en la columna «Autoría» de `corpus/capa_C_prensa.csv`.

## 5. Respaldos

- `respaldos/html/`: copias HTML de 16 páginas clave capturadas el 15-16-10-2026 (documentos normativos de Cashea —incluido el informe técnico de la filtración—, piezas de prensa centrales y la página OJS del artículo de Tovar Gutiérrez y Arévalo Molina). El respaldo de El Estímulo conserva la página de error HTTP 429 como evidencia documentada del bloqueo.
- `respaldos/texto_capturado/`: texto íntegro recuperado vía buscador de las páginas con bloqueo anti-robots (Centro de Ayuda Intercom; portales de UNIMET, Efecto Cocuyo y El Estímulo) y de las publicaciones en redes descritas en la capa D.

Se recomienda como tarea de preservación adicional archivar las URL de la capa A en archive.org o perma.cc y guardar capturas de pantalla fechadas de las páginas de niveles y de la escalera punitiva antes del envío final del manuscrito.

## 6. Consideraciones éticas

Se trabaja solo con contenido público, conforme a las directrices AoIR 3.0 (franzke et al., 2020) y a la discusión sobre ética de la netnografía (Paoli, 2025). Se evaluó la expectativa contextual de privacidad de cada fuente. En el capítulo, las cuentas de usuarios particulares se seudonimizan (se citan plataforma, fecha y contenido); las cuentas corporativas y de medios se citan nominalmente. Los posts se emplean como material ilustrativo de las narrativas en circulación, no como evidencia representativa de su distribución.

## 7. Alcance declarado

El estudio es una **primera aproximación** documental. Sus hipótesis deberán contrastarse en una fase posterior mediante entrevistas en profundidad con usuarios y, de ser posible, con ejecutivos de Cashea.
