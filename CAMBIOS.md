# Registro de cambios – Juegos de Celia

## v4 (2 oct 2026)
- Parejas: tableros más grandes. Por defecto 6 parejas (12 cartas, 3x4); se puede elegir hasta 8 parejas (16 cartas, 4x4) en el panel.
- Varias fotos por persona y por tipo (01/02 actuales, 03 de pequeño): el juego elige una distinta cada partida.
  Archivos: NOMBRE_01a.jpg, NOMBRE_01b.jpg… (carga en lote del panel y generar_datos.py).
- Memoria usa dos fotos distintas de la misma persona, tomadas de todas sus fotos actuales (01 y 02 juntas).
- Nunca se muestra el nombre en las cartas de fotos (v3).
- Cache del servicio: juegos-madre-v4.

## v5 (2 oct 2026)
- Sopa de letras: palabras en horizontal, vertical y diagonal (siempre izquierda->derecha o arriba->abajo). Tableros más compactos. Se puede arrastrar o tocar inicio y fin.
- Parejas: fotos sin recortar (se ve la foto entera); carta acertada atenuada con tic verde; mensajes de ánimo variados al acertar.
- Quitados "Marido y mujer", "Padres e hijos" y "Hermanos". Nuevo "¿Quiénes son...?" (Parejas): pregunta + panel de 6 fotos, solo valen las respuestas correctas.
- Juego nuevo "Busca el objeto" (sin datos): 30-36 objetos, 5 por partida, pista tras 3 fallos.
- Juego nuevo "Diferencias": 13 fotos x 3 versiones x 7 diferencias (en el JSON privado, panel: fotos de diferencias).
- Ajustes: parejas mínimo 6; nuevo ajuste "Busca el objeto: dibujos".
- Disposición de Parejas: se mantiene la que mejor encaja en pantalla (no se fuerza vertical/horizontal por dispositivo).
- Cache del servicio: juegos-madre-v5.

## Pendiente de la revisión de César
(Anotar aquí lo que vaya encontrando al probar todos los juegos en la tablet.)
