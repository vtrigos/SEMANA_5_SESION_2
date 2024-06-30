# Box Model

Sirve para maquetear en base a cajas el diseño web, se divide en:
- Content box (Interno) : Contenido de texto
- Padding box (Interno) : espacios alrededor de context box
- Border box (Interno): Tamaño borde
- Margin box (Externo) : Márgenes alrededor de la caja a diferencia del padding este es externo hacia afuera y puede mover la caja según valores positivos y negativos, incluso superponerse.

El tema de colapsado es cuando 2 valores verticales adyacentes se cruzan o sobreponen tomará el mayor valor dejando sin efecto el menor valor.

## Selector universal
- (*) Seleccciona todos los elementos


## Box Sizing

- El box sizing permite que las dimensiones establecidas en una caja no varien al asignar valor a padding o border.


# Posicionamiento

Especifica donde posicionar un elemento en cualquier parte de nuestra web.

- Position Relative: Conserva las dimensiones originales y se desplaza usando propiedades de posicionamiento para mover distancias pequeñas o da contexto a absolute. 
- Position Absolute: No conserva dimensiones originales y depende de un elemento padre es decir el espacio (universo) donde se va a desplazar si no lo hubiera, se relaciona con el body.
- Position Fixed: Posiciona un elemento de forma fija siempre en la web, no se desplaza con el contenido de la página y no depende de nadie.
- Position Sticky: Parecido a fixed es decir fija un elemento la diferencia es que si permite desplazamiento hasta un limite establecido.

Cuando un elemento esta posicionado puede usar las propiedades: top, right, bottom, left, z-index.

## Propiedades de un elemento posicionado

- top: Desplaza elemento hacia arriba.
- right: Desplaza elemento hacia derecha.
- bottom: Desplaza elemento hacia abajo.
- left: Desplaza elemento hacia la izquierda.
- z-index: Permite mediante un número de posición la jerarquía para mostrar un elemento delante o detrás de otro elemento como si fueran capas.





