# Parte · Desmenuzado · 26 nov 2026 (09:15Z)

## Programado hoy: 5 subidas, sin fallos
| Vídeo | ID | Sale |
|---|---|---|
| s51 leche cortada | ODam2Ps0E98 | 20 dic 14:00 |
| s52 aquafaba | NVf9o7eDROA | 20 dic 20:00 |
| s48 burbujas del cava | wDWCeNMPEEM | 21 dic 14:00 |
| s49 doce uvas | _nql3XhaliI | 21 dic 20:00 |
| C27 patatas de tubo (recorte de L9, nuevo) | _rFTEh8pQog | 26 dic 14:00 |

- **El canal queda programado en YouTube hasta el 21 dic, con 2 Shorts al día.** Ya no queda ningún borrador.
- **Huecos:** del 22 al 25 dic no hay vídeo hasta que se grabe el lote del 30 nov (ver abajo). El 26 dic solo hay un Short (C27).

## Directrices v6: lote de voz del 30 nov, preparado
- **Guiones:** 8 Shorts nuevos (s53–s60, 3.721 caracteres en total), con la estructura nueva: la respuesta en la primera frase, antes del segundo 5. Los temas son de supermercado, del tipo «¿sabes qué lleva / cómo se fabrica X?»:

  | Short | Tema | Caracteres |
  |---|---|---|
  | s53 | Palitos de cangrejo sin cangrejo | 469 |
  | s54 | Queso rallado con celulosa | 476 |
  | s55 | Nata de spray | 450 |
  | s56 | Leche condensada | 446 |
  | s57 | Zumo de concentrado | 478 |
  | s58 | Descafeinado | 491 |
  | s59 | Aceitunas rellenas de anchoa | 467 |
  | s60 | Gominolas con gelatina | 444 |

- **Revisión de los guiones:** ortografía pasada con `orto.mjs` (solo marca nombres propios). Cada cifra tiene su fuente, apuntada en `lote_30nov.md`.
- **Escenas 3D:** las 8 están hechas (`escenas/s53–s60.js`). Las he probado con tiempos aproximados (`tiempos_falsos.py`, `previa.sh`) y he corregido el encuadre. Cuando haya voz, `tiempos.py` sustituye los tiempos aproximados.
- **Títulos:** siguen la regla de la v6 (afirmación concreta o pregunta con dato y 2 hashtags), por ejemplo «Los palitos de cangrejo no llevan cangrejo 🦀».
- **Fechas:** del 22 al 25 dic, a las 13:00Z y a las 19:00Z.
- **Tarea programada:** `trig_01CMumzc…` arranca el 30 nov a las 18:30Z. Primero comprueba que ElevenLabs se ha renovado; si no, reintenta 2 h más tarde. Después graba los 8 dentro del 25 % de Desmenuzado, renderiza, revisa y programa.
- **Otras ideas de recorte que he descartado:**
  - El de los chocolates (L5 n4) repetía s06.
  - No quedan más capítulos de largos de 25–35 s que no repitan otros Shorts.

## Recursos
- **vidIQ:** 0 créditos. Quedan unos 160 del canal.
- **ElevenLabs:** 0 caracteres (agotado hasta el 30 nov).

## Fallo arreglado
- El clon compartido `shorts-media` se quedó a medias en una reorganización de 56 commits por un `pull --depth=1`.
  - La aborté y volví a poner encima solo C27. No se perdió nada de los otros canales.
  - `subir.sh` ya no usa `--depth=1`.

## Para el capitán en Studio
- Nada pendiente.
