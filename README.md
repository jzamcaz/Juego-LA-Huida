# La Huida

Juego de terror en el bosque, hecho en un solo archivo HTML. Cruza el bosque de noche, esquiva a las criaturas y llega a la cabaña antes de que te cacen.

**by Dante Z**

**Jugar:** https://jzamcaz.github.io/Juego-LA-Huida/

Funciona en PC y en teléfono, sin instalar nada.

## Cómo se juega

- **Moverte:** WASD o flechas del teclado. En el teléfono, los botones táctiles.
- **Destello:** barra espaciadora (o el botón Destello). Gasta una carga de linterna, ilumina más lejos y paraliza a las criaturas cercanas.
- **Sonido:** tecla M. **Menú:** tecla R.

## Objetos

- **Pila amarilla:** recarga 2 cargas de linterna.
- **Amuleto azul:** las criaturas se mueven mucho más lento durante 10 segundos.
- **Lente blanca:** tu luz llega más lejos para siempre (hasta 6 lentes).
- **Llave dorada:** desde la noche 80 la cabaña está cerrada y hay que encontrarla.

## Reglas

- Son **100 noches**. Cada noche el bosque es más grande (de 15×10 a 60×36) y aparecen más criaturas.
- Cada 20 noches cambian los colores del bosque y de las criaturas, y se vuelven más difíciles de distinguir.
- Hay **punto de control** al superar las noches 20, 40, 60 y 80. Si te cazan, vuelves al último; si aún no tienes ninguno, empiezas desde la noche 1.
- Al superar la noche 100 se desbloquea el logro final.

## Notas técnicas

- Un único archivo (`index.html`), sin dependencias ni compilación. Usa canvas 2D y la API de audio del navegador.
- El progreso (noche guardada, punto de control y mejor noche) se guarda en el navegador de cada dispositivo y no se comparte entre dispositivos.
