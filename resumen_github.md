# Creación de un token en GitHub y su enlace con Google Authenticator
> Las instrucciones que a continuación se presentan, tienen como objetivo principal conseguir la creación de un token en GitHub para que posteriormente sea enlazado con Google Authenticator como método de autenticación para aumentar la seguridad de la cuenta.
<p align="center">
  <img src="https://user-images.githubusercontent.com/132395579/235983330-61787f16-61b8-4e2d-82d9-621b4e02b79b.jpg" width="200px"/>
  <br/>
  <sub>Logotipo Github</sub>
</p>

1. **Para iniciar con el procedimiento es necesario ingresar a la dirección https://github.com/ desde cualquier navegador web. En la parte superior de la pantalla se encuentran dos opciones “Sign in” y “Sign up”, si usted ya tiene una cuenta creada en dicha plataforma diríjase al punto 3 del presente documento, en caso contrario continue con el paso 2.**
    <p align="center">
      <img src="https://user-images.githubusercontent.com/132395579/235987431-fa1fe865-f963-4c6c-8999-ed3628997fbb.png" width="500px"/>
      <br/>
      <sub>Sitio principal de GitHub</sub>
    </p>

2. **Si usted aún no tiene una cuenta de GitHub acceda a la opción “Sign up” y espere a que cargue la página.**
    <p align="center">
      <img src="https://user-images.githubusercontent.com/132395579/235990337-5738ee8d-b1d8-427a-ba29-c62aaf7caad5.png" width="500px"/>
      <br/>
      <sub>Formulario para el registro de una cuenta Github</sub>
    </p>
    
    1. En el campo “**Enter your email**” ingresar una dirección de correo electrónico y presionar el botón “**Continue**”.
    3. En el campo “**Create a password**” ingresar la contraseña de su cuenta y dar clic sobre el botón “**Continue**”. 
        > El botón antes mencionado se habilita después de haber ingresado una contraseña que tenga entre 8 y 15 caracteres incluyendo al menos un número y una letra mayúscula.
    5. En el campo “**Enter a username**” ingresar un nombre de usuario que contenga al menos 3 caracteres. Cuando se habilite el botón “**Continue**” dar clic sobre el mismo.
    6. El siguiente campo es para indicar si se quiere o no recibir publicidad en el correo electrónico registrado, ingresar una “*y*” en caso de que si se quieran recibir anuncios e ingresar una “*n*” en caso contrario. Posteriormente presionar el botón “**Continue**”
    7. Resolver el captcha que aparece en pantalla.
    8. Presionar el botón “**Create account**” cuando se haya terminado de rellenar el formulario.
    9. Ingresar a la bandeja de entrada del correo electrónico registrado y verificar el código enviado por la plataforma.
    10. Capturar en el navegador el código recibido vía correo electrónico.
        > Cuando el sistema detecta que el código es correcto el sistema se redirige de forma automática.
    12. En la nueva página presentada por GitHub se tiene una ventana en la que es necesario indicar el número de miembros que generalmente van a colaborar con su cuenta y el tipo de uso que se dará a la cuenta. Seleccionar las opciones que mejor se adapten a sus necesidades.
    13. Como siguiente paso se deben seleccionar las características específicas de GitHub que se estarán usando con la cuenta que está siendo creada. 
        > De la lista de características seleccionar “**Collaborative coding**”, “**Automation and CI/CD**”, “**Security**”, “**Project Management**” y “**Team administration**”.
    15. Presionar el botón de color azul y marcado con la leyenda “**Continue**” que se ubica al término de la lista de características con las que cuenta GitHub.
    16. En la nueva página mostrada por GitHub, seleccionar el plan que mejor se adapte a las necesidades de usted como usuario. Existen dos planes, uno que es gratuito y un segundo que es de paga. Dependiendo de la decisión tomada, presionar el botón que se ubica al término de la lista de características que posee cada una de las ofertas. En este caso se presiona el botón “**Continue for free**”.
    17. GitHub como manera de confirmar que la cuenta se creó exitosamente, muestra una animación, al término de la antes mencionada muestra el panel principal de la cuenta.
3. **Cuando ya se tenga una cuenta de GitHub, ingresar en la opción “Sign in”, esto mostrara el formulario de acceso a la cuenta.**
    <p align="center">
      <img src="https://user-images.githubusercontent.com/132395579/235991625-8883ad41-71dd-427a-8ef8-f813b3783e4c.png" width="500px"/>
      <br/>
      <sub>Formulario para iniciar sesión con una cuenta Github</sub>
    </p>
    
    1. Ingresar el nombre de usuario o correo electrónico en el campo “**Username or email address**” del formulario.
    1. Ingresar la contraseña de la cuenta en el campo “**Password**” del formulario.
    1. Dar clic sobre el botón “**Sign in**”.
4. **Para crear el token de GitHub es necesario ya haber ingresado a la cuenta.**
    <p align="center">
      <img src="https://user-images.githubusercontent.com/132395579/235992082-fd5965ba-7c0a-4493-9042-89bfbf098fdc.png" width="500px"/>
      <br/>
      <sub>Creación de un token Github</sub>
    </p>
    
    1. Buscar la imagen de perfil que aparece en la parte superior derecha de la pantalla y dar clic sobre de ella.
    1. Dentro del menú desplegado, buscar la opción “**Settings**” y acceder a ella.
    1. En la página mostrada, ubicar la lista de opciones que aparecen debajo de la imagen de perfil, esto del lado izquierdo de la pantalla. Navegar hacia la parte inferior de la página y ubicar la opción “**Developer settings**”, ingresar a ella.
    1. En la lista de opciones que se muestran del lado izquierdo de la pantalla ubicar la opción “Personal access tokens” y dar clic sobre de ella para que se despliegue un nuevo menú.
    1. Dar clic sobre la opción "**Tokens (classic)**".
    1. En la página que se muestra en el navegador, ubicar el botón “**Generate new token**” que se ubica del lado derecho del título de la página y dar clic sobre del mismo.
    1. Del menú que se despliega al presionar el botón “**Generate new token**”, seleccionar la opción “**Generate new token (classic)*”.
    1. En la página que se muestra en el navegador se incluye un formulario en el cual se van a ingresar algunos datos de configuración del token a generar. En el campo “**Note**” ingresar alguna descripción para el token.
    1. En el campo “**Expiration**” ingresar la fecha de caducidad del token. 
        > La vigencia del token debe ser de al menos un día.
    3. De las opciones mostradas en el apartado “**Select scopes**”, seleccionar los permisos que tendrá el token.
    4. Después de seleccionar los permisos del token, presionar el botón “**Generate token**” que aparece al final de la página en color verde.
    5. Copiar el token que se muestra en la nueva página mostrada en el navegador.
4. **Descarga de Google Authenticator en un equipo celular.**
    <p align="center">
      <img src="https://user-images.githubusercontent.com/132395579/235992685-ea3a7b90-f5f2-49a1-a729-49c4b7c29b41.jpg" width="500px"/>
      <br/>
      <sub>Interfaz principal de la aplicación Google Authentication</sub>
    </p>
    
    1. En la tienda de aplicaciones del equipo celular, buscar la aplicación “**Google Authenticator**” y descargarla.
    1. Una vez descargada e instalada la aplicación, iniciar sesión con la cuenta de su preferencia.
5. **Activación de la autenticación en dos pasos de GitHub (2FA).**
    <p align="center">
      <img src="https://user-images.githubusercontent.com/132395579/235992253-922095ad-9250-41f0-9fbd-abdd82c37fb0.png" width="500px"/>
      <br/>
      <sub>Activación de Two-Factor Authentication de Github</sub>
    </p>
    
    1. Buscar la imagen de perfil que aparece en la parte superior derecha de la pantalla y dar clic sobre de ella.
    1. Dentro del menú desplegado, buscar la opción “**Settings**” y acceder a ella.
    1. En la página mostrada, ubicar la lista de opciones que aparecen debajo de la imagen de perfil, esto del lado izquierdo de la pantalla. Navegar hacia la parte inferior de la página y ubicar la opción “**Password and authentication**”, ingresar a ella.
    1. En la sección principal de la página mostrada, buscar el apartado “**Two-factor authentication**” y dentro de esta el botón con la leyenda “**Enable two-factor authentication**” y dar clic sobre del mismo.
    1. Acceder a la aplicación “**Google Authenticator**” desde el telefono celular y dar clic sobre el botón “**+**” que aparece en la página principal.
    1. Seleccionar la opción “**Escanear un código QR**” y escanear el código mostrado en la página de GitHub.
    1. En el campo “**Verify the code from the app**” ingresar el código de 6 dígitos que arroja la aplicación del celular.
    1. Una vez capturado el código, presionar el botón “**Continue**” que aparece en la parte inferior derecha del formulario.
    1. En la página mostrada en el navegador de la computadora, presionar el botón “**Download**” que aparece al termino de los códigos de recuperación de la cuenta.
    1. Una vez que se descargó un archivo con extensión .txt, presionar el botón “**I have saved my recovery codes**”.
    1. Como último paso, presionar el botón “**Done**” que se muestra en la página de confirmación de GitHub, con esto está finalizado el proceso de activación de autenticación en dos pasos.
6. **Comprobar que la autenticación mediante “Google Authenticator” funcione correctamente.**
    <p align="center">
      <img src="https://user-images.githubusercontent.com/132395579/235993434-1b8fd89b-68f3-40b2-84d9-73b05f111329.png" width="500px"/>
      <br/>
      <sub>Comprobación del correcto funcionamiento de la cuenta Github</sub>
    </p>
    
    1. Para comprobar que el proceso se haya llevado a cabo correctamente, es necesario cerrar la sesión de GitHub, para esto se debe buscar la imagen de perfil que aparece en la parte superior derecha de la pantalla y dar clic sobre de ella.
    1. Dentro del menú desplegado, buscar la opción “**Sign out**” y acceder a ella.
    1. Para iniciar sesión seleccionar la opción “**Sign in**” que se ubica en la parte superior derecha de la pantalla, lo anterior muestra el formulario de acceso al sistema.
    1. Capturar el nombre de usuario o correo electrónico asociado a la cuenta.
    1. Ingresar la contraseña de la cuenta.
    1. Presionar el botón “**Sign in**” que se muestra justo debajo del formulario en color verde.
    1. Si la autenticación en dos pasos se activó de forma correcta, la siguiente página mostrada en el navegador es un formulario que solicita el ingreso del código de autenticación.
    1. En el equipo celular ingresar a la aplicación “**Google Authenticator**” y buscar el código correspondiente a la opción “**GitHub: nombre_usuario**”, dicho código capturarlo en el campo “**Authentication code**” de la página de GitHub.
        > Al terminar de capturar el código, el sistema automáticamente intenta iniciar sesión.
    3. Si todo salió de forma correcta, el sistema muestra la página principal del panel de GitHub y con esto se da por concluido el proceso de activación y prueba de la autenticación en dos pasos de una cuenta GitHub con la ayuda de Google Authenticator.
