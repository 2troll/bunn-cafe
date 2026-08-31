# BUNN — Tostador de café de especialidad

Sitio de **diez páginas** en español, inglés y árabe con RTL real, para una
tostadora de café de especialidad.

**Ver online:** https://2troll.github.io/bunn-cafe/

`بُنّ` es la palabra árabe para el grano de café, y la raíz de la que salieron
«café», «coffee» y «Kaffee». De ahí el nombre y de ahí la paleta: el fondo es
el color del grano tostado, el acento es el ocre del tueste y el verde
secundario es el color del grano crudo, antes de pasar por el tambor.

## Las diez páginas

`Inicio` · `Cafés` · `Orígenes` · `Tueste` · `Cata` · `Suscripción` ·
`Hostelería` · `Preparación` · `Preguntas` · `Contacto`

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

## Detalles de traducción

- 112 claves × 3 idiomas, paridad exacta; 13 estructuras paralelas.
- **Concordancia de número**, que es donde se cae casi todo el mundo:
  `un origen` / `4 orígenes`; en árabe `منشأ واحد` (1), `منشأين` (2),
  `٤ مناشئ` (3–10) y `١٢ منشأً` (11+). En inglés la frase se reformuló para
  que el verbo valga en singular y plural.
- Dígitos árabe-índicos pedidos con `ar-u-nu-arab`.
- `letter-spacing: 0` en los rótulos árabes: espaciarlos rompe las ligaduras.
- `background-position` del desplegable reflejada a mano.

## Comprobado

```
112 claves × 3 idiomas    paridad ✔ · 0 sin traducir
10 rutas × 3 idiomas      0 fugas de idioma
3 perfiles de tueste      curva + 3 marcas cada uno
3 cafés en el radar       6 ejes · tabla 6×4
calendario                11 bandas · 6 pistas · alineadas en LTR y RTL
```

---

**Maqueta de demostración.** Empresa ficticia. Las ventanas de cosecha y las
proporciones de preparación son reales; los precios y los lotes, de ejemplo.
