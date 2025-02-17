Proyecto de Creación y Adaptación de Plantillas Web y Formularios
Este proyecto tiene como objetivo la creación y adaptación de plantillas web responsive y formularios interactivos para ser utilizados en diferentes contextos. El formulario incluido en el código tiene múltiples pasos y validaciones en tiempo real, adaptándose a diferentes tamaños de pantalla (responsive).

Descripción
Este proyecto incluye:

Formulario multi-paso: Un formulario interactivo que consta de tres pasos, donde se recopila información personal, de seguridad y adicional.
Validación en tiempo real: El formulario valida los campos introducidos en cada paso, mostrando mensajes de error si algún campo no cumple con los requisitos.
Diseño responsive: El formulario y los botones de navegación se adaptan a diferentes tamaños de pantalla, asegurando una experiencia de usuario adecuada en dispositivos móviles, tabletas y escritorios.
Estilos personalizados: Se incluyen estilos CSS para proporcionar un diseño atractivo y consistente, utilizando colores, márgenes y bordes específicos.
Características
Responsive Design: El diseño se adapta automáticamente a diferentes tamaños de pantalla utilizando @media queries.
Validación de campos:
Validación de nombre (solo letras y espacios).
Validación de correo electrónico (formato de correo válido).
Validación de contraseña (mínimo 8 caracteres).
Validación de edad (entre 0 y 120).
Validación de fecha de nacimiento (campo obligatorio).
Interactividad: El formulario permite navegar entre los diferentes pasos con botones "Siguiente" y "Anterior", mostrando solo el paso actual.
Feedback visual: Los campos validados correctamente tienen bordes verdes, mientras que los que tienen errores o aún no se validaron tienen bordes rojos.
Tecnologías Utilizadas
HTML: Estructura básica del formulario y sus campos.
CSS: Estilos para hacer el formulario atractivo y responsive.
JavaScript: Validación en tiempo real, interactividad en la navegación entre los pasos del formulario.
Instrucciones
Clonar el repositorio: Puedes clonar este proyecto utilizando el siguiente comando de git:

bash
Copiar
git clone <URL_DEL_REPOSITORIO>
Abrir el archivo HTML: El formulario está contenido en el archivo index.html. Puedes abrirlo en cualquier navegador web para verlo en acción.

Personalización:

Puedes personalizar los campos del formulario (por ejemplo, agregar más campos o cambiar los existentes).
Los estilos se encuentran en la sección <style> dentro del <head> del archivo HTML. Aquí puedes cambiar los colores, márgenes, fuentes, etc.
Puedes ajustar la validación de campos según tus necesidades modificando las funciones JavaScript.
Uso
Navegación entre los pasos:

El formulario está dividido en tres pasos, cada uno mostrado en su propio <fieldset>.
Los botones "Siguiente" y "Anterior" permiten a los usuarios navegar entre los pasos.
Validación:

Los campos obligatorios son marcados con un asterisco rojo (*).
Los campos que tienen un error mostrarán un mensaje debajo del campo.
Si el formulario no está correctamente validado, el botón de envío está deshabilitado.
Envío:

Una vez todos los campos estén correctamente validados, el formulario puede ser enviado a un servidor a través del formulario de envío.
Ejemplo de Pantallas
Pantalla de Escritorio: El formulario se muestra en un diseño de columna única, con los campos de entrada organizados verticalmente.

Pantalla Móvil: En pantallas pequeñas, el formulario y los botones se ajustan para caber en el ancho de la pantalla. Los botones de navegación se apilan verticalmente.

Personalización
1. Agregar más pasos
Para agregar más pasos, simplemente añade más <fieldset> en el formulario y actualiza el script JavaScript para permitir la navegación entre los nuevos pasos.

2. Modificar los estilos
Los estilos CSS están integrados en el archivo HTML. Puedes modificar los colores, fuentes y otros detalles en la sección <style> para adaptarlo a tu propio diseño.

3. Validación de campos adicionales
Para agregar validaciones personalizadas, puedes actualizar las funciones de validación de JavaScript. Si quieres validar campos adicionales o cambiar los criterios de validación de los campos existentes, puedes hacerlo modificando las funciones como validarNombre(), validarCorreo(), etc.

Contribuciones
Si deseas contribuir a este proyecto, puedes hacer un fork y enviar un pull request con tus cambios. Asegúrate de probar tus modificaciones antes de enviarlas.

Licencia
Este proyecto está bajo la Licencia MIT. Puedes usar, modificar y distribuir este proyecto de acuerdo con los términos de la licencia.

