# Corpus documental del caso Cashea (Venezuela) — repositorio de investigación

Repositorio de datos y metodología que acompaña al capítulo **«El ranking que se mueve: poder algorítmico, mutabilidad unilateral y reactividad de usuarios en una plataforma BNPL venezolana (el caso Cashea)»**, estudio de caso exploratorio destinado a un libro colectivo (FACES-UCV).

El repositorio existe para hacer auditable la base empírica del capítulo: la totalidad de las fuentes primarias tabuladas, las citas textuales de cada documento, el registro de verificación de enlaces y los respaldos de las páginas consultadas.

## Estructura

```
├── README.md                        Este archivo
├── METODOLOGIA.md                   Metodología completa: diseño, criterios, búsqueda y verificación
├── corpus/
│   ├── capa_A_fuentes_corporativas.csv   12 documentos normativos corporativos
│   ├── capa_B_hitos_2022_2026.csv        15 hitos corporativos y de contexto
│   ├── capa_C_prensa.csv                 17 piezas de prensa (octubre 2025, filtración 2026 y contexto)
│   └── capa_D_posts_publicos.csv         14 publicaciones públicas en redes sociales
├── verificacion/
│   └── registro_verificacion_enlaces.csv Registro de la verificación del 15-16-10-2026
└── respaldos/
    ├── html/                        Copias HTML de las páginas clave, capturadas el 15-16-10-2026
    └── texto_capturado/             Texto íntegro recuperado vía buscador de páginas con bloqueo anti-robots
```

## Advertencias de uso

- **Cifras corporativas**: las cifras de escala (usuarios, volúmenes, pérdidas) son declaraciones de la empresa recogidas por la prensa; se registran como autorreporte corporativo, no como datos auditados.
- **Posts de redes sociales**: Instagram, Facebook, TikTok, Reddit y X bloquean la verificación automatizada. Todos los posts fueron localizados y descritos mediante búsqueda web el 15-10-2026 y/o están citados e incrustados en la cobertura periodística de la capa C. Se recomienda su preservación adicional en archive.today o perma.cc.
- **Ética**: el tratamiento de las fuentes sigue las directrices AoIR 3.0 (franzke et al., 2020). En el capítulo, las cuentas de usuarios particulares se seudonimizan; las cuentas corporativas y de medios se citan nominalmente por su carácter institucional. Este repositorio mantiene la trazabilidad completa de las fuentes públicas con fines exclusivamente académicos y de revisión por pares; quien lo consulte debe abstenerse de contactar, identificar o exponer a los usuarios citados.
- **Portales con bloqueo a robots**: unimet.edu.ve, efectococuyo.com y elestimulo.com no responden a la verificación automatizada (000/429); su contenido se comprobó por apertura directa y se conserva en `respaldos/texto_capturado/`.
- **Literatura sobre Cashea**: la búsqueda académica específica («Cashea Venezuela BNPL», 2022-2026) no arrojó resultados; la única producción existente (Tovar Gutiérrez & Arévalo Molina, 2026, UNY; Sanabria Rotondaro, 2025, UNIMET) se localizó por búsqueda web dirigida y está incorporada al corpus y a las referencias del capítulo. Ninguna aborda el sistema de clasificación ni su contestación.
- **Única página no disponible**: `cashea.app/releases/mmc-bajada-de-inicial` figura en el índice oficial de Novedades pero devuelve 404 al 15-10-2026; su contenido se documenta vía el índice y la cobertura de prensa.

## Licencia sugerida

Creative Commons Atribución 4.0 Internacional (CC BY 4.0) para la documentación y los datos tabulados. Las copias de respaldo de páginas de terceros se incluyen con fines de archivo académico y verificación, sin alteración de su contenido ni de sus derechos de autor.

## Contacto

[Nombre de la autora — afiliación — correo institucional]
