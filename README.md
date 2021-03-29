# PPLI-NEWS
Web y aplicación móvil para Plataforma por el Periodismo Libre e Independiente (PPLI NEWS)

Visita la web www.pplinews.tk

Descripción del proyecto web
Landing page SPA (Single Page Application) en javascript puro programado en HTML5, CSS3/SASS con base de datos XML codificada en UTF8 y Hexadecimal.
Siendo un medio periodístico digital que necesita de contínua actualización utiliza una base de datos a la que accede usando AJAX/Javascript decodificando hexadecimal a UTF8 debido a que incluye código HTML5 dentro del propio XML con el fin de integrar a la perfección ambos lenguajes de programación en un solo fichero de BBDD para la entradas de cada noticia para posteriores implementaciones de Backend en las que se admitirá uso de HTML5.

Descripción de la aplicación móvil (Android Nativo)
La aplicación inicia con un Splash Screeen en tiempo de carga con inicio de sesión con cuenta Google o e-mail haciendo uso de Firebase BBDD, en la que existen 2 tipos de usuarios con distintos privilegios, uno con derecho de lectura/escritura en la BBDD (administrador) y otro con derecho a lectura (usuario) que puede ver las noticias que publica el administrador y configurar su perfil de usuario en el menú de configuración así como guardar noticias publicadas en 'marcadores' para su posterior visualización. La aplicación estructura su interfaz por categorías de noticias ordenadas por fecha y permite su búsqueda haciendo uso de una barra de búsqueda. Está programadama en JAVA en entorno Android Studio.

Debido a incorporación tardía al curso por cambio de centro, al uso de tecnologías distintas a las cursadas y a la adaptación del proyecto al de I.E.S. Campanillas así como diversos cambios en el planteamiento del proyecto por petición del tutor el proyecto comienza su desarrollo en Enero de 2021.

Histórico de avances actualizado:

11/01/2021 al 17/01/2021:
Creación de los ficheros y directorios básicos del proyecto web.

18/01/2021 al 24/01/2021:
Desarrollo de iconos y apartados gráficos del proyecto web así como la sección HTML y SASS/CSS

Bibliografía utilizada:

Udemy: 
Curso Sass/CSS

Youtube: 
Vídeos búsqueda: "cómo compilar Sass/Css en linux" y "... con Plugin en VSCode".

25/01/2021 al 31/01/2021:
Continúa el proyecto CSS e implementaciones Javascript añadiendo efectos visuales.

En esta fase ya se ha concluido la incorporación de todos los requerimientos del proyecto:
- Uso de grid Layout/Area Layout.
- Media Querys responsivos en distintos tamaños adaptados a todos los dispositivos.
- Menú móvil y menú ordenador.
- Footer funcionando con flex-box.
- Incorporación de sonidos en la navegación y otros elementos multimedia.

Bibliografía utilizada:

W3Schools.com - tutoriales Css.

1/02/2021 al 7/02/2021:
Implementación de AJAX con BBDD en XML usando codificación Hexadecimal/UTF-8
Correcta implementación de la búsqueda de rutas XML ordenadas por filtro.

Bibliografía utilizada:
Foro en stackoverflow.com preguntas de otros usuarios.
W3Schools.com tutoriales XML path entre otros.

8/02/2021 al 14/02/2021:
Resolución de problemas y testeo general del diseño y de todas las funcionalidades.

15/02/2021 al 21/02/2021:
Creación de ficheros de redireccionamiento 404 y htaccess, creación de dominio y puesta
a punto del servidor host donde se ha alojado la web www.pplinews.tk, además de las 
respectivas configuraciones en el CDN Cloudflare.

Se ha realizado un testeo completo de la web online.

22/02/2021 al 28/02/2021:
Diseño de la aplicación móvil, se ha creado el splash screen en tiempo de carga al inicio de sesión
Se ha implementado el inicio de sesión con e-mail y google y se ha creado la BBDD en Firebase.

1/03/2021 al 7/03/2021:
Menú de usuario e interfaz en construcción.

8/03/2021 al 14/03/2021:
Resolución de incompatibilidades en Android Studio con paquetes afectados y actualizaciones pendientes.

15/03/2021 al 21/03/2021
En la App móvil las imágenes de los usuarios ahora se guardan en la BBDD de Firebase, nueva interfaz de usuario.
Queda finalizado el inicio de sesión de los usuarios y las configuraciones de gestión de cuentas en Firebase.

Bibliografía utilizada:

Stackoverflow:
https://es.stackoverflow.com/questions/411128/error-al-implementar-firebase-en-proyecto-android-studio

Android CodeLabs Developers:
https://developer.android.com/training/permissions/requesting

Firebase Studio Developers:
https://firebase.google.com/docs/auth/android/password-auth?hl=es
https://firebase.google.com/docs/storage/android/start?hl=es

Webs:
https://www.programcreek.com/ "com.google.firebase.auth.UserProfileChangeRequest"

Para cualquier duda o sugerencia: rsantiagoy.3ia@gmail.com, Slack, Telegram ó 620 859 904
