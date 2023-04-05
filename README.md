# Tienda-Online

Posisionamiento

Static: posición por defecto de los elementos.
Es el único caso en el que no se puede utilizar top, right, bottom ni left.

Absolute: los elementos permanecen en la posición donde fueron colocados, pero pierden su espacio físico, es decir, se sobreponen en otros elementos. Aclaración: para poder aplicar este valor, el contendor padre debe tener position relative.

Relative: conservan su posición original y espacio físico, pero podemos moverlos con las propiedades top, right, bottom, y left.

Fixed: pierden su espacio físico y permanecen de forma fija.

Sticky: conservan su espacio físico, pero cuando el scroll los alcanza lo siguen sin perder dicho espacio físico.
Es muy usado para barras de navegación.

Initial: vuelve el position de un elemento a como estaba originalmente.

Inherit: hereda el position de su padre.

¿Qué logra object-fit en CSS?
A las imágenes le aplicamos la propiedad object-fit, ya que resuelve como el contenido se ajustará a su contendor.

Sus valores pueden ser:

contain → mantiene la relación de aspecto mientras le ajusta dentro del contendedor.
cover → mantiene la realción de aspecto, pero la ajusta para llenar el contenedor.
fill → modifica su tamaño para llenar el contenedor.
none → no se redimensiona.
scale-down → el contenido se dimensiona como si none o contain estuvieran especificados, lo que resulta en un tamaño de objeto concreto más pequeño.