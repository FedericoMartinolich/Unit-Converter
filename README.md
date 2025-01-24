Conversor de Unidades

Este es un proyecto simple basado en HTML, CSS y JavaScript para realizar conversiones entre diferentes tipos de unidades, como longitud, peso y temperatura.

Características

Selección de tipo de unidad: Longitud, Peso o Temperatura.

Conversión entre diferentes unidades dentro de cada tipo.

Interfaz intuitiva y fácil de usar.

Tecnologías utilizadas

HTML5: Estructura básica del proyecto.

JavaScript: Lógica de selección y cálculo de las conversiones.

CSS: Opcional, para mejorar el diseño.

Estructura del código

HTML

El HTML contiene los siguientes elementos principales:

Un selector (<select>) para elegir el tipo de unidad.

Dos selectores (<select>) para seleccionar la unidad de origen y la de destino.

Un campo de entrada (<input>) para ingresar el valor a convertir.

Un botón para calcular el resultado.

JavaScript

El código JavaScript realiza las siguientes tareas:

Actualizar las opciones de unidad: Basándose en el tipo de unidad seleccionado, las opciones de las listas desplegables se rellenan dinámicamente.

Realizar la conversión: Se calcula el valor convertido según las unidades seleccionadas y el valor ingresado.

Mostrar el resultado: Se muestra el resultado en un cuadro de alerta.

Estructura de las conversiones

Longitud:

Metros, Kilómetros, Millas, Pies.

Peso:

Gramos, Kilogramos, Libras, Onzas.

Temperatura:

Celsius, Fahrenheit, Kelvin.

Instrucciones de uso

Clonar este repositorio o copiar el código fuente.

Abrir el archivo index.html en un navegador web.

Seleccionar el tipo de unidad en el primer desplegable.

Elegir las unidades de origen y destino en los siguientes desplegables.

Ingresar el valor a convertir en el campo de entrada.

Hacer clic en el botón "Calcular" para ver el resultado.

Ejemplo de conversión

Seleccione "Longitud".

Elija "Metros" como unidad de origen y "Kilómetros" como unidad de destino.

Ingrese el valor "1000".

Haga clic en "Calcular".

Resultado esperado: "1".

Personalización

Para agregar más unidades o realizar modificaciones:

Editar el objeto options en el archivo JavaScript para incluir nuevas unidades.

Actualizar la lógica de conversión en la función calculate según sea necesario.
