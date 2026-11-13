# Cambios

Cada versión nueva se anota arriba de todo.

## v0.2.0 — 2026-11-13 · Juego completo

- **Ajustes para padres** (mantener apretado el engranaje 1,5 segundos):
  - Modo **automático**: "desde la del", "ahora practica hasta la del" y "puede llegar hasta la del". Cuando domina la última tabla (8 de 10 cuentas sabidas), suma la siguiente sola sin pasar el techo.
  - Modo **manual**: rango fijo "desde / hasta".
  - Multiplicar hasta ×10 o ×12, mezclar el orden (3×4 y 4×3), velocidad (automática, lenta, normal, rápida) y voz.
  - Mapa de progreso por cuenta (sin ver, le cuesta, aprendiendo, casi, la sabe) y botón para borrar el progreso.
- **Aprende de verdad**: cada cuenta guarda cuántas veces la acertó a la primera. Las que cuestan salen más seguido y las que ya sabe salen menos.
- Si falla una cuenta o se le escapa, **vuelve 3 pompas más tarde** en la misma ronda.
- Cuando una pompa se escapa, se marca la respuesta correcta y la voz la dice.
- **Velocidad automática**: si acierta 9 o más a la primera, la próxima ronda es un poco más rápida; si acierta 5 o menos, más lenta.
- **Puntos**: 10 a 20 por pompa a la primera (más si es rápido), 5 si la revienta después de equivocarse, +5 por racha de 3 o más, y +50 por reventar las 10.
- **Monedas** propias (puntos ÷ 10) y **tienda** con 6 pompas (clásica, chicle, menta, dorada, galaxia, arcoíris) y 5 fondos (atardecer, cielo, noche, mar, caramelo).
- Pantalla **Mis tablas** con 0 a 3 estrellas por tabla y candado en las que todavía no se desbloquearon.
- Fin de ronda con aviso de tabla nueva y lista de cuentas "para repasar".
- Voz que lee la cuenta y botón de sonido en el inicio.
- El progreso se guarda en el navegador de cada dispositivo.

## v0.1.0 — 2026-11-13 · Maqueta estética

Primera versión para aprobar el aspecto, todavía sin la lógica completa.

- Pompas de jabón tornasoladas que suben y tiemblan como las de verdad.
- Pantalla de inicio "¡Revienta Tablas!" con pompas de fondo que se pueden reventar.
- Ronda de prueba de 10 pompas con tablas del 1 al 4 y 4 respuestas abajo.
- Al acertar, la pompa revienta con gotitas de colores, sonido y puntos (más puntos si es rápido).
- Al equivocarse, la pompa se sacude y esa respuesta se apaga; no resta puntos.
- Si llega al techo de nubes se escapa volando y no suma.
- Pantalla final con 1 a 3 estrellas, aciertos y puntos (+50 si hace 10 de 10).
- Tres fondos para elegir: atardecer, cielo y noche.

### Falta (próximas versiones)

- Ajustes para padres: rango de tablas manual o automático con techo.
- Registro de qué cuentas sabe y cuáles le cuestan.
- Velocidad que se adapta, voz que lee la cuenta, monedas y tienda propia.
