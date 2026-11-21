# Parte · Desmenuzado · 21 nov 2026 (01:40 Madrid)

## Lo importante: el tope de 10 al día es de vidIQ, no de YouTube
Al reintentar s21, vidIQ respondió con un mensaje nuevo:
- Hoy ya se habían gastado las **10 subidas a YouTube a través de vidIQ**.
- El contador se reinicia a **medianoche del Pacífico (09:00 Madrid)**.

Eso explica que el 19 y el 20 nov entraran exactamente 10. **No hace falta esperar 24 h desde el fallo:** basta con esperar a las 09:00 de Madrid. Lo dejo apuntado para que el capitán lo pase a las directrices (sección B), porque afecta también a Visceral si sube por vidIQ.

## Hecho en este turno (sin subir nada)
Dejé creados **14 borradores** completos (título, descripción, etiquetas, público, categoría 28 y fecha):

| Vídeos | Publicación |
|---|---|
| s21–s24 | 30 nov – 1 dic |
| L9 v2 patatas de bolsa | 2 dic, 14:00 |
| s25–s29, s31–s34 | 3–7 dic |

- **Descripción del L9:** enlaza al L5 v2 y al Short C9.
- **C11 y C12:** no tienen borrador todavía. Se crean en cuanto el L9 tenga enlace, porque lo llevan arriba.
- **Lista con IDs:** `dz/posts_pend.txt`.

## Próximo paso
- **Hoy a las 09:10 Madrid** (`trig_015JPS…`) se publican s21 → s24 → L9 → C11 → C12 → s25 → s26 → s27 (10).
- **Mañana a las 09:10** se publica el resto: s28, s29, s31–s34.
- **Cobertura:** después de esta tanda el canal tendrá vídeo programado cada día hasta el 4 dic; con la de mañana, hasta el 7 dic.

## Créditos
- **vidIQ:** 0 créditos. Quedan 165 de 200.
- **ElevenLabs:** 0 caracteres.

## Actualización a las 09:15 Madrid: 10 subidas
| Vídeo | ID de YouTube | Publicación (Madrid) |
|---|---|---|
| s21 umami | AqQIYHEtCCs | lun 30 nov, 14:00 |
| s22 huevo que flota | 3sXCHOAQhCU | lun 30 nov, 20:00 |
| s23 anacardos | qKUAL8wIKfY | mar 1 dic, 14:00 |
| s24 agua con gas | Py9TLEYejy4 | mar 1 dic, 20:00 |
| L9 v2 patatas de bolsa | CUIrqgO9Bss | mié 2 dic, 14:00 |
| C11 se ablandan | oARUtPB-GH4 | mié 2 dic, 14:00 |
| C12 acrilamida | wCPB6Cpm3-c | mié 2 dic, 20:00 |
| s25 plátano en la nevera | PJjaEVJUWl0 | jue 3 dic, 14:00 |
| s26 pimientos | EIeZ5UZRDJ8 | jue 3 dic, 20:00 |
| s27 bolsa de patatas | gSVoaf36HLo | vie 4 dic, 14:00 |

- **Fallida:** s28, por el tope de vidIQ (10 al día). Se confirma el reinicio a las 09:00 de Madrid.
- **Pendientes:** s28, s29 y s31–s34, en borradores. Se publican **mañana, 22 nov, a las 09:10** (`trig_01MorEb8…`). Con eso todo lo empezado queda programado hasta el 7 dic.
- **Créditos:** 0 de vidIQ (quedan 165 de 200) y 0 caracteres de ElevenLabs.

### Para el capitán en Studio
**«Vídeo relacionado»:**
- C9 (Y6MxKB2OHHI) y C10 (H3dA2N0tanE) → L5 v2 (OeIUhYiW2r8).
- C11 (oARUtPB-GH4) y C12 (wCPB6Cpm3-c) → L9 v2 (CUIrqgO9Bss).
- Siguen pendientes los del parte del 19 nov:
  - C1 y C2 → L1 v2.
  - C7 y C8 → L4 v2.

**Otras comprobaciones:**
- BRMSctql5Lc sin fecha.
- «No está creado para niños».

## Actualización 16:15 — orden del capitán del 21 nov (llenar diciembre)

### Programado y cobertura
- **Ya en YouTube (programado):** todo hasta el 4 dic a las 14:00 (s27).
- **En borrador con su fecha puesta:** 34 vídeos, del 4 dic (s28) al 21 dic, a 2 Shorts al día desde el 8 dic. El calendario completo está en `claude/desmenuzado-calendario.md`.
- **El canal queda cubierto hasta el 21 dic** en cuanto se publiquen los borradores.
- **Hoy no se ha publicado nada:** el tope de vidIQ de hoy ya estaba gastado. Hay una tarea programada que publica por orden de fecha:
  - 22 nov, 09:20 (`trig_017jV2Dg…`): 10.
  - 23 nov: 10.
  - 24 nov: 10.
  - 25 nov: 4.
  - Todo debería quedar programado antes del 30 nov.
- **Fallo de vidIQ encontrado y corregido:** s35, C13, s36 y C14 tenían la fecha vacía en el borrador. Si se hubieran publicado así, habrían salido al momento. Ahora tienen su fecha, y la tarea comprueba la fecha de cada borrador antes de publicarlo.

### Vídeos nuevos (todos revisados: 5 fotogramas cada uno y entre −14,3 y −15,0 LUFS)
- **Shorts con voz nueva (18):** s35–s52.
- **Clips de los largos (12):** C13, C14, C17, C18, C19, C20, C21, C23 y C26 (L1/L4/L5/L9), más C25. Todos tienen:
  - un rótulo con la pregunta en el primer fotograma (nuevo: `rotulo.py`);
  - el enlace al largo en la primera línea de la descripción.
  - A C13, C14 y C17 se les cambió el vídeo en el borrador por la versión con rótulo.
- **Descartados:**
  - C15: repite C2 (piel de la salchicha).
  - C24: repite C11 (patatas que se ablandan).
  - C16 y C22: encuadre malo.
  - En su lugar se hicieron C25 (sal de las patatas de bolsa) y C26 (salchicha y mayonesa).
- **Corregido antes de subir:** el final de s40 (el vaso y la remolacha se salían del encuadre).

### Caracteres de ElevenLabs (presupuesto de Desmenuzado: 9.000)
| Vídeo | Caracteres | Vídeo | Caracteres | Vídeo | Caracteres |
|---|---|---|---|---|---|
| s35 | 492 | s41 | 470 | s47 | 496 |
| s36 | 485 | s42 | 487 | s48 | 508 |
| s37 | 484 | s43 | 492 | s49 | 533 |
| s38 | 487 | s44 | 503 | s50 | 474 |
| s39 | 533 | s45 | 490 | s51 | 487 |
| s40 | 473 | s46 | 480 | s52 | 454 |

- **Total:** 8.828 de 9.000. Quedan 172, que no alcanzan para otro guion.
- **Contador de la cuenta:** unos 306.435 de 320.281, así que el saldo total ronda los 13.800.
- **Clips:** 0 caracteres.
- **vidIQ:** 0 créditos usados en este turno. Quedan 165 de 200.

### Para el capitán en Studio
- **«No está creado para niños»:** en todos los vídeos nuevos (s28–s52 y los clips C13–C26) cuando aparezcan en Studio.
- **«Vídeo relacionado»** (los IDs saldrán al publicarse; se apuntarán en `registro.md`):
  - C13, C14, C23 y C26 → L1 v2 (2i7Lkg1wQtI).
  - C17, C18 y C19 → L4 v2 (-YEdYigtPso).
  - C20 → L5 v2 (OeIUhYiW2r8).
  - C21 y C25 → L9 v2 (CUIrqgO9Bss).
- **Pendientes de partes anteriores:**
  - C1 y C2 → L1 v2.
  - C7 y C8 → L4 v2.
  - C9 y C10 → L5 v2.
  - C11 y C12 → L9 v2.
  - Comprobar que BRMSctql5Lc sigue sin fecha.
- **Borradores de vidIQ que no hay que publicar:** C15 (`04e9d453…`) y C24 (`376071e9…`). Se pueden borrar desde vidIQ si molestan.
