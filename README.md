Este proyecto aspira a fomentar la creatividad, la innovación y la resolución de problemas, al
tiempo que ofrece una visión de los procesos de desarrollo de software y sus implicaciones en
un contexto educativo. Con un enfoque centrado en la calidad, la usabilidad y la eficiencia, este
proyecto final representa la comprensión y la aplicación práctica de los principios
fundamentales socializados en clase.

2. Elementos a evaluar.

● Conceptos básicos de HTML.

○ Maquetación.

○ HTML semántico.

● Conceptos básicos de CSS.

○ Asignación de estilos usando clases y selectores.

○ Modelo de caja.

○ Aplicación de estilos con buenas prácticas.

○ Flexbox y grid.

● Javascript

○ Modificación del DOM con Javascript.

○ Implementación de funciones.

○ Uso y gestión de estructuras de datos (arreglos y objetos)

○ Implementación de iteradores y condicionales.

○ Gestión de eventos en Javascript.

■ Ingreso de texto.

■ Botones.

■ Selectores

○ Tablas y formularios básicos.

○ Uso de procesos asíncronos con Promesas.

4. Lineas de desarrollo.

El desarrollo de productos de software debe obedecer a el planteamiento de soluciones de
problemas reales, por lo tanto se han definido la siguiente área de negocio permitidas para el
proyecto final:

b. Gimnasios.


5. Vistas del sistema.

Las vistas solicitadas en el sistema son:

● Registro de un nuevo producto, Registro.

● Pantalla de Indicaciones.

● Vista de productos, con paginación de 15 elementos.

● Buscador de información por 3 atributos.

● Lista de productos resultado de la búsqueda.

Las vistas se dividen en los siguientes componentes:

● Vista de registro de productos (Registro)

○ Título de la página.

○ Descripción de la vista.

○ Formulario de registro.

■ Campo para el nombre.

■ Selector de categoría.

■ Selector de imagen.

■ Campo para el código de producto.

■ Campo para el precio.

■ 3 Atributos adicionales de libre elección.

○ Botón de registro.

○ Botón de limpiar campos.

● Pantalla de indicaciones.

○ Título de la página.

○ Descripción de la empresa.

○ Indicaciones de como crear un producto.

○ Ejemplo de opciones disponibles.

○ Botón de redirección a Registro de productos.

● Vista de productos.

○ Titulo de la página.

○ Sección de productos, se deben visualizar todas sus propiedades.

○ Paginación de los productos, 15 productos por página.

○ La paginación debe indicar en cuál página se encuentra y tener mínimo dos
botones, el de siguiente página y el de página anterior.

○ Barra de navegación

■ Botón para búsqueda de productos.

■ Botón para redirección a registro de productos.

● Buscador de productos.

○ Título de la página.

○ Sección de filtros en el centro y zona superior. .

■ Mínimo tres opciones para buscar en la lista de productos.

■ Indicador en cada opción sobre la propiedad que va a filtrar.

■ Opción para limpiar los filtros.

■ Botón para realizar el filtro.

● Lista de resultados.

○ Tabla de 10 elementos con paginación para los resultados.

○ Debe indicar la imagen de los productos encontrados.

○ Visualizar al menos 6 propiedades de los elementos encontrados.

○ Botón de regresar a la vista de productos.


6. Condiciones del sistema
El siguiente proceso describe los casos de usos que el usuario puede realizar cuando está
interactuando con el sistema:

● Registro de productos

○ El usuario debe ingresar los campos requeridos para hacer le proceso de registro.

○ Tipo de campo de Nombre: String no superior a 20 caracteres.

○ Selector de categoría.

■ El sistema de tener definidas mínimo 5 categorias.

○ Selector de imagen.

■ La selección debe ser por el nombre de la imagen.

■ Se debe tener mínimo 10 opciones para imagenes.

○ Campo de precio.

■ Solo debe aceptar números, debe estar formateado en pesos.

○ Código del producto..

■ Mínimo 8 caracteres.

■ Debe tener almenos una minúscula y una mayuscula.

■ Debe tener mínimo 2 números.

○ Puedan dar click en el botón de Registrar.

○ El producto debe ser validado y si alguno de los campos requeridos o el código
del producto es incorrecto, se debe visualizar un mensaje y redirigir el usuario a la
página de indicaciones.

○ Se debe tener la opción para limpiar los campos y digitar otro producto.

○ Una vez el producto es validado es redireccionado a la página principal de
productos.

● Vista de productos

○ Las lista carga inicialmente los 15 primeros elementos de la DB.

○ En la parte inferior puede el usuario seleccionar la página siguiente con un botón,
lo cual cargará los siguientes 15 elementos de la DB.

○ Se habilita el boton de página anterior para regresar a los primeros 15 elementos.

○ Cuando se llega la última página el boton de siguiente debe inhabilitarse.

○ Cada elemento debe visualizarse como una tarjeta, mostrando todos los
atributos disponibles para ese elemento.

○ Debe estar disponibles una barra de navegación con dos opciones, Registrar un
nuevo producto y buscar un producto en la base de datos.

○ Cuando se da click sobre buscar un nuevo producto se debe redireccionar a la
página de filtros para buscar un producto.

● Buscador de productos.

○ La sección de filtros debe tener mínimo tres campos para ingresar o seleccionar
los filtros que se pueden aplicar, los filtros pueden ser entradas de texto o
selectores de opciones y deben estar ubicados en la parte superior de la página.

○ El usuario puede seleccionar uno o más filtros y luego aplicarlos con un botón de
Buscar.

○ El usuario puede eliminar los filtros y regresar a las condiciones iniciales con un
botón de Limpiar.

○ Cuando se presiona el botón “Buscar” se debe simular el proceso de obtención de
datos con una promesa.

○ Se debe indicar un mensaje de “Cargando” o un loading mientras la información
carga.

○ La lista de resultados debe actualizarse 2 segundos despues de haber
presionado el botón de Buscar.

● Sección de lista de resultados.

○ La información debe presentarse como una tabla de 10 elementos y se debe
visualizar mínimo 6 caracteristicas de cada elemento.
○ La lista y la paginación se actualiza con la cantidad de elementos que coincidan
con la busqueda.
○ El usuario encontrará en esta vista los siguientes detalles:
■ Título del elemento.
■ Imagen del elemento.
■ Categoría
■ Precio
■ 2 caracteristicas adicionales de libre selección, las cuales dependerá de la
linea de negocio que haya elegido el estudiante.
■ Botón para “Regresar” a la vista principal.
■ Botón de limpiar la búsqueda.
