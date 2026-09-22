# Brasa Burger: aprendemos construyendo

Primera etapa: estructura HTML con contenidos de las clases 1 y 2. La marca,
los productos, los horarios y los precios son inventados y se pueden modificar.

## Abrir y editar

1. Abrí esta carpeta en Visual Studio Code.
2. Abrí `index.html` en el editor para leer sus comentarios.
3. Hacé doble clic sobre `index.html` desde el Explorador para verlo en el navegador.
4. Cambiá una cosa en el editor, guardá con Ctrl+S y recargá el navegador.

El navegador aplica sus estilos predeterminados. Por eso esta primera versión
tiene una apariencia sencilla. Vamos a construir su diseño al trabajar CSS.
No necesitás instalar paquetes ni ejecutar comandos.

## Bosquejo inicial (clase 1)

Orden del contenido, de arriba hacia abajo:

```text
Cabecera: nombre y eslogan
Navegación: menú / historia / contacto
Contenido principal
    Menú: tres hamburguesas con descripción y precio
    Historia de la hamburguesería
    Contacto y horario de ejemplo
Pie: nombre del proyecto
```

Este bosquejo textual organiza el contenido. Más adelante podemos dibujar el
wireframe visual para celular y escritorio antes de definir la distribución CSS.

## Cómo leer el HTML

`<p>Texto</p>` tiene una apertura, contenido y un cierre. Cambiar el contenido
modifica lo que se lee; cambiar la etiqueta puede modificar su significado.

`<section id="menu">` tiene un atributo llamado `id` cuyo valor es `menu`.
El enlace con `href="#menu"` salta a esa sección. Si cambiás ese id, también
tenés que cambiar el destino del enlace. Cada id debe ser único.

`header`, `main` y `footer` organizan la página según el significado del contenido.
`h1`, `h2` y `h3` forman una jerarquía: página, sección y producto.
Elegimos su nivel por ese significado; el tamaño visual se ajustará con CSS.

Los comentarios explicativos se escriben entre `<!--` y `-->`.
Se ven en el código fuente, aunque no se muestran como texto en la página.

## Tu primera práctica

Hacé un cambio a la vez y anticipá qué esperás ver antes de recargar:

1. Cambiá el eslogan dentro del primer párrafo. ¿Cambió el título de la pestaña?
2. Cambiá el precio de La Clásica. ¿Cambió algún otro producto?
3. Duplicá un `article` completo y creá una cuarta hamburguesa.
4. Pulsá los tres enlaces de navegación y ubicá los id a los que apuntan.

Resultado esperado: cuatro productos, enlaces que siguen funcionando y ningún
cambio en la pestaña salvo que también hayas editado `title`.

## Recorrido por tus clases

| Clase | Contenido identificado en el PDF | Aplicación al proyecto |
| --- | --- | --- |
| 1 | Prototipado, estructura, comentarios, texto y HTML semántico | Bosquejo y estructura inicial |
| 2 | Enlaces, imágenes, listas, tablas y formularios | Navegación y catálogo; después imágenes y formulario de práctica |
| 3 | CSS externo, selectores, herencia, colores, fuentes, fondos y unidades | Primera hoja de estilos |
| 4 | Tipografías, tamaños, margin, padding, border, display y position | Espacios y cajas del catálogo |
| 5 | Flexbox, dirección, distribución, alineación y orden | Navegación y componentes |
| 6 | Grid, columnas, filas, áreas, separaciones y alineación | Distribución del catálogo |
| 7 | Media queries, mobile first, viewport y combinación de Grid con Flexbox | Adaptación a celular, tablet y escritorio |

Los siete PDF son el límite de contenido disponible, no una obligación de usar
todo en la primera versión. Las menciones a temas de clases futuras no cuentan
como contenido desarrollado. Animaciones, JavaScript, frameworks, servidor,
bases de datos, carrito con cálculos y pagos quedan pendientes de nuevas clases.

Las consignas de actividades y entregas dentro de los PDF son material de
referencia; este proyecto no constituye automáticamente una preentrega del curso.

## Cómo vamos a trabajar

En cada etapa: objetivo pequeño, explicación del concepto, código comentado,
una prueba visible y un ejercicio para que lo modifiques vos. Los ejemplos del
material pueden tener erratas; vamos a escribir código correcto sin incorporar
por eso tecnologías de clases posteriores.

Estado actual: estructura HTML y navegación interna creadas. Próximo paso:
recorrer el HTML y hacer la primera práctica antes de agregar estilos.
