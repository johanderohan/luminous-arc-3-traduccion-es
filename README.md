# Luminous Arc 3: Eyes — Traducción al español

[![Invítame a un café en Ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/johanderohan)

Traducción al **español de España** de *Luminous Arc 3: Eyes* (ルミナスアーク3 アイズ,
Nintendo DS, 2009), el RPG táctico de imageepoch publicado por Marvelous Entertainment,
que solo salió en Japón. Es una traducción **directa del japonés**.

La traducción se reparte como **parche**: no incluye el juego. Necesitas tu propia
copia de la versión japonesa para aplicarlo.

## Estado

Última versión: **[v1.0](../../releases/tag/v1.0)**.

| Parte | Estado |
|---|---|
| Guion (historia, conversaciones libres, finales, termas, subescenarios) | **28.497 registros traducidos** (todos los que tienen texto) |
| Opciones de diálogo y objetivos del mapa | Traducidos |
| Interfaz: objetos, equipo, habilidades, lapis, clases, lugares, menús, ayudas, biblioteca, secretos, diario de Kopin, consejos de combate | **3.984 unidades traducidas** |
| Gráficos con texto: menú de título, dificultad, menús, tienda, guardado, botones y carteles de combate, resultado, tarjetas de capítulo, carteles de mapa y capturas del tutorial | **76 ficheros gráficos traducidos** |
| Caracteres españoles | **á é í ó ú ü ñ Á É Í Ó Ú Ü Ñ ¡ ¿ « » “ ”** |

El juego original solo tenía una fuente japonesa de ancho fijo. El parche añade una
**fuente proporcional** con letras españolas (mismo color y contraste que el original),
así que el texto cabe en las cajas sin abreviaturas forzadas.

Se mantienen sin traducir, como parte de la imagen de marca, el logotipo y los rótulos
que ya estaban en inglés (OPTION, Action Order, Chapter…). Las voces y los vídeos de
anime se conservan tal cual.

### Comprobaciones y trabajo pendiente

Se ha jugado en emulador (DeSmuME) **desde partida nueva hasta el tercer combate**
(capítulo 2): prólogo, tutorial, los dos primeros combates completos, tiempo libre en
la academia, tienda, inventario y equipo, opciones, guardar en la tarjeta y continuar
desde el título. No hubo cuelgues. El resto del juego se ha revisado con
comprobaciones automáticas (límites de cada caja, bytes, caracteres y estructura de
todos los ficheros), pero **no se ha jugado de principio a fin**.

La traducción y la revisión se han hecho con ayuda de inteligencia artificial, con
biblia de personajes y términos, revisión de coherencia y pruebas en emulador, pero
**sin revisión humana independiente**. Si encuentras errores, abre una incidencia.

Pendiente o conocido:

- Algunos gráficos siguen en japonés: las marcas de agua del diagrama de atributos,
  las cabeceras del menú Extra, alguna pantalla del taller de alquimia y un rótulo
  grande de un evento concreto.
- En la lista «Action Order» del combate los nombres van en versalitas pequeñas y,
  a veces, con un hueco entre dos letras.
- Al usar «Saltar» puede verse un instante la caja de diálogo a medio dibujar.

## Cómo aplicar el parche

1. Descarga el parche `.xdelta` de la sección **[Releases](../../releases)**.
2. Consigue tu copia del juego en versión **japonesa**. El parche solo funciona con
   esa versión exacta.
3. **Comprueba que tu copia es la correcta** antes de nada:

   | | |
   |---|---|
   | Archivo | `Luminous Arc 3 - Eyes (Japan).nds` |
   | Tamaño | 134.217.728 bytes (128 MB) |
   | MD5 | `0e6e1fe020844193ff2219d8fbca4b6c` |

   ```bash
   md5sum "Luminous Arc 3 - Eyes (Japan).nds"     # Linux
   md5 "Luminous Arc 3 - Eyes (Japan).nds"        # macOS
   CertUtil -hashfile "Luminous Arc 3 - Eyes (Japan).nds" MD5   # Windows
   ```

   Si no coincide, el parche fallará o dará un resultado corrupto.
4. Aplica el parche con una de estas herramientas:
   - **Windows**: [Delta Patcher](https://github.com/marco-calautti/DeltaPatcher/releases)
   - **Linux / macOS**: `xdelta3 -d -s "juego original.nds" parche.xdelta "juego traducido.nds"`
5. Para **v1.0**, comprueba que la ROM resultante tiene MD5
   **`4da632e1a86ff5e794d86016e3022860`** (134.217.728 bytes).
6. Carga la ROM resultante en tu emulador o flashcard preferidos.

## Cambios

- **v1.0**: primera versión pública.

## Créditos

- Traducción, fuente y herramientas: johanderohan.
- Los rótulos gráficos usan las tipografías libres Fira Sans y DejaVu Serif.

## Aviso

Este proyecto es una traducción hecha por afición, sin ánimo de lucro y sin relación
alguna con imageepoch ni Marvelous. Aquí no se distribuye el juego ni ninguna parte
de él: solo un parche que modifica una copia que ya tengas.

Si eres el titular de los derechos y quieres que retire esto, abre una incidencia
y lo hago.
