# Criterios de análisis de accesibilidad (nivel A)

| Prin-cipio | Pauta | Criterio | Descripción técnica | Descripción general |  |
|--------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1. Perceptible | 1.1 Alternativas textuales | 1.1.1 - Contenido no textual | Todo contenido no textual, que se presenta al usuario, cuenta con una alternativa textual que sirve para un propósito equivalente, con algunas excepciones. | Todas las imágenes deben tener descripción (la que se observa al señalarla con el mouse). Esto se coloca con un atributo llamado "alt". Si la imagen es decorativa, igual debe contenerlo "vacío", de manera que las tecnologías de asistencia, como los lectores de pantalla, puedan ignorarla; caso contrario, la describen con nombre de archivo y ello es confuso para el usuario. |  |
| 1.2 Contenido multimedia dependiente del tiempo | 1.2.1 - Sólo audio y sólo video (pregrabados) | Excepto para cuando el audio o el vídeo es un contenido multimedia alternativo al texto y está claramente identificado como tal, debe cumplirse lo siguiente: | debe proporcionarse una alternativa que proporcione información equivalente a la del audio o video pregrabado. | Los audios y videos debe tener una alternativa en forma de texto, como son las transcripciones o descripciones. Para los videos se puede proporcionar una pista de audio, que podrá revisarse repetidas veces. Las tecnologías de asistencia pueden leer el texto en voz alta o traducirlo a Braille. |  |
| 1.2.2 - Subtítulos (pregrabado) | Se proporcionan subtítulos para todo audio pregrabado presente en un contenido multimedia sincronizado, excepto cuando es un contenido multimedia alternativo al texto y está claramente identificado como tal. | Se aplica a audio y video combinados, para que sean accesibles a las personas sordas. Cuando el audio de un video es significativo, debe ir acompañado de subtítulos sincronizados. |  |  |  |
| 1.2.3 - Audiodescripción o alternativa multimedia pregrabada | Para el contenido de vídeo pregrabado, se proporciona una alternativa multimedia | o una audiodescripción | del contenido multimedia sincronizado. | Se debe permitir a las personas ciegas o con impedimentos visuales, el acceso al contenido visual de una presentación multimedia. Una forma es incluir descripciones de audio en las porciones del video que no tengan sonido. Otra forma, es proporcionar una descripción textual. En esas descripciones se incluye información sobre el contexto, las acciones y expresiones de los actores, y cualquier otro material visual importante. |  |
| 1.3 Adaptabilidad | 1.3.1 - Información y relaciones | La información, la estructura y las relaciones transmitidas a través de la presentación pueden ser programablemente determinadas o se encuentran disponibles en texto. | Los desarrolladores del sitio web deben estructurar los contenidos de forma que queden identificados claramente, en el código, los encabezados o títulos, las listas de elementos, las etiquetas y campos de formularios, y los títulos de tablas. De esta forma, un lector de pantalla podrá anticipar el contenido y el usuario podrá elegir adónde navegar. |  |  |
| 1.3.2 - Secuencia significativa | Cuando la secuencia en la que se presenta un contenido afecta a su significado, la secuencia correcta de lectura puede ser programablemente determinada. | Los desarrolladores del sitio web deben organizar la secuencia de navegación con teclado de forma lógica: de izquierda a derecha y de arriba abajo (el cursor no debe "saltar" de un lugar a otro de la página desordenadamente). |  |  |  |
| 1.3.3 - Características sensoriales | Las instrucciones que se proporcionan, para comprender y operar con un contenido, no dependen solamente de las características sensoriales de los componentes, tales como forma, tamaño, ubicación visual, orientación o sonido. | Las personas ciegas o con problemas visuales pueden no entender la información que depende la forma o de la ubicaión que tienen. Por lo tanto, se debe proporcionar información adicional, usualmente en forma de texto. |  |  |  |
| 1.4 Distinguible | 1.4.1 - Uso del color | El color no se emplea como el único medio visual para transmitir una información, indicar una acción, provocar una respuesta o distinguir visualmente un elemento. | Debido a que muchas personas están impedidas de ver correctamente los colores, incluyendo ciegos, daltónicos y con poca visión, no debe usarse sólo el color como indicador de algo. Por ejemplo, hay páginas donde un botón rojo sirve para rechazar y uno verde para aceptar; si alguien no ve el color no podrá conocer dichas funciones. También sucede con los mensajes de error, que se muestran en rojo. Para indicar el significado de un componente, además de color, debe usarse texto. |  |  |
| 1.4.2 - Control de audio | Si cualquier audio se reproduce automáticamente en una página web durante más de tres segundos, se proporciona ya sea un mecanismo que permita pausar o detener el audio, o un mecanismo que permita controlar el volumen del audio de manera independiente al del resto del sistema. | Si se proporcionan mecanismos para pausar, detener o controlar el volumen de los audios que comienzan automáticamente, las personas que utilizan lectores de pantalla pueden oir lo que el lector les dice, sin que interfieran otros sonidos. Esto también beneficia a aquellas personas que no se pueden concentrar en el contenido visual (incluyendo texto), cuando hay sonidos de fondo. Aunque el criterio no lo exige, lo ideal es que no haya sonidos que comiencen automáticamente. |  |  |  |
| 2. Operable | 2.1 | Accesible a través del teclado | 2.1.1 - Teclado | Toda funcionalidad del contenido es operable a través de una interfaz de teclado, sin que exista un límite de tiempo específico para realizar las pulsaciones de las teclas. | Es muy importante proporcionar el acceso mediante teclado para personas ciegas, y para otros grupos con impedimentos en su movilidad que no le permiten usar mouse. Todas las funciones del contenido deben poder operarse con teclado, además de proporcionar otros métodos de interacción como el mouse. |
| 2.1.2 - Sin trampa de teclado | Si el foco puede moverse a un componente de la página por medio de una interfaz de teclado, u otro método de salida estándar, entonces el foco puede moverse fuera de ese componente empleando simplemente la misma interfaz de teclado y, si para ello se necesita algo más que la simple flecha o techa de tabulación, entonces se avisa al usuario del método con el que mover el foco. | Se debe asegurar que el foco no quede "atrapado" en una subsección de la página. Se le debe indicar al usuario qué teclas, o combinación de teclas, se emplean para salir de esa subsección. |  |  |  |
| 2.2 | Tiempo suficiente | 2.2.1 - Limite de tiempo ajustable | Para cada límite de tiempo que se establece en el contenido, se cumple al menos uno de los siguientes casos: desactivar, ajustar, extender, excepción de tiempo real, excepción esencial, excepción de 20 horas. | Las personas con problemas de ceguera, de baja visión, de destreza o con limitaciones cognitivas, pueden requerir más tiempo para leer contenido o realizar funciones. Si éstas dependen del tiempo, | algunos usuarios encontrarán dificultades para llevarlas a cabo, y el servicio será inaccesible para ellos. Por lo tanto, se deben proporcionar opciones para desactivar los límites de tiempo, personalizar la duración de los plazos, o solicitar más tiempo. |
| 2.2.2 - Pausar, detener, ocultar | Para cualquier información que se mueva, parpadee, se desplace o se actualice automáticamente, que comience en forma automática, dure más de 5 segundos y se presente en forma paralela a otro contenido, debe existir un mecanismo que permite al usuario pausar, detener u ocultar la información, o controlar la frecuencia de la actualización, a menos que ello sea esencial para la actividad. | "Moverse, desplazarse, parpadear": se refiere a películas de animación, presentaciones multimedia, juegos en tiempo real, tablas de cotizaciones, etc. | "Auto-actualización": se refiere a contenido que se actualiza o desaparece de acuerdo a un intervalo de tiempo preestablecido. Por ejemplo, noticias, clima, etc. |  |  |
| 2.3 | Ataques | 2.3.1 - Tres destellos o por debajo del umbral | Las páginas web no contienen nada que destelle más de tres veces en un segundo, o el destello está por debajo de los umbrales de destello general y de destello rojo. | Los destellos pueden provocar convulsiones en personas fotosensibles, por lo que no podrían acceder tranquilamente al contenido. Por lo tanto, deben evitarse. |  |
| 2.4 | Navegable | 2.4.1 - Saltar bloques | Existe un mecanismo que permite saltar bloques de contenido que se repiten en múltiples páginas web. | Es muy útil proporcionar enlaces que permitan saltear porciones de contenido que se repite en varias páginas. De esta manera, un lector de pantalla no lo reproducirá repetidas veces. También se deben colocar enlaces para saltear objetos animados, como reproductores de películas, y así permitir al usuario el ahorro de tiempo. |  |
| 2.4.2 - Página titulada | Las páginas web tienen títulos que describen su tema o propósito | El título se visualiza en la barra de títulos de la ventana o en la pestaña que contiene la página. Por lo tanto, debe ser descriptivo, permitiendo identificar rápidamente el contenido. |  |  |  |
| 2.4.3 - Orden de foco | Si una página web puede navegarse secuencialmente y la secuencia de navegación afecta a su significado u operatividad, los componentes que pueden recibir el foco lo hacen en un orden que conserva íntegros su significado y operatividad. | Se debe asegurar que el usuario que navega con el teclado pueda hacerlo en un orden lógico y significativo. |  |  |  |
| 2.4.4 - Propósito de un vínculo (en su contexto) | El propósito de cada vínculo puede determinarse con el texto del vínculo, o del texto del vínculo junto a su contexto programablemente determinable, excepto donde el propósito del vínculo puede ser ambiguo para los usuarios en general. | Para enlaces ubicados dentro de un texto, su nombre debe tener signficado, caso contrario, una persona ciega -usando lector de pantalla- deberá leer el texto circundante o clickear el enlace para ver adónde va. Esto es lo mínimo que se pide para alcanzar el nivel A de conformidad; si se tratara de alcanzar el nivel AAA, todos los enlaces deben tener texto significativo. |  |  |  |
| 3. Comprensible | 3.1 Legible | 3.1.1 - Idioma de la página | El idioma por defecto de cada página web puede ser programablemente determinado. | Los desarrolladores de sitios web deben proporcionar el idioma de las páginas, lo cual permite que el texto y cualquier contenido lingüístico se presente de forma correcta. Esto aduda a personas que usan lectores de pantalla, personas con problemas cognitivos que usan software texto-a-voz, personas que dependen de subtítulos. |  |
| 3.2 Predecible | 3.2.1 - Con foco | Recibir el foco por parte de cualquier componente no provoca ningún cambio de contexto. | Cuando una persona navega el contenido web, debe poder hacerlo de forma predecible. Es decir, que no debe producirse un cambio cuando un elemento recibe el enfoque. Éste sólo debe producirse por una acción del teclado o del mouse. Ejemplos de cambios de contexto: ventanas que se abren automáticamente o formularios que se envían cuando un elemento recibe el enfoque. |  |  |
| 3.2.2 - Con entrada de datos | Cambiar la configuración de cualquier componente de la interfaz de usuario no causa automáticamente ningún cambio de contexto, a menos que el usuario haya sido advertido del comportamiento antes de emplear el componente. | El ingreso de datos o la selección de una opción en un formulario, deben tener efectos predecibles, no deben producir cambios de contexto. |  |  |  |
| 3.3 Ayuda en la entrada de datos | 3.3.1 - Identificación de errores | Si se detecta automáticamente un error de entrada de datos, se identifica el ítem erróneo y el error se describe al usuario por medio de texto. | La página debe comunicar el error en el momento que se produce. Por ejemplo, usualmente los errores en carga de formularios aparecen cuando se envían y se vuelve a cargar la página, lo que hará que el lector de pantalla la lea completa. Para evitar esa pérdida de tiempo, los mensajes deben mostrarse al producirse. |  |  |
| 3.3.2 - Instrucciones o etiquetas | Se proporcionan etiquetas o instrucciones cuando el contenido requiere entrada de datos por parte del usuario. | Se deben proporcionar instrucciones, especialmente para personas que navegan utilizando lectores de pantalla dentro de un formulario o un menú complejo. |  |  |  |
| 4. Robusto | 4.1 Compatible | 4.1.1 - Interpretación | Para contenido que se haya implementado empleando un lenguaje de marcado, los elementos cuentan con etiquetas completas de cierre y apertura, se han anidado correctamente, no contienen atributos duplicados y cualquier ID es único, excepto donde la especificación permita excepciones. | Los desarrolladores de sitios web deben construir sus páginas utilizando correcta sintáxis y estructura, para que los navegadores web y las tecnologías de asistencia puedan analizar y mostrar el contenido de forma precisa. |  |
| 4.1.2 - Nombre, rol, valor | Para todo componente de interfaz de usuario (incluidos, pero no limitados a: elementos de formulario, vínculos y componentes generados por medio de scripts), el nombre y el rol pueden ser programablemente determinados; los estados, propiedades y valores que pueden ser establecidos por el usuario pueden ser programablemente establecidos; y los cambios en tales ítems se notifican a los agentes de usuario, incluidas las ayudas técnicas. | Si los desarrolladores web construyen las páginas utilizando controles (botones, menúes, listas, etc) estándares, las tecnologías de asistencia los intrepretarán sin inconvenientes. Si usan controles personalizados, deben crearlos de forma que las tecnologías de asistencia puedan interpretarlos. Esto los hará comptatibles con: lectores de pantalla, ampliadores de pantalla, software de reconocimiento de voz. |  |  |  |