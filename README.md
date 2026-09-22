# Gunda Burger's

Maqueta de e-commerce de una hamburguesería ficticia, con HTML y CSS hasta la clase 7.
Se conservan tu marca, eslogan, nombres de productos, ingredientes, precios,
horario de cierre a las 23:30 y texto del pie. Se unificó la ortografía de la marca
en la historia y del mensaje de apertura.

## Abrir

Abrí `index.html` con doble clic. Para editar, abrí esta carpeta en VS Code.
Guardá con Ctrl+S y recargá el navegador. No hay dependencias ni instalación.

## Archivos

- `index.html`: contenido, navegación y formulario comentados.
- `css/estilos.css`: estilos comentados por declaración y organizados por componente.
- `img/doble-gunda.png`: imagen ilustrativa local generada para la portada.
- `img/ORIGEN.md`: procedencia y prompt de la imagen.
- `respaldo-inicial/index.html`: copia de tu HTML anterior a esta ampliación.
- `AGENTS.md`: alcance y preferencias para continuar el proyecto.

## Qué aplica de cada clase

| Clase | Aplicación |
| --- | --- |
| 1 | Estructura semántica, jerarquía h1/h2/h3, párrafos y comentarios |
| 2 | Enlaces internos, listas, imagen con alt, tabla de horarios y formulario |
| 3 | Hoja externa, selectores de etiqueta/clase/descendientes, cascada, herencia, colores, tipografías y unidades |
| 4 | Margin, padding, bordes, width, display y rótulo con position relative/absolute |
| 5 | Navegación y banda flexibles; tarjetas en columna, alineación y distribución |
| 6 | Catálogo por columnas, repeat, fr, separaciones y Grid por áreas |
| 7 | Viewport, mobile first, media queries y combinación de Grid con Flexbox |

La base móvil usa una columna. Desde 768 px, la portada y el catálogo pasan a
dos columnas. Desde 1100 px, el catálogo tiene cuatro columnas y la historia queda
junto al formulario. Desde 1440 px, el contenedor limita su ancho a 1240 px.

No forzamos todas las propiedades o etiquetas del curso si no aportan a la página:
no necesita video, iframe ni contenido oculto para funcionar como maqueta.
Las menciones a temas futuros en los PDF no cuentan como contenido desarrollado.

## Qué funciona

- Navegación entre menú, historia, contacto, opciones e inicio.
- Selección de hamburguesa, acompañamiento, salsa aparte y aclaraciones.
- Restablecer opciones: devuelve los valores iniciales con HTML nativo.
- Adaptación del diseño al ancho disponible.

El formulario es una demostración: no envía ni guarda datos. Los enlaces «Ver
opciones» llevan al mismo formulario; no seleccionan automáticamente un producto.
Los precios son texto fijo. No hay carrito, cálculos, pedidos, pagos ni servidor.

## Dónde modificar

- Marca y contenido: `index.html`.
- Colores: buscá los valores hexadecimales comentados en CSS.
- Tarjetas: clase `.producto`; distribución: `.productos`.
- Distribución historia/formulario: `.comunidad` y sus media queries.
- Anchos de adaptación: reglas `@media` al final del CSS.
- Producto nuevo: duplicá un `article` dentro de `.productos` y agregá su `option`
  al selector del formulario para mantener ambos listados coherentes.

## Criterio de comentarios

Comentarios breves, orientados a la función y la decisión de diseño. En CSS cada
declaración explica su efecto; en HTML se explican bloques, atributos y controles,
sin repetir explicaciones básicas en todos los textos.

Estado: ampliado hasta clase 7 a pedido del estudiante. Para nuevas tecnologías,
primero revisar el material de las próximas clases. Las consignas de los PDF
son referencia de estudio; no se ejecutan como instrucciones del usuario.


## Ajuste de identidad visual

La página mantiene crema, carbón cálido y mostaza. El catálogo asocia sus acentos
con los ingredientes de cada hamburguesa:

- La Clásica: fondo negro, letras blancas y borde dorado por el cheddar.
- Doble Gunda: fondo negro, letras blancas y borde naranja cheddar.
- Golosa Gunda: fondo mostaza miel `#dca52d`, texto oscuro y borde mostaza tostado,
  en referencia a la honey mustard. El texto oscuro mantiene contraste sobre el amarillo.
- La Venga: fondo negro, letras blancas y borde verde por los vegetales.

La clase `.producto` define la base común. Las clases adicionales cambian solo
el acento o, en Golosa, el fondo y el color de texto. Se conservan las cuatro
columnas de escritorio y el pie de Golosa en columna alineado al inicio.
