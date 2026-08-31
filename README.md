# BUNN — Tostador de café de especialidad

Sitio de **dieciséis páginas** en español, inglés y árabe con RTL real, para una
tostadora de café de especialidad.

**Ver online:** https://2troll.github.io/bunn-cafe/

`بُنّ` es la palabra árabe para el grano de café, y la raíz de la que salieron
«café», «coffee» y «Kaffee». De ahí el nombre y de ahí la paleta: el fondo es
el color del grano tostado, el acento es el ocre del tueste y el verde
secundario es el color del grano crudo, antes de pasar por el tambor.

## Las dieciséis páginas

`Inicio` · `Cafés` · `Orígenes` · **`Elige tu café`** · **`Receta`** ·
**`Qué va con qué`** · **`Comparar`** · `Tueste` · `Cata` ·
**`Trazabilidad`** · **`Cronómetro`** · `Suscripción` · `Hostelería` ·
`Preparación` · `Preguntas` · `Contacto`

Las seis en negrita son nuevas, y ninguna repite el formato de otra ni el de
los otros sitios:

| Página | Formato | Qué hace |
|---|---|---|
| **Elige tu café** | Asistente por pasos | Cuatro preguntas sobre cómo bebe usted el café —ninguna sobre notas de cata— y sale un café concreto y un formato. Se puede ir atrás |
| **Receta** | Calculadora bidireccional | Escriba gramos o mililitros y el otro campo se recalcula manteniendo la proporción del método. Con botones de ½, ×2 y ×4 |
| **Qué va con qué** | Mapa de calor | Seis cafés × seis métodos, de 0 a 5. Señala solo el más versátil y el más exigente |
| **Comparar** | Barras divergentes A/B | Dos cafés enfrentados en los seis ejes de cata, y dice en cuál se separan más |
| **Trazabilidad** | Línea de tiempo vertical | Un lote de Huila de la finca a la taza: ocho pasos y siete meses |
| **Cronómetro** | Temporizador por pasos | Cuenta, avanza solo, marca el paso activo y dice cuánta agua lleva echada. Con pausa y reinicio |

## Las tres piezas que no son adorno

- **Curva de tueste.** Temperatura contra tiempo para tres perfiles (filtro,
  espresso y omni), con el punto de giro, el primer crack y la salida marcados
  sobre la curva. Las curvas no son dibujos: se calculan con una exponencial
  de calentamiento y el instante del primer crack se despeja de la propia
  ecuación, así que si se cambia un perfil la marca se mueve sola.
- **Perfil de cata.** Radar de seis ejes con tres cafés, con tabla equivalente
  para que la identidad no dependa sólo de la forma.
- **Calendario de cosecha.** Ventanas reales por origen. Colombia y Kenia
  aparecen dos veces porque tienen cosecha principal y secundaria, y las
  ventanas que cruzan el fin de año se parten en dos bandas.

## Cómo están hechas las cifras

Las matrices numéricas —recetas, matriz café × método, perfiles sensoriales,
puntuación del asistente y pasos del cronómetro— viven **fuera** de los
diccionarios de idioma, en constantes compartidas. Así los tres idiomas leen
exactamente los mismos números y no pueden divergir, que es el fallo clásico
de traducir tablas a mano.

## Detalles de traducción

- 112 claves × 3 idiomas, paridad exacta; 13 estructuras paralelas.
- **Concordancia de número**, que es donde se cae casi todo el mundo:
  `un origen` / `4 orígenes`; en árabe `منشأ واحد` (1), `منشأين` (2),
  `٤ مناشئ` (3–10) y `١٢ منشأً` (11+). En inglés la frase se reformuló para
  que el verbo valga en singular y plural.
- Dígitos árabe-índicos pedidos con `ar-u-nu-arab`.
- `letter-spacing: 0` en los rótulos árabes: espaciarlos rompe las ligaduras.
- `background-position` del desplegable reflejada a mano.

## Fotografía

4 fotografías reales de **Wikimedia Commons**, todas con licencia libre
(CC0, CC BY o CC BY-SA), descargadas al repositorio y no enlazadas a un
tercero: si mañana desaparecen de Commons, el sitio sigue igual.

- Cada una lleva **texto alternativo traducido a los tres idiomas**, no un
  `alt` en español dentro de la versión árabe.
- Los créditos —título, autor y licencia con enlace— se muestran dentro del
  propio sitio y también cambian de idioma.
- Se redimensionaron a 1400 px de ancho; ninguna pasa de 500 KB.

Se descartó una candidata de fisioterapia que la licencia permitía usar pero
que retrataba a **un menor identificable**. En una maqueta comercial eso no se
publica aunque sea legal.

## Comprobado

```
181 claves × 3 idiomas    paridad ✔ · 0 sin traducir
16 rutas × 3 idiomas      0 fugas de idioma
16 enlaces del menú       los 16 navegan
desborde horizontal       0 px en las 16 rutas
cronómetro                corre, pausa y reinicia
3 perfiles de tueste      curva + 3 marcas cada uno
3 cafés en el radar       6 ejes · tabla 6×4
calendario                11 bandas · 6 pistas · alineadas en LTR y RTL
```

---

**Maqueta de demostración.** Empresa ficticia. Las ventanas de cosecha y las
proporciones de preparación son reales; los precios y los lotes, de ejemplo.
