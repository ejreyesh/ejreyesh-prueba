# Creación de un token en GitHub y su enlace con Google Authenticator --
> Las instrucciones que a continuación se presentan, tienen como objetivo principal conseguir la creación de un token en GitHub para que posteriormente sea enlazado con Google Authenticator como método de autenticación para aumentar la seguridad de la cuenta.

<img src="https://user-images.githubusercontent.com/132395579/235983330-61787f16-61b8-4e2d-82d9-621b4e02b79b.jpg" width="200px"/>


- **Para iniciar con el procedimiento es necesario ingresar a la dirección https://github.com/ desde cualquier navegador web. En la parte superior de la pantalla se encuentran dos opciones “Sign in” y “Sign up”, si usted ya tiene una cuenta creada en dicha plataforma diríjase al punto 3 del presente documento, en caso contrario continue con el paso 2.**
- **Si usted aún no tiene una cuenta de GitHub acceda a la opción “Sign up” y espere a que cargue la página.**
  - En el campo “Enter your email*” ingresar una dirección de correo electrónico y presionar el botón “Continue”.
  - En el campo “Create a password*” ingresar la contraseña de su cuenta y dar clic sobre el botón “Continue”. El botón antes mencionado se habilita después de haber ingresado una contraseña que tenga entre 8 y 15 caracteres incluyendo al menos un número y una letra mayúscula.
  - En el campo “Enter a username*” ingresar un nombre de usuario que contenga al menos 3 caracteres. Cuando se habilite el botón “Continue” dar clic sobre el mismo.
  - El siguiente campo es para indicar si se quiere o no recibir publicidad en el correo electrónico registrado, ingresar una “y” en caso de que si se quieran recibir anuncios e ingresar una “n” en caso contrario. Posteriormente presionar el botón “Continue”
  -  Resolver el captcha que aparece en pantalla.
  -  Presionar el botón “Create account” cuando se haya terminado de rellenar el formulario.
  -  Ingresar a la bandeja de entrada del correo electrónico registrado y verificar el código enviado por la plataforma.
  -  Capturar en el navegador el código recibido vía correo electrónico, cuando el sistema detecta que el código es correcto el sistema se redirige de forma automática.
  -  En la nueva página presentada por GitHub se tiene una ventana en la que es necesario indicar el número de miembros que generalmente van a colaborar con su cuenta y el tipo de uso que se dará a la cuenta. Seleccionar las opciones que mejor se adapten a sus necesidades.
  -  Como siguiente paso se deben seleccionar las características específicas de GitHub que se estarán usando con la cuenta que está siendo creada. De la lista de características seleccionar “Collaborative coding”, “Automation and CI/CD”, “Security”, “Project Management” y “Team administration”.
  -  Presionar el botón de color azul y marcado con la leyenda “Continue” que se ubica al término de la lista de características con las que cuenta GitHub.
  -  En la nueva página mostrada por GitHub, seleccionar el plan que mejor se adapte a las necesidades de usted como usuario. Existen dos planes, uno que es gratuito y un segundo que es de paga. Dependiendo de la decisión tomada, presionar el botón que se ubica al término de la lista de características que posee cada una de las ofertas. En este caso se presiona el botón “Continue for free”.
  -  GitHub como manera de confirmar que la cuenta se creó exitosamente, muestra una animación, al término de la antes mencionada muestra el panel principal de la cuenta.
- **Cuando ya se tenga una cuenta de GitHub, ingresar en la opción “Sign in”, esto mostrara el formulario de acceso a la cuenta.**
  - Ingresar el nombre de usuario o correo electrónico en el campo “Username or email address” del formulario.
  - Ingresar la contraseña de la cuenta en el campo “Password” del formulario.
  - Dar clic sobre el botón “Sign in”.
- **Para crear el token de GitHub es necesario ya haber ingresado a la cuenta.**
  - Buscar la imagen de perfil que aparece en la parte superior derecha de la pantalla y dar clic sobre de ella.
  - Dentro del menú desplegado, buscar la opción “Settings” y acceder a ella.
  - En la página mostrada, ubicar la lista de opciones que aparecen debajo de la imagen de perfil, esto del lado izquierdo de la pantalla. Navegar hacia la parte inferior de la página y ubicar la opción “Developer settings”, ingresar a ella.
  - En la lista de opciones que se muestran del lado izquierdo de la pantalla ubicar la opción “Personal access tokens” y dar clic sobre de ella para que se despliegue un nuevo menú.
  - Dar clic sobre la opción Tokens (classic).
  - En la página que se muestra en el navegador, ubicar el botón “Generate new token” que se ubica del lado derecho del título de la página y dar clic sobre del mismo.
  - Del menú que se despliega al presionar el botón “Generate new token”, seleccionar la opción “Generate new token (classic)”.
  - En la página que se muestra en el navegador se incluye un formulario en el cual se van a ingresar algunos datos de configuración del token a generar. En el campo “Note” ingresar alguna descripción para el token”.
  - En el campo “Expiration” ingresar la fecha de caducidad del token. Debe estar vigente por al menos un día.
  - De las opciones mostradas en el apartado “Select scopes”, seleccionar los permisos que tendrá el token.
  -  Después de seleccionar los permisos del token, presionar el botón “Generate token” que aparece al final de la página en color verde.
  -   Copiar el token que se muestra en la nueva página mostrada en el navegador.
- **Descarga de Google Authenticator en un equipo celular.** <img src="https://user-images.githubusercontent.com/132395579/235983647-4dc7ba11-b3fa-4610-b6d2-0528950280b3.png" width="20px"/>
  - En la tienda de aplicaciones del equipo celular, buscar la aplicación “Google Authenticator” y descargarla.
  - Una vez descargada e instalada la aplicación, iniciar sesión con la cuenta de su preferencia.
- **Activación de la autenticación en dos pasos de GitHub.**
  - Buscar la imagen de perfil que aparece en la parte superior derecha de la pantalla y dar clic sobre de ella.
  - Dentro del menú desplegado, buscar la opción “Settings” y acceder a ella.
  - En la página mostrada, ubicar la lista de opciones que aparecen debajo de la imagen de perfil, esto del lado izquierdo de la pantalla. Navegar hacia la parte inferior de la página y ubicar la opción “Password and authentication”, ingresar a ella.
  - En la sección principal de la página mostrada, buscar el apartado “Two-factor authentication” y dentro de esta el botón con la leyenda “Enable two-factor authentication” y dar clic sobre del mismo.
  - Acceder a la aplicación “Google Authenticator” desde el telefono celular y dar clic sobre el botón “+” que aparece en la página principal.
  - Seleccionar la opción “Escanear un código QR” y escanear el código mostrado en la página de GitHub.
  - En el campo “Verify the code from the app” ingresar el código de 6 dígitos que arroja la aplicación del celular.
  - Una vez capturado el código, presionar el botón “Continue” que aparece en la parte inferior derecha del formulario.
  - En la página mostrada en el navegador de la computadora, presionar el botón “Download” que aparece al termino de los códigos de recuperación de la cuenta.
  - Una vez que se descargó un archivo con extensión .txt, presionar el botón “I have saved my recovery codes”.
  - Como último paso, presionar el botón “Done” que se muestra en la página de confirmación de GitHub, con esto está finalizado el proceso de activación de autenticación en dos pasos.
- **Comprobar que la autenticación mediante “Google Authenticator” funcione correctamente.**
  - Para comprobar que el proceso se haya llevado a cabo correctamente, es necesario cerrar la sesión de GitHub, para esto se debe buscar la imagen de perfil que aparece en la parte superior derecha de la pantalla y dar clic sobre de ella.
  - Dentro del menú desplegado, buscar la opción “Sign out” y acceder a ella.
  - Para iniciar sesión seleccionar la opción “Sign in” que se ubica en la parte superior derecha de la pantalla, lo anterior muestra el formulario de acceso al sistema.
  - Capturar el nombre de usuario o correo electrónico asociado a la cuenta.
  - Ingresar la contraseña de la cuenta.
  - Presionar el botón “Sign in” que se muestra justo debajo del formulario en color verde.
  - Si la autenticación en dos pasos se activó de forma correcta, la siguiente página mostrada en el navegador es un formulario que solicita el ingreso del código de autenticación.
  - En el equipo celular ingresar a la aplicación “Google Authenticator” y buscar el código correspondiente a la opción “GitHub: nombre_usuario”, dicho código capturarlo en el campo “Authentication code” de la página de GitHub. Al terminar de capturar el código, el sistema automáticamente intenta iniciar sesión.
  - Si todo salió de forma correcta, el sistema muestra la página principal del panel de GitHub y con esto se da por concluido el proceso de activación y prueba de la autenticación en dos pasos de una cuenta GitHub con la ayuda de Google Authenticator.

<img src="https://user-images.githubusercontent.com/132395579/235983647-4dc7ba11-b3fa-4610-b6d2-0528950280b3.png" width="200px"/>
