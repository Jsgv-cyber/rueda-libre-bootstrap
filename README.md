Descripción del Proyecto: Rueda Libre (Implementación con Bootstrap)
Estructura y Componentes de la Página:

* Encabezado (header): Cuenta con el título principal, un subtítulo descriptivo y, en la esquina superior derecha, un botón interactivo para activar el modo nocturno. Este botón permite adaptar los colores de la página a entornos oscuros y recuerda la preferencia del usuario. 
* Menú de Navegación (nav): Ubicado debajo de la cabecera, ofrece diferentes opciones con enlaces de desplazamiento suave hacia las distintas secciones de la página. 
* Sección Quiénes Somos: Presenta un texto explicativo sobre la iniciativa, sus horarios (de lunes a viernes de 7:00 am a 10:00 pm, y fines de semana o festivos hasta las 9:30 pm) y la variedad de bicicletas adaptadas a distintas necesidades, desde opciones más deportivas hasta modelos para acrobacias. 
* Catálogo de Bicicletas (Carrusel): Un componente interactivo que muestra 9 tipos de bicicletas divididas en diapositivas (con una disposición de 3 bicicletas por segmento). Se puede navegar mediante flechas a los costados y cada tarjeta incluye una pequeña descripción de la bicicleta. 
* Tarifas: Muestra de forma detallada los precios del alquiler diurno y nocturno (tanto para recorridos cortos como largos), acompañados de un aviso aclaratorio: "Los alquileres están sujetos a disponibilidad. Consulta las condiciones y horarios al realizar tu reserva." 
* Formulario de Reserva: Situado en la parte final antes del pie de página, se activa mediante un botón que despliega los campos requeridos: nombre, cédula, correo, celular, tipo de bicicleta y fecha de alquiler. Incluye el botón de envío y la nota aclaratoria: "Este formulario todavía no envía la reserva a un negocio; necesita conectarse a un servicio o backend para recibir los datos." 

Desarrollo Técnico y Uso de Bootstrap:

* El código se construyó inicialmente de forma nativa en HTML, estructurando primero el header, los enlaces CSS, el botón de modo nocturno, y utilizando mayoritariamente listas y contenedores (div) para dar forma a las secciones. 
* Funcionalidades más elaboradas, como el cambio dinámico de tema (modo noche), se implementaron mediante JavaScript y persistencia local (localStorage). 
* Bootstrap se integró posteriormente para refinar los estilos, definiendo márgenes, espaciados y la estructura de cuadrícula (row y col), logrando una disposición limpia, funcional y adaptable. 

Nota Personal y Conclusión:

Al principio no comprendía del todo la utilidad práctica de Bootstrap para agregar estilos. Sin embargo, al comprobar cómo permite organizar de mejor manera el CSS y, sobre todo, cómo aporta componentes interactivos y funcionales de tipo JavaScript a un proyecto que inicialmente no los poseía, descubrí que es una herramienta sumamente útil y eficiente a la hora de diseñar páginas web.
