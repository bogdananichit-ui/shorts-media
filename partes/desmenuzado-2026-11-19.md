# Parte · Desmenuzado · 19 nov 2026 (turno de 00:53 a 02:30, Madrid)

Orden del capitán del 19 nov: retomar la sección A, subir de uno en uno por fecha y empezar por el L1 v2.

## Resumen
- **YouTube dejó subir 10 vídeos** (de 00:56 a 01:00 Madrid). El 11.º (C9) dio `uploadLimitExceeded`. Primer dato del límite real del canal sin verificar: unos **10 al día**.
- **Programado sin huecos hasta el 25 nov** (L5 incluido). Lo que falta (C9 en adelante) espera al reintento del **20 nov a las 01:25**, que ya está programado.
- **Render terminado:** los 34 Shorts están renderizados, revisados (5 fotogramas cada uno, entre −14,3 y −14,9 LUFS) y en la biblioteca de vidIQ. No queda nada a medio hacer.

## Subidas de hoy (10)
| Vídeo | ID de YouTube | Publicación (Madrid) |
|---|---|---|
| L1 v2 salchicha | 2i7Lkg1wQtI | jue 19 nov, 14:00 |
| L4 v2 queso | -YEdYigtPso | sáb 21 nov, 14:00 |
| C7 suero | Abwl3_6Jn3A | sáb 21 nov, 14:00 |
| C8 mozzarella | _6AKscawh2k | sáb 21 nov, 20:00 |
| s08 miel | 686GyVrs8Xk | dom 22 nov, 20:00 |
| s09 leche | BECbcHwEm6s | lun 23 nov, 14:00 |
| s10 aceite en la pasta | OG4ZO6tJcRw | lun 23 nov, 20:00 |
| s11 huevo cocido | eUECrVxxVvc | mar 24 nov, 14:00 |
| s12 kétchup | aNL3rizWzlY | mar 24 nov, 20:00 |
| L5 v2 chocolate | OeIUhYiW2r8 | mié 25 nov, 14:00 |

- **Fallida:** C9 (se funde en la boca), 01:00 Madrid, `uploadLimitExceeded`.
- **Cambio en lo ya creado:** L1 v1 (BRMSctql5Lc) pasado a **privado** con vidIQ, por orden del capitán (5 créditos).
- **Enlaces en las descripciones:**
  - L4 enlaza al L1 v2 y a s06.
  - L5 enlaza a s06 y al L4.
  - C7 y C8 enlazan al L4.

## Pendiente de subir (por fecha; IDs en `dz/posts_pend.txt`)
| Fecha | Vídeos |
|---|---|
| 25 nov | C9 (borrador a608ec0a, falló) y C10 (borrador 855eb902) |
| 26 nov | s13 (borrador 1aa599f4) y s14 |
| 27 nov – 1 dic | s15–s24 (2 al día) |
| 2 dic | L9 v2, C11 y C12 |
| 3–7 dic | s25–s29, s31–s34 |

- Todo está en la biblioteca de vidIQ.
- Calendario completo: `claude/desmenuzado-calendario.md`.
- s30 no se publica, porque repite C8.

**Cuándo entra cada cosa:** a unos 10 al día, el 20 nov entraría hasta s20 o s21 y el 21 nov el resto.

## Para el capitán en Studio
- **BRMSctql5Lc (L1 v1):** está en privado, pero comprueba que no le quedó la fecha del 19 nov 14:00. vidIQ no deja ver si se borró la programación.
- **«Vídeo relacionado»:**
  - C1 (6fM8aKutK_8) y C2 (1ti0SdbETJQ) → L1 v2 (2i7Lkg1wQtI).
  - C7 (Abwl3_6Jn3A) y C8 (_6AKscawh2k) → L4 v2 (-YEdYigtPso).
- **Descripción de C1 y C2:** añadir arriba «▶ El vídeo completo: https://www.youtube.com/watch?v=2i7Lkg1wQtI». Ahora no enlazan al L1 v2.
- **«No está creado para niños»:** la herramienta de vidIQ no tiene esa opción. Revisa los 10 subidos hoy por si Studio lo pide.

## Créditos
- **vidIQ:** 5 este turno (update_video de BRMSctql5Lc). Saldo total: 569. Quedan **165 de 200** del canal hasta el 12 dic.
- **ElevenLabs:** 0 caracteres. Hoy no se generó voz.

## Fallos y notas
1. **El entorno se reinició dos veces** y cortó el render. Lo relancé y se terminó.
2. **`shorts-media` se quedó a mitad de un rebase** por un choque con un archivo de Desmontado (`45-rueda-al-reves.mp4`). Me quedé con la versión remota y no toqué nada de Desmontado.
3. **Defectos menores vistos en la revisión** (no se volvieron a renderizar):
   - s19: el rótulo «HORAS FUERA DE LA NEVERA» se corta por la derecha.
   - s31: hay un segundo de escena vacía hacia el 0:28.
   - s27: repite la respuesta del L9 (el nitrógeno), pero sale 2 días después.
4. **Por qué paro:** el render está terminado y YouTube no deja subir más hasta pasadas 24 h. El reintento del 20 nov a las 01:25 (`trig_01GScFrh…`) sigue por C9.
